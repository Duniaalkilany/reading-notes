# **The Past, Present, and Future of Local Storage for Web Applications**

![img](https://lh3.googleusercontent.com/proxy/60mvE2xRP0tF8pra1S7_e5nC3fXuQ4upEHR8i09m4V1kLc2EIwq5ZOB7017Rfm_GgCG__BuOBvZFHkLKuRSCpFUFK5FWMRcEqGAKmsABXut8Zi0_M9m6F21TDRorlWn4V43QiGV0DCuoDoT0tB145w_AaW-h6Zb8lSVUO21QV-ZZOQtF8wPwgNaGH0CAtbPpHsfj7YGm5hVYfNrM25nYwAt3AFHVSm6F)

## **Historically,** web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

* ## Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over .
* ## Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).
* ## Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.


## What we really want is :

* a lot of storage space
* on the client
* that persists beyond a page refresh
* and isn’t transmitted to the server

**Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.**


# **INTRODUCING HTML5 STORAGE**

![img](https://csharpcorner.azureedge.net/UploadFile/cd7c2e/difference-between-local-storage-session-storage-ans-cookie/Images/WebStorageinHTML1.jpg)

 ## **what is HTML5 Storage?**

 ## Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

 ## **Which browsers?**

 ## the latest version of pretty much every browser supports HTML5 Storage… even Internet Explorer!

**HTML5 STORAGE SUPPORT**

**IE	FIREFOX	 SAFARI	 CHROME	 OPERA	IPHONE	ANDROID**

***8.0+	 3.5+	4.0+	4.0+	10.5+	2.0+	2.0+***

# **check for HTML5 Storage**

function supports_html5_storage() {

  try {

    return 'localStorage' in window && window[' localStorage'] !== null;

  } catch (e) {

    return false;

  }

}

# **USING HTML5 STORAGE**

![img](https://i.ytimg.com/vi/2hJ1rTANVnk/maxresdefault.jpg)

If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

interface Storage {

  getter any getItem(in DOMString key);

  setter creator void setItem(in DOMString key, in any data);

};

Calling setItem() with a named key that already exists will silently overwrite the previous value.

Calling getItem() with a non-existent key will return null rather than throw an exception.

Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets. For example, this snippet of code:

var foo = localStorage.getItem("bar");

// ...

localStorage.setItem("bar", foo);

…could be rewritten to use square bracket syntax instead:

var foo = localStorage[" bar"];

// ...

localStorage[" bar"] = foo;

There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

interface Storage {

  deleter void removeItem(in DOMString key);

  void clear();
};

Calling removeItem() with a non-existent key will do nothing.

Finally, there is a property to get the total number of values in the storage area, and to iterate through all of the keys by index (to get the name of each key).

interface Storage {

  readonly attribute unsigned long length;

  getter DOMString key(in unsigned long index);

};

**If you call key() with an index that is not between 0–(length-1), the function will return null.**

![img](imgs/180.png)


# **BEYOND NAMED KEY-VALUE PAIRS:** 

# COMPETING VISIONS

the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers, platforms, and devices. As a web developer, that’s just not something you see every day, is it? But there is more to life than “5 megabytes of named key/value pairs,” and the future of persistent local storage is… how shall I put it… well, there are competing visions.

**actual working code in 4 browsers**

openDatabase('documents', '1.0', 'Local document storage', 5*1024*1024, function (db) {

  db.changeVersion('', '1.0', function (t) {

    t.executeSql('CREATE TABLE docids (id, name)');

  }, error);

});

As you can see, most of the action resides in the string you pass to the executeSql method. This string can be any supported SQL statement, including SELECT, UPDATE, INSERT, and DELETE statements. It’s just like backend database programming, except you’re doing it from JavaScript! 

The Web SQL Database specification has been implemented by four browsers and platforms.

WEB SQL DATABASE SUPPORT

**IE	FIREFOX	SAFARI	CHROME	OPERA	IPHONE	ANDROID**

**·	·   	4.0+    	4.0+	    10.5+	     3.0+	   2.0**

![img](https://static.wixstatic.com/media/d69d56_9da5f74a004a4e7b885c9cf820ff2107~mv2.jpeg/v1/fill/w_230,h_210,al_c,q_90/d69d56_9da5f74a004a4e7b885c9cf820ff2107~mv2.jpeg)



### Sources:
* [The Past, Present, and Future of Local Storage for Web ApplicationsS](http://diveinto.html5doctor.com/storage.html)






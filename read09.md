# The Coder's Computer
![nn](https://images.techhive.com/images/article/2015/12/thinkstockphotos-489773763-100632538-large.jpg)
### What is a text editor?
A text editor is a piece of software that you download and install on your computer,or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a web site. The text editor has to be one of the most important tools you can use as an aspiring web developer.

### What are the different types of text editors?
* Visual Studio Code.
* Sublime Text.
* Notepad++
* Brackets.
* UltraEdit.
* Atom.
* TextEdit.
* gEdit

### What features should you look for in a text editor?
1.  code completion
2. syntax highlighting 
3.  a nice variety of themes (to reduce eye strain and fatigue)
4. the ability to choose from a healthy selection of extensions available when you need them. You might find some other features that are must-have’s, but I think these features are a good start.

### The Difference Between Text Editors and IDEs :

* A text editor kind of gives away what it does in the title—it edits text.
It also manages text, and manages files. I love that name “text
wrangler” because in a way that’s what really a text editor does. It
wrangles your text together into something meaningful.

* An IDE (Integrated Development Environment) is really a suite of
different software all coming together. An IDE is a text editor, a file
manager, a compiler, and a debugger all in one software package.

![img](https://miro.medium.com/max/1140/1*21oUCQRxP7aL2U1zO_XSvg.jpeg)

# The Command Line!
![i](https://i.ytimg.com/vi/cBokz0LTizk/maxresdefault.jpg)
**Your window into the computer.**
The command line is an interesting beast, and if you've not used one before, can be a bit daunting. 
## *So what are they exactly?*
A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.The command line typically presents you with a prompt. As you type, it will be displayed after the prompt.

## *Opening a Terminal*
* If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.
* If on Linux then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'.
* If you are on Windows and intend to remotely log into another machine then you will need an SSH client. A rather good one is Putty (free) .

## *The Shell, Bash*
If you would like to know which shell you are using you may use a command called echo to display a system variable stating your current shell. echo is a command which is used to display messages.
![img](C:\Users\Student\Desktop)

### *Shortcuts*
The terminal may seem daunting but don't fret. Linux is full of shortcuts to help make your life easier. You'll be introduced to several of them throughout this tutorial. Take note of them as not only do they make your life easier, they often also save you from making silly mistakes such as typos.

# Basic Navigation!
![bb](https://i.ytimg.com/vi/7FlnF7Gn2So/maxresdefault.jpg)
*explore the system*

1. What's in Our Current Location? ***PWD COMMAND :***
The first command we are going to learn is **pwd** which stands for Print Working Directory. (You'll find that a lot of commands in linux are named as an abbreviation of a word or words describing them. This makes it easier to remember them.) The command does just that. It tells you what your current or present working directory is. Give it a try now.

**user@bash:pwd**
**home/ryan**
**user@bash:**


2. What's in Our Current Location? ***ls command:***
It's one thing to know where we are. Next we'll want to know what is there 
**user@bash:ls**
**bin Documents public_html**
**user@bash:**

3. Let's Move Around a Bit ***cd command:***
In order to move around in the system .
**cd [location]**

# More About Files!

***Everything is a File*** 
Ok, the first thing we need to appreciate with linux is that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc. To begin with, this won't affect what we do too much but keep it in mind as it helps with understanding the behaviour of Linux as we manage files and directories.

* Linux is Case Sensitive :

**user@bash:**ls Documents
FILE1.txt File1.txt file1.TXT
...
**user@bash:**file Documents/file1.txt
Documents/file1.txt: ERROR: cannot open 'file1.txt' (No such file or directory)


* Spaces in names
Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items. They are how we know what is the program name and can identify each command line argument. If we wanted to move into a directory called Holiday Photos for example the following would not work.

**user@bash:**ls Documents
FILE1.txt File1.txt file1.TXT Holiday Photos
...
**user@bash:**cd Holiday Photos
bash: cd: Holiday: No such file or directory

* Quotes
The first approach involves using quotes around the entire item. You may use either single or double quotes (later on we will see that there is a subtle difference between the two but for now that difference is not a problem). Anything inside quotes is considered a single item.

**user@bash:**cd 'Holiday Photos'
**user@bash:**pwd
/home/ryan/Documents/Holiday Photos

* Escape Characters
Another method is to use what is called an escape character, which is a backslash ( \ ). What the backslash does is escape (or nullify) the special meaning of the next character.

**user@bash:**cd Holiday\ Photos
**user@bash:**pwd
/home/ryan/Documents/Holiday Photos

* Hidden Files and Directories
To make a file or directory hidden all you need to do is create the file or directory with it's name beginning with a . or rename it to be as such. Likewise you may rename a hidden file to remove the . and it will become unhidden. The command ls which we have seen in the previous section will not list hidden files and directories by default. We may modify it by including the command line option -a so that it does show hidden files and directories.

**user@bash:**ls Documents
FILE1.txt File1.txt file1.TXT
...
**user@bash:**ls -a Documents
. .. FILE1.txt File1.txt file1.TXT .hidden .file.txt
...
![nn](https://www.onlogic.com/company/io-hub/wp-content/uploads/2016/08/Blog-Cover-Image-Linux-Bash.jpg)

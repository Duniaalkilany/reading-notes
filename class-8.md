## **APIs**

![img](https://i2.wp.com/www.learnsteps.com/wp-content/uploads/2017/12/apis.png?fit=722%2C449&ssl=1)




## **What does REST stand for?**

### REST or RESTful API design (Representational State Transfer) is designed to take advantage of existing protocols. ... This means that developers do not need to install libraries or additional software in order to take advantage of a REST API design.


## **REST APIs are designed around a :**

### Resources, which are any kind of object, data, or service that can be accessed by the client.


## **What is an identifer of a resource? Give an example ?**

### which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

### **https://adventure-works.com/orders/1**

## **What are the most common HTTP verbs?**

### he primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively.

![img](https://miro.medium.com/max/1324/1*OdQfB6npJJtjMDDoRzehVw.png)

## **What should the URIs be based on?**

### URIs should be based on nouns and NOT verbs.


## **Give an example of a good URI**
### Example:

**https://adventure-works.com/orders**


## **What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?##

### Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation.

### SO That’s means the web APIs that expose a large number of small resources.And it’s a bad thing we should try to avoid chatty web APIs.

## **What status code does a successful GET request return?**
### returns HTTP status code 200 (OK)

## **What status code does an unsuccessful GET request return?**
### It’s return 404 (Not Found).

## **What status code does a successful POST request return?**
### It’s return HTTP status code 200.

## **What status code does a successful DELETE request return?**
### It’s respond with HTTP status code 204.

![img](https://s3.us-west-1.wasabisys.com/idbwmedia.com/images/api/twitter_statuscodes.png)

## Things I want to know more about

I want to know more about REsT and HTTP methods .

## Sources:
* [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)



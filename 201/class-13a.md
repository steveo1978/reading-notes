# Reading Notes Class 13a

  ## Local Storage

  ### The Past, Present, and Future of Local Storage for Web Applications

  Persistant Local Storage is one of the areas where native client applications, have held an advantage over web applications. Cookies were invented early in the web's history, and can be used for persistant local storage of small amounts of data. There are 3 deal breakers they are as follows :

   - Cookies are included with every HTTP request thereby slowing down your web application by needlessly transmitting the same data over and over.

   - Cookies are included with every HTTP request, thereby sending data unencripted over the internet //(//unless your entire web application is served over SSL //)//

   - Cookies are limited to about 4KB of data - enough to slow down your application //(//see above//)//, but not enough to be terribly useful.

What we really want is as follows :

   - A lot of storage space
   - On the client
   - That persists beyond a page refresh
   - And that it isn't transmitted to the server

## Brief history before HTML5

In the beginning there was only Internet Explorer. To that end, as part of the first great browser wars, Microsoft invented a browser-to-end-all-browser-wars, Internet Explorer. One of the things it used was DHTML behaviors, and one of the behaviors was called userData. UserData allows web pages to store up to 64KB of data per domain, in hierarchical XML-based structure.

In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of **Flash Cookies**. Flash gives each domain 100KB of storage **For Free**. Beyond that, it prompts the user for each order of magnitude increase in data storage //(1MB, 10MB, and so on.//)

In 2007, **GOOGLE** launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers. After obtaining permission from the user once, Gears can store unlimited amounts of data per domain in SQL database tables.

All of them are either specific to a single broswer, or reliant on a third-party plugin. So this is the problem that HTML5 set out to solve: **To provide a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins**

## Introducing HTML5 Storage

HTML5 storage is a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close the browser tab, or even exit the browser. But unlike cookies, this data is never transmitted to the remote web server.

   - The following browsers support HTML5 Storage :

       ``HTML5 Storage Support``
``IE   FireFox   Safari   Chrome   Opera   IPhone  Android``
``8.0     3.5+     4.0+     4.0+    10.5+    2.0+     2.0+``


## Using HTML5 Storage

HTML5 storage is based on named key/value pairs. You store data based on named key, then you can retrieve that data with the same key. The named key is a string. That data can be any type supported by JavaScript, including strings, Booleans, intergers, or floats. The data is actually stored as a string.


## Tracking Changes To The HTML5 Storage Area

If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever **setItem()**, **removeItem()**, or **clear()** is called and *actually changes something*. The Storage event is supported everywhere the **localStorage** object is supported, which includes IE 8. The Storage event is not cancelable.


## Limitations in Current Browsers

**5 Megabytes** is how much storage space each origin gets by default. This is consistent across all browsers. If you're storing a lot of intergers or floats, the difference in representation can really add up. Each digit in that float is being stored as a character, not in the usual representation of a floating point number.

**QUOTA_EXCEEDED_ERR** is the exception that will get thrown if you exceed your storage quotaof 5 megabytes. No browser supports any mechanism for web developers to request more storage space. Some broswers allow the user to control each site's storage quota, but it's purely a user-initiated action, not something that you as a web developer can build into your web application.


## HTML5 Storage in Action

With HTML5 storage, we can save your browser progress locally, within the browser itself. It uses the **localStorage** object to save whether there is something like a game in progress. 





[Click here to return to the table of Contents](class-13a.md)
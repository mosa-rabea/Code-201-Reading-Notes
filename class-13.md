# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS: 

* ### persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

# HTML5 Storage:
#### Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser, Like cookies .

------------------------------------
# localStorage in JavaScript :

#### localStorage is a property that allows JavaScript sites and apps to save key-value pairs in a web browser with no expiration date. This means the data stored in the browser will persist even after the browser window is closed.

------------------------------------
# How does localStorage work?

##### To use localStorage in your web applications, there are five methods to choose from:
* setItem(): Add key and value to localStorage
* getItem(): This is how you get items from localStorage
* removeItem(): Remove an item by key from localStorage
* clear(): Clear all localStorage
* key(): Passed a number to retrieve the key of a localStorage .
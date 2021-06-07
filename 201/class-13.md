# Reading
## [“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)


* ersistent local storage is one of the areas where native client applications have held an advantage over web application

* potentially dealbreaking downsides:
  1. thereby slowing down your web application by needlessly transmitting the same data over and over

  2. thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

  3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful


### HTML5 Storage

- *Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually).*



- Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.


- HTML5 Storage is based on named key/value pairs

- you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.


- There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

  - interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};


- he storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.


|PROPERTY|	TYPE|	DESCRIPTION|
|--------|------|--------------|
|key	|string	the named key that was added, removed, or modified|
|oldValue|any	the previous value (now overwritten), or null if a new itemwasadd|
|newValue|	any	the new value, or null if an item was removed|
|url*|	string	the page which called a method that triggered this change|


* 5 megabytes” is how much storage space each origin gets by default.

* UOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes

- with HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. 

- instead of automatically calling a newGame() function that would reset these variables to hard-coded values, we call a resumeGame() function instead.

- The Indexed Database API exposes what’s called an object store.

- as a web developer At the moment, virtually you cant do nothing beyond some technology demos.


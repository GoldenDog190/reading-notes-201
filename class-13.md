# Online Article Reading Summary

## [“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html) 

**Persistant Local Storage**
- Persistant Local Storage: is one of the areas where native client applications have held an advantage over web applications.
- Native applications: the operating system typically provides an abstract layer for storing and retrieving applocation-specific data.
  * if native application needs local storage beyond key value pairs, you can embed own database, invent file format, etc
- Cookies: invented early in web history, and can be used for persistant local storage of small amounts of data.
  * downside: included with every HTTP request and limited to 4KB of data.
- What we really want: a lot of storage space on the client that persists beyond a page refreash and isn't transmitted to server, which before HTML5 was unsatisfactory.

**Storage Hacks before HTML5**
- Microsoft first manily pushed Internet Explorer
- In 2002 Adobe introduced Flash 6, and then ExternalInterface in Flash 8
- In 2007 Google launched Gears

**HTML5 Storage**
- Meant to provide a standard API, implement natively and consistant multiple browsers, without having to rely on third-part plugins.
- HTML5 storage is also refered to as web storage, local storage, or DOM storage.
- HTML5 storage is a way for web pages to store key value pairs locally, within the client web browser. You store data based on a named key, then retrieve that data with the same key. The name key is a string.
- Tracking changes can be done by setting a trap for the storage event.
- Limitations:  5 megabytes of storage by default and your storing strings, not data in its original format.
- Can save progress locally, within the browser itself.
- With HTML5 a new API has been standardized and implemented across all browsers, platforms, and devices.
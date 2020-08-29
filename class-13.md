# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

- Native client applications have held an advantage over web applications. 

- The operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state.

- Web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.

- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).

- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.

## A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5

- In the beginning there was Microsoft and everyody else.

- Microsoft developedOne a thing called DHTML Behaviors, and one of these behaviors was called `userData`.

- `userData` allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.

- In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers.

- Gears provides an API to an embedded SQL database based on SQLite. 

## INTRODUCING HTML5 STORAGE

- HTML5 - is a way for web pages to store named key/value pairs locally, within the client web browser.

## USING HTML5 STORAGE

- Calling `setItem()` with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception.

- Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the `getItem()` and `setItem()` methods, you can simply use square brackets.

## LIMITATIONS IN CURRENT BROWSERS

- “5 megabytes” is how much storage space each origin gets by default. Storing strings or floats can add up quickly.

- “QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes.

- "no" is the answer you get when you ask for more.

## HTML5 STORAGE IN ACTION

- With HTML5 Storage, we can save the progress locally, within the browser itself.
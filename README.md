```
                         ,ad8888ba,            
                        d8"'    `"8b           
                       d8'        `8b     
  ,adPPYba,            88          88          
 a8"     "8a           88          88     
 8b       d8           Y8,        ,8P          
 "8a,   ,a8"            Y8a.    .a8P           
  `"YbbdP"'              `"Y8888Y"'            

            888888888888                       
```

FunnyFace.js     
============

HTML binding for Lulz 

Tiny, elegant & flexible html binding

Provides an easy to bind an object to a section of HTML

Proxies through $ (jQuery or ...)

Built in automatic dependency resolution makes hooking up code a dream

(c) 2012 by weepy, MIT Licensed



Simple Example
--------------

```
<div id=person bind='text: this'></div>

var name = o_O.property('John')

o_O.bind(name, '#person')

// HTML text is now 'John'

name('Bob')

// HTML text is now 'Bob'

```

Further Examples
----------------

See folder examples

Features
--------

* o_O.property      : evented properties with automatic dependency resolution
* o_O.bind          : bind an object to a section of HTML with 'bind' attributes
* o_O.collection    : a simple collection of objects
* o_O.klass         : a simple klass with o_O.property


Running Tests
-------------

either just run

mocha

or open test/mocha.html

Compatability
-------------

Tested in IE 7,8,9, Chrome 16, Firefox 4 and Safari 5

Todo
----

* Website
* Update bindings after a setTimeout to throttle multiple calls?

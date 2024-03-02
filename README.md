# VirtualXposedFrida
Virtual Xposed Frida is an aplication that implement frida for instrumentation, this virtual auto run the gadget on the startup of any aplication inside of the virtual, making it be possible to run tests on non rooted device without repacking the apk, bypassing signature tests, and others kinds of detection.

just add your target on the app then you can play with it :)

#Note
the target aplication will be black screen, because its gadget will be awaiting for a frida iteraction.

#Iteration example
usb
```
frida -U -n "Gadget" -l yourscript.js
```

### Limitations
1 - this aplication only support arm64 for now.

2 - you can only instrumentate one aplication per time.

### Why to use?
Thats simple, dont waste your time repacking others aplication, while you can run the original one.

### Releases:
https://github.com/publicresources/VirtualXposedFrida/releases


#### Note
this is a resigned version of virtual xposed, nothing else was changed only the part where the library is loaded into in the aplication.
the credits and support must be to the original authors.
https://virtualxposed.com/


### Details
frida gadget version 16.2.1
virtual xposed version 0.18.2

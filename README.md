# VirtualXposedFrida
Virtual Xposed Frida is an aplication that implement frida for instrumentation, this virtual auto run the gadget on the startup of any aplication inside of the virtual, making it be possible to run tests on non rooted device without repacking the apk, breaking the signature 

just add your target on the app then you can play with it :)

#Note
the target aplication will be black screen, because its the gadget awaiting for a frida iteraction.

#Iteration example
usb
```
frida -U -n "Gadget" -l yourscript.js
```

# Limitations
1 - this aplication only support arm64 for now.

2 - you can only instrumentate one aplication per time.



# Releases:
https://github.com/publicresources/VirtualXposedFrida/releases

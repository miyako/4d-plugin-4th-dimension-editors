4d-plugin-4th-dimension-editors
===============================

This is a simple wrapper of the [PA_MethodEditor](http://sources.4d.com/trac/4d_4dpluginapi/wiki/CMU84350.HTM) entry point.

On v13 and later, you should really use the native command [METHOD OPEN PATH](http://doc.4d.com/4D-Language-Reference-13.5/Design-Object-Access/METHOD-OPEN-PATH.301-1458472.en.html).

```
$methodName:="Method1"
$lineNumber:=1

PA OPEN METHOD EDITOR ($methodName;$lineNumber)
```

Platform
--------

Tested 4D v12.6 OS X 10.9.4 and Windows 7.
Should be compatible with v11 and later.

Compiled for Mac i386 (32/64 bits), Windows (32/64 bits).
For PPC version please compiled from source.

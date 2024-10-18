MiniJGL - A continuation of Lightweight Java Game Library 2
======

MiniJGL is a continuation of LWJGL2, as well as a project to increase the range of OS and Architecture compatibility. Windows 95 was successfully tested. Future platform plans are:

Windows 95-11:
 - x86 ANSI
 - x86 Unicode
 - x64 Unicode
Linux:
 - x64
 - x86
 - ARM64
Solaris 8-11:
 - x86
 - x64
 - SPARC
 - SPARCv9
Mac OS X 10.4-???
 - PowerPC
 - x64

Other systems might enter this list as we obtain them, but currently these are the only machines we own.
There are also plans to introduce new graphics APIs, such as Vulkan. 


LWJGL is Copyright (c) 2002-2007 Lightweight Java Game Library Project All rights reserved. MiniJGL is not affiliated with LWJGL.


The Lightweight Java Game Library (LWJGL) is a solution aimed directly at professional and amateur Java programmers alike to enable commercial quality games to be written in Java. 
LWJGL provides developers access to high performance crossplatform libraries such as OpenGL (Open Graphics Library), OpenCL (Open Computing Language) and OpenAL (Open Audio Library) allowing for state of the art 3D games and 3D sound.
Additionally LWJGL provides access to controllers such as Gamepads, Steering wheel and Joysticks.
All in a simple and straight forward API.

Compilation
-----------

MiniJGL requires JDK 5-7 and Ant installed to compile, as well as your platforms native compiler to compile the JNI. Currently, "apt", or the "Annotation Processing Tool" is used to process annotations. This is why JDK5-7 are required, as JDK8+ have removed this tool. This will change in the future, while still maintaining Java 5 compatibility to increase the range of supported systems as much as possible.

* ant generate-all
* ant compile
* ant compile_native

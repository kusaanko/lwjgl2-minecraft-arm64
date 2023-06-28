[LEGACY] LWJGL - Lightweight Java Game Library
======

> **WARNING**
> 
> This is the repository of the original LWJGL, which is no longer actively maintained. Unless you have released a product that uses LWJGL 2.x, you should probably be looking at [LWJGL 3](https://github.com/LWJGL/lwjgl3).

The Lightweight Java Game Library (LWJGL) is a solution aimed directly at professional and amateur Java programmers alike to enable commercial quality games to be written in Java. 
LWJGL provides developers access to high performance crossplatform libraries such as OpenGL (Open Graphics Library), OpenCL (Open Computing Language) and OpenAL (Open Audio Library) allowing for state of the art 3D games and 3D sound.
Additionally LWJGL provides access to controllers such as Gamepads, Steering wheel and Joysticks.
All in a simple and straight forward API.

Website: [http://legacy.lwjgl.org](http://legacy.lwjgl.org)
Forum: [http://forum.lwjgl.org](http://forum.lwjgl.org)
Bugs/Suggestions: [https://github.com/LWJGL/lwjgl/issues](https://github.com/LWJGL/lwjgl/issues)

# What is this?
This is for Minecraft older than 1.7 on Apple Silicon Macs.

This works with arm64 and x86_64 JDK 1.8 and macOS 10.9 or later.

# Environment
- Xcode
- JDK 1.8 x86_64 (Zulu is recommended)
- JDK 1.8 arm64 (Zulu is recommended)
- ant

Compilation
-----------

LWJGL requires a JDK and Ant installed to compile, as well as your platforms native compiler to compile the JNI.

```bash
export JAVA_HOME_x86_64={Your jdk x64 path}
export JAVA_HOME_arm64={Your jdk arm64 path}
export JAVA_HOME={Your jdk ant archtecture path}
/usr/libexec/java_home -v "Your version"
ant generate-all
ant compile
ant compile_native
```

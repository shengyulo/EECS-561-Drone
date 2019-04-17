# EECS-561-Drone
Drone Project

## Matlab Version
+ Matlab version is prefered of `2018b` or later.

## Install Matlab package
+ Aerospace Blockset
+ Optimization Toolbox
+ Simulink Control Design
+ Signal Processing Toolbox
+ Computer Vision Toolbox
+ Simulink 3D Animation

## Install MinGW-w64 C/C++ Compiler

1. [Download](http://sourceforge.net/projects/tdm-gcc/files/TDM-GCC%20Installer/tdm64-gcc-5.1.0-2.exe/download)
2. Install MinGW and follow the procedure show on the screen. Note, check the box `"Check for updated files on the TDM-GCC server"`.
3. Create and select `MinGW-w64/TDM64(32-bit and 64 bit)`
5. In Matlab command line, type (`C:\TDM-GCC-64` should be the folder where you install MinGW)
``` matlab
setenv('MW_MINGW64_LOC','C:\TDM-GCC-64')
```
6. In command line, type
``` matlab
mex -setup
```
You should see the following message shows up which means you are done.
``` matlab
MEX configured to use 'MinGW64 Compiler (C)' for C language compilation.
```

## Open Quadcopter Project

1. In command line, type
``` matlab
asbQuadcopterStart
```
2. Wait for initialization

# 3rdParty

This repository contains a bunch of library as prebuilt binaries.  

## Structure

Each folder contains files as follow. Basically, I only include x64 binaries and do not support Win32 binaries.  

- include: header files (*.h)  
- bin64: dynamic linking library (*.dll)  
- lib/x64: shared library (*.lib)  

## Library list

- [GLFW-3.3.0](https://www.glfw.org/download.html)
- [GLEW-2.1.0](http://glew.sourceforge.net/)
- [OpenCV-2.4.13.6](https://opencv.org/releases/): it only contains minimum modules.
  + 3 mandatories: core, imgproc, highgui  
  + 4 optional modules for camera calibration, etc.: calib3d, features2d, flann, ml  
- [AntTweakBar-1.16b](https://github.com/stnoh/AntTweakBar): This is compiled by VS2015, with fixes for GLFW3  

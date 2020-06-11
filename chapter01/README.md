chapter01 - glslcookbook
===============

Chapter 1. Getting Started with GLSL <br/>

In this chapter, we will cover the following recipes:  <br/>
- Using a function loader to access the latest OpenGL functionality 
- Using GLM for mathematics 
- Determining the GLSL and OpenGL version 
- Compiling a shader 
- Linking a shader program 
- Sending data to a shader using vertex attributes and vertex buffer objects 
- Getting a list of active vertex input attributes and locations
- Getting debug messages 
- Building a C++ shader program class

### build sample code
g++ src/*.cpp  ../ingredients/*.cpp ../glad/glad.c  -std=c++11  -framework OpenGL `pkg-config --cflags --libs glfw3` `pkg-config --cflags --libs glm` -I../ingredients -I../include <br/>

### run sample code
Usage: ./a.out recipe-name <br/>

Recipe names:  <br/>
- basic : Basic scene. <br/>
- basic-attrib : Prints active attributes. <br/>
- basic-debug : Display debug messages. <br/>
- basic-uniform : Basic scene with a uniform variable. <br/>
- basic-uniform-block : Scene with a uniform block variable. <br/>

result : basic <br/>
<image src="https://raw.githubusercontent.com/ohwada/MAC_OpenGL_SL_Cookbook/master/chapter01/result/screenshot_basic.png" width="300" /><br/>


### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter01


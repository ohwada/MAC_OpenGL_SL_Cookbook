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
- ads : Ambient, diffuse, and specular shading. <br/>
- diffuse : Diffuse shading only <br/>
- discard : Example of discarding fragments <br/>
- flat : Flat shading <br/>
- subroutine : Using a shader subroutine <br/>
- two-side : Two-sided lighting <br/>



### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter01


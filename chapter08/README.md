chapter08 - glslcookbook
===============

Chapter 8. Using Noise in Shaders  <br/>
In this chapter, we will cover: <br/> 
- Creating a noise texture using GLM 
- Creating a seamless noise texture 
- Creating a cloud-like effect Creating a wood-grain effect 
- Creating a disintegration effect Creating a paint-spatter effect 
- Creating a night-vision effect

### build sample code
g++ src/*.cpp  ../ingredients/*.cpp ../glad/glad.c  -std=c++11  -framework OpenGL `pkg-config --cflags --libs glfw3` `pkg-config --cflags --libs glm` -I../ingredients -I../include <br/>

### run sample code
Usage: ./a.out recipe-name <br/>

Recipe names:  <br/>
- decay : decay of a teapot <br/>
- night-vision : night vision goggles <br/>
- noise : just display the raw noise texture <br/>
- paint : paint spatters on a teapot <br/>
- sky : clouds and sky <br/>
- wood : wood  <br/>


### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter08


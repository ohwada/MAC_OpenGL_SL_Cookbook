chapter02 - glslcookbook
===============

Chapter 2. The Basics of GLSL Shaders <br/>
In this chapter, we will cover:  <br/>
- Implementing diffuse, per-vertex shading with a single point light source 
- Implementing per-vertex ambient, diffuse, and specular (ADS) shading Using functions in shaders 
- Implementing two-sided shading Implementing flat shading 
- Using subroutines to select shader functionality 
- Discarding fragments to create a perforated look

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


### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter02


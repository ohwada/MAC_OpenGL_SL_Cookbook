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
- ads : Ambient, diffuse, and specular shading. <br/>
- diffuse : Diffuse shading only <br/>
- discard : Example of discarding fragments <br/>
- flat : Flat shading <br/>
- subroutine : Using a shader subroutine <br/>
- two-side : Two-sided lighting <br/>

result : ads <br/>
<image src="https://raw.githubusercontent.com/ohwada/MAC_OpenGL_SL_Cookbook/master/chapter02/result/screenshot_ads.png" width="300" /><br/>


### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter02


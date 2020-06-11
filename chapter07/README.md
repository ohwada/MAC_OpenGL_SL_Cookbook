chapter07 - glslcookbook
===============

Chapter 7. Shadows  <br/>
In this chapter, we will cover:   <br/>
- Rendering shadows with shadow maps 
- Anti-aliasing shadow edges with PCF 
- Creating soft shadow edges with random sampling 
- Creating shadows using shadow volumes and the geometry shader


### build sample code
g++ src/*.cpp  ../ingredients/*.cpp ../glad/glad.c  -std=c++11  -framework OpenGL `pkg-config --cflags --libs glfw3` `pkg-config --cflags --libs glm` -I../ingredients -I../include  <br/>

### run sample code
Usage: ./a.out recipe-name  <br/>

Recipe names:  <br/> 
- ao : Ambient occlusion from a texture  <br/>- jitter : Blur shadow map edges using a random jitter  <br/>
- pcf : Blur shadow map edges using percentage-closer-filtering  <br/>
- shadow-map : Simple shadow map  <br/>
- shadow-volume : Shadow Volumes using geometry shader.  <br/>

result : ao <br/>
<image src="https://raw.githubusercontent.com/ohwada/MAC_OpenGL_SL_Cookbook/master/chapter07/result/screenshot_ao.png" width="300" /><br/>


### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter07


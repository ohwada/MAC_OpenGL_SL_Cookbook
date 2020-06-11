chapter03 - glslcookbook
===============

Chapter 3. Lighting, Shading, and Optimization <br/>
 
In this chapter, we will cover:  <br/>
- Shading with multiple positional lights 
- Shading with a directional light source 
- Using per-fragment shading for improved realism 
- Using the halfway vector for improved performance 
- Simulating a spotlight 
- Creating a cartoon shading effect Simulating fog


### build sample code
g++ src/*.cpp  ../ingredients/*.cpp ../glad/glad.c  -std=c++11  -framework OpenGL `pkg-config --cflags --libs glfw3` `pkg-config --cflags --libs glm` -I../ingredients -I../include <br/>

### run sample code
Usage: ./a.out recipe-name <br/>

Recipe names:  <br/>
- directional : Directional light source <br/>
- fog : Fog <br/>
- multi-light : Multiple light sources <br/>
- per-frag : Per-fragment shading <br/>
- spot : Spot light <br/>
- toon : Toon shading <br/>

result : directional <br/>
<image src="https://raw.githubusercontent.com/ohwada/MAC_OpenGL_SL_Cookbook/master/chapter03/result/screenshot_directinal.png" width="300" /><br/>


### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter03


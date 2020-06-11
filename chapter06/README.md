chapter06 - glslcookbook
===============

Chapter 6. Using Geometry and Tessellation Shaders  <br/>
In this chapter, we will cover:  <br/>
- Point sprites with the geometry shader 
- Drawing a wireframe on top of a shaded mesh 
- Drawing silhouette lines using the geometry shader 
- Tessellating a curve 
- Tessellating a 2D quad Tessellating a 3D surface 
- Tessellating based on depth


### build sample code
g++ src/*.cpp  ../ingredients/*.cpp ../glad/glad.c  -std=c++11  -framework OpenGL `pkg-config --cflags --libs glfw3` `pkg-config --cflags --libs glm` -I../ingredients -I../include <br/>

### run sample code
Usage: ./a.out recipe-name <br/>

Recipe names:  <br/>
- bez-curve : 2D Bezier curve with tessellation shader <br/>
- point-sprite : Point sprites with the geometry shader <br/>
- quad-tess : Demonstrates how quad tessellation works <br/>
- shade-wire : Uses the geometry shader to draw a mesh over a shaded object <br/>
- silhouette : Uses the geometry shader to draw silhouette edges <br/>
- tess-teapot : Uses tessellation to draw a teapot <br/>
- tess-teapot-depth : Varies the amount of tessellation with depth <br/>

result : bez-curve <br/>
<image src="https://raw.githubusercontent.com/ohwada/MAC_OpenGL_SL_Cookbook/master/chapter05/result/screenshot_bez_curve.png" width="300" /><br/>


### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter06


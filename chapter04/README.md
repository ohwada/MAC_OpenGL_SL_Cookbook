chapter04 - glslcookbook
===============

Chapter 4. Using Textures  <br/>

In this chapter, we will cover:  <br/>
- Applying a 2D texture 
- Applying multiple textures Using alpha maps to discard pixels - Using normal maps Simulating reflection with cube maps - Simulating refraction with cube maps Applying a projected texture Rendering to a texture 
- Using sampler objects
 

### build sample code
g++ src/*.cpp  ../ingredients/*.cpp ../glad/glad.c  -std=c++11  -framework OpenGL `pkg-config --cflags --libs glfw3` `pkg-config --cflags --libs glm` -I../ingredients -I../includee <br/>

### run sample code
Usage: ./a.out recipe-name <br/>

- alpha-test : Discard fragments based on an alpha test. <br/>
- multi-tex : Multiple textures <br/>
- normal-map : Normal map <br/>
- proj-tex : Projected texture <br/>
- reflect-cube : Reflection with a cube map <br/>
- refract-cube : Refraction with a cube map <br/>
- render-to-tex : Render to a texture using framebuffer objects <br/>
- sampler-obj : Sampler objects <br/> 
- texture : Basic texture mapping <br/>

### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter04


chapter05 - glslcookbook
===============

Chapter 5. Image Processing and Screen Space Techniques <br/>

In this chapter, we will cover:  <br/>
- Applying an edge detection filter 
- Applying a Gaussian blur filter 
- Implementing HDR shading with tone mapping 
- Creating a bloom effect 
- Using gamma correction to improve image quality 
- Using multisample anti-aliasing 
- Using deferred shading


### build sample code
g++ src/*.cpp  ../ingredients/*.cpp ../glad/glad.c  -std=c++11  -framework OpenGL `pkg-config --cflags --libs glfw3` `pkg-config --cflags --libs glm` -I../ingredients -I../include <br/>

### run sample code
Usage: ./a.out recipe-name <br/>

Recipe names:  <br/>
blur : Gaussian blur <br/>
- deferred : deferred rendering <br/>
- edge : edge detection filter <br/>
- gamma : gamma correction <br/>
- hdr-bloom : bloom example with HDR tone mapping. <br/>
- msaa : multisample anti-aliasing <br/>
- oit : order independent transparency (requires OpenGL 4.3) <br/>
oit example is not supported on MacOS. <br/>
- tone-map : tone mapping example. <br/>

result : blur <br/>
<image src="https://raw.githubusercontent.com/ohwada/MAC_OpenGL_SL_Cookbook/master/chapter05/result/screenshot_blur.png" width="300" /><br/>


### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter05


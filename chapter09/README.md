chapter09 - glslcookbook
===============

Chapter 9. Particle Systems and Animation  <br/>
In this chapter, we will cover:  <br/>
- Animating a surface with vertex displacement 
- Creating a particle fountain 
- Creating a particle system using transform feedback 
- Creating a particle system using instanced particles 
- Simulating fire with particles 
- Simulating smoke with particles
 
### build sample code
g++ src/*.cpp ../ingredients/*.cpp  ../glad/glad.c  -std=c++11  -framework OpenGL `pkg-config --cflags --libs glfw3` `pkg-config --cflags --libs glm`  -I../ingredients -I../include <br/>

### run sample code
Usage: ./a.out recipe-name <br/>

Recipe names:  <br/>
- fire : particles simulating fire <br/>
- particles : a fountain of particles <br/>
- particles-feedback : a fountain of particles implemented with transform feedback <br/>
- particles-instanced : a fountain of instanced particles, mmmm.. donuts <br/>
- smoke : particles simulating smoke <br/>
- wave : a plane wave displacement animation <br/>



### Reference <br/>
- https://www.opengl.org/
- https://github.com/daw42/glslcookbook/tree/master/chapter09


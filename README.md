# lzha0267_9103_tut6

### Part 1: Imaging Technique Inspiration

The example creates an elegant visual effect using particles moving like **circular random walkers**. I am inspired primarily by how **particle system** combines **circular motion** with **brightness detection**. As particles move in smooth, circular paths, they dynamically react to the brightness of the underlying image. If the brightness is relatively high, the particles bounce off, changing direction and speed accordingly, adding depth and complexity to the artwork.  

This technique aligns with the assignment requirements, as the particle system rebuilds the image by **dynamically weaving it** together in an interesting and graceful way, forming a complete picture through motion.  

![Circular random walker 1](images/circular_random_walker_1.png)
*Figure 1: Particles moving in circular motion in response to image brightness*

![Circular random walker 2](images/circular_random_walker_2.png)
*Figure 2: Particles recreating the image*

---

### Part 2: Coding Technique Exploration

To achieve the **circular random walkers** effect, I explored the **particle system**.  

> *“A particle system is a collection of many, many minute particles that together represent a fuzzy object.” -- William T. Reeves*  

Each particle is an independent body with properties like **position, velocity, and acceleration**. These particles move dynamically across the canvas, responding to **forces** such as gravity, wind, or, in this case, image brightness.  

By continuously updating each particle’s position and direction, the system creates an evolving pattern that adapts to the image. This technique allows for flexibility in controlling the behaviour of the particles, ensuring smooth movement with the underlying image.  

Here is the example implementation of [Particle System](https://editor.p5js.org/soh25@sva.edu/sketches/B1KK2I1k4).  

![Particle System example](images/particle_system.png)
*Figure 3: Particle system example showing dynamic patterns*
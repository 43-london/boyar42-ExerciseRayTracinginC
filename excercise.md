# Exercise

##Exercise: Ray Tracing in C

Create a simple ray tracing program that can render basic 3D scenes with spheres. The skies the limit but here are some of the functionalities you should aim to implement:

1. Cast rays from a viewpoint into a scene with a sphere.
2. Detect intersections between rays and spheres in the scene.
3. Simulate the propagation of light in the scene by sending secondary rays from the intersection points to the light source.
4. Shade the intersection points depending on the direction of the normal at the intersection point, the direction of the light and the direction of the ray that was originally cast from the viewpoint to the sphere.
5. Store the image data in a suitable format (e.g., PPM).

Here’s how it should be prototyped:

`void ray_tracer(void);`

Some testable goals: 
1. A scene with a single sphere that's being light up by a light source.
2. A scene with multiple spheres that's being light up by a light source. Balls can have reflective, clear or shiny texture.
3. A scene with spheres and one or multiple light source creating shadow effects.
4. A scene where light bounces off the sphere into different directions.

Note: 
This is a more advanced C project that requires some knowledge of 3D graphics, so you might want to learn some fundamentals of ray tracing before starting this project. You might also want to learn about the PPM image format to output your rendered scenes.
# Submissions 
 git push your solution in this repo and hit /submit in Discord
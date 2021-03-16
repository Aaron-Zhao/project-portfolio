Mars Glider is an application of [Particle Filter](https://en.wikipedia.org/wiki/Particle_filter). The project consists of two parts, in first part we need to estimate the next location of the glider using Particle Filter given its atmospheric height and the radar distance to the ground. In second part, once we can track where the glider is running towards we then navigate the glider to return to the center of the dropzone as close as possible.

The black arrows are the particles, the purple circle is the estimation of the glider location, and the red arrow is where the glider really is. The estimation will get more accurate as the time passes since "inferior" particles will get eliminated in the process.

This is a project in CS 7638 Robotics: AI Techniques class.

![Mars Glider Part 1](/MarsGlider/mars_glider_part1.gif "Mars Glider Part 1")]

![Mars Glider Part 2](/MarsGlider/mars_glider_part2.gif "Mars Glider Part 2")]

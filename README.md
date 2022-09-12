# CS450-Computer-Graphics-Final

This code uses Mike Bailey's OpenGL sample program as a base.

## How to use

Once the files are downloaded, go into the [Final](Final) folder. Right-click on [Sample.sln](Final/Sample.sln) and open it in Visual Studio.

To run, you can either run it with or without debugging. 

### Controls

To rotate the camera, left-click on the window and drag.

To open the menu, right-click on the window.

To zoom in and out, scroll up and down on the scroll wheel respectively.

### Settings

Initially, you'll see a white axis and a white dot flying along overhead the Z axis.

To open the settings, right-click on the window.

#### Particle Simulations

To select the particle simulation you'd like, right-click on the window to open the menu. Under "Particle Selection" there are four options.

##### Off

Turns off all the particles.

##### Tornado

Spawns a large number of particles and teapots along with a floor. Over time, they'll start spiralling upwards until they eventually despawn and are replaced by particles at the base of the tornado.

##### Gravity Well

Spawns particles around the axis that start moving towards the center. The closer to the center, the faster they move.

##### Rain

Spawns particles above a floor. As they reach the floor, they'll change the square they hit to red and respawn at the top. There's a few detection issues since there's too many particles for it to handle at times.

#### Lighting

By default, lighting is off.

##### Off

The default option. All of the objects will appear white, excluding the red panels on the floor.

##### Ambient

Turns on ambient lighting. 

##### Specular

Light will be emitted from the white dot passing over the Z axis and the objects will be lit accordingly.

#### Other Settings

The other settings are ripped straight from the original program and function as you'd expect, though the color setting doesn't work.

Here's a video of the intended funciton.

https://media.oregonstate.edu/media/t/1_hb7940iv

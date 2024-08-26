The Intel RealSense libraries provide incredible flexibility and depth for experimenting with localization.

I modified some of these libraries to map custom images and fields that can help localize within complex environments.
I introduced scripts to incorporate YCrCb intensity pipelines that are flexible and adaptable, and do not 
heavily depend on lighting. 

I anticipate some of these libraries to become gravely important in robotics, especially more so for distance monitoring
in vehicles, or in autonomous systems in general.

As for future additions, I hope to pair this with dead-wheel tracking so that you add a check for the T265 mapping, 
which is known to be spotty from time to time. I hope to introduce this to FTC Robotics; feel free to use if this helps
you with your localization pipelines!

- Aryan Avlash

Documentation Author: Niko Procopi

Fixing 2D elements after flipping Y-axis

In previous tutorials, sprite2D.vert shader
was hard-coded to adjust for Vulkan's inverted
Y-axis. We removed that, so the code is now
identical to what you would see in an OpenGL or
DirectX implementation. Additionally, in Scene, 
we changed the Y coordinate of each 2D element from
around +0.8 to around -0.8, which is what the coordiinate
system would be in OpenGL or DirectX
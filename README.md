# render_meshes
Python code to read a ply or obj mesh file and estimate its visibility from a view, using z-buffering (depth buffer).
Camera paramters need to be provided (intrinsics and extrinsics, assuming pinhole model ). Modifying the code to use some other projection model such as fisheye is easy enough, as the z-buffering logic remains unchanged.

This is a very common task that comes up in 3D reconstruction / SLAM / Augmented Reality / Graphics tasks

# CENG469 - Computer Graphics II
  Homework 1, Catmull-Clark Subdivision

I began by inspecting the outputs of the algorithm for some sample meshes in Blender. This helped me get a feel for the algorithm. Then, I looked online for simple descriptions and explanations. I believed that I had to understand the algorithm well before implementing it, as doing so would probably save a lot of debugging time. For graphics algorithms, making the first implementation as correct as possible is important because they are harder to debug than conventional algorithms.

My platform was Windows 10 and Visual Studio 2022. I began coding by copying a 'library' that I wrote for projects that involve OpenGL. The library saves some time that I would have wasted writing shader uniform passing, buffer binding/unbinding etc. From this point on, I will split the blog into sections for each component of the implementation.

## OBJ Loader

The sample OBJ loader did not support all the features I wanted and was not written in my style. So I decided to replace it. This was trivial and involved learning about the simple OBJ format from some page online, then writing a parser. 

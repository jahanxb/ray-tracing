Ray tracing Algorithm. 

1) Performed Ray trace and correctly draw a sphere object and another object in the scene
2) Correctly performed Phong shading by supporting ambient, diffuse, and specular
lighting in your renderer.
3) Interpolated the vertices of the polygons to determine the normal
at each pixel to be used for shading.
4) Displayed shadows by not illuminating surfaces by lights from which they are
occluded and illuminated direct light on the surface.
5) Correctly perform recursive reflection (up to 3 iterations) by creating 2 shiny
surface and one non-shiny sphere and bounce rays off of it.

How to Run the file 
**On Windows**
1) Simply install CodeBlocks or DevCPP or Visual Studio. 
2) Extract the files in the same folder. 
3) Open main.cpp file or (ques_h4.cpp) in the IDE. (Both files have the same code , for the sake of simplicity we included main.cpp as it's the conventional way) 
4) Compile and run the file. 
5) You will see a console window , Showing "rendering Completed". 
6) After that go to the same folder, You will see an image with (.png) format Named as (scene_anti-aliased.png) that's the output result image. 

**On Linux** 
1) Extract the files in a folder 
2) Open Terminal and goto the current directory. 
3) Run the following command in the terminal 
     terminal$~  gcc main.cpp -o main
     |OR|
      terminal$~  gcc ques_h4.cpp -o ques_h4
5) You will see a message on terminal , Showing "rendering Completed" . 
6) After that go to the same folder, You will see an image with (.png) format Named as (scene_anti-aliased.png) that's the output result image. 

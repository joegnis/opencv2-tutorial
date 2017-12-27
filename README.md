# OpenCV 2 Tutorial

Source codes as I was going through the OpenCV 2 official tutorials which start from: 
[How to build applications with OpenCV inside the 
Microsoft Visual Studio](https://docs.opencv.org/2.4.12/doc/tutorials/introduction/windows_visual_studio_Opencv/windows_visual_studio_Opencv.html)

## Environment

- OpenCV 2.4.12
- Visual Studio 2013

## Note

### Image Watch: viewing in-memory images in the Visual Studio debugger

To make debugging work, I have to use static libs because they come with pdb files. 
Then to make static libs work, besides changing the path in _Linker_, in property sheets, go to "_C/C++_ > _Code Generation_ > _Runtime Library_"
and change it to "/MTd" for _Debug_ or "/MT" for _Release_. 
Add additional libs to _Linker_ dependencies as well, such as "libjpegd.lib".

## Log

- 12/26/2017. Finished [How to build applications with OpenCV inside the 
Microsoft Visual Studio](https://docs.opencv.org/2.4.12/doc/tutorials/introduction/windows_visual_studio_Opencv/windows_visual_studio_Opencv.html).
Set up Visual Studio.
- 12/27/2017. Finished [Image Watch: viewing in-memory images in the 
Visual Studio debugger](https://docs.opencv.org/2.4.12/doc/tutorials/introduction/windows_visual_studio_image_watch/windows_visual_studio_image_watch.html).
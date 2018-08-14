## Object Detection
This is an implementation of the Faster R-CNN in C++ on Windows  
  
The project includes：
The camera captureing the image  
Detecting persons in the pictures
Saving the pictures and sending them to the server and the smart phones  

### Requirements
- caffe
- OpenCV

### Getting Started
Create a solution with Visual Studio and include the source code  
Download the Getui APP and use the value in the app to replace the "appId", "appKey", "masterSecret" and "cid" in GRTUI.h
Build the solution
Run ObjectDetect.cpp

### Results
The speed of the program achieves 13fps on GeForce GTX 1060

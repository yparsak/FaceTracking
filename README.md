# FaceTracking
Face Tracking using OpenCV

Download OpenCV, and extract it to a directory.

Create a user library, and include opencv-330.jar which is under opencv/build/java/opencv-330.jar

Add user library to the project using Properties/Java Build Path/Add library
Once the user library is added, modify "Native Library Location"

The Native library location should point to:
opencv directory path/build/java/x64 (if using 64 bit OS)
opencv directory path/build/java/x86 (if using 32 bit OS)

If you export the jar file, you should have opencv_java330.dll in the same directory. Use

x64/opencv_java330.dll for 64 bit OS
x86/opencv_java330.dll for 32 bit OS

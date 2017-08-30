# TensorFlow YOLO object detection on Android
<div align="center">
  <img src="http://i.imgur.com/hskdvoi.png"><br><br>
</div>

[Source project](https://github.com/miyosuda/TensorFlowAndroidDemo)

**android-yolo** is the first implementation of YOLO for TensorFlow on an Android device. It is compatible with Android Studio and usable out of the box. It can detect the 20 classes of objects in the Pascal VOC dataset: aeroplane, bicycle, bird, boat, bottle, bus, car, cat, chair, cow, dining table, dog, horse, motorbike, person, potted plant, sheep, sofa, train and tv/monitor. The network only outputs one predicted bounding box at a time for now. The code can and will be extended in the future to output several predictions.

To use this demo first clone the repository. Download the TensorFlow YOLO [model](https://drive.google.com/file/d/0B2fFW2t9-qW3MVJlQ29LRzlLT2c/view?usp=sharing) and put it in android-yolo/app/src/main/assets. Then open the project on Android Studio. Once the project is open you can run the project on your Android device using the Run 'app' command and selecting your device.

**NEW**: The **standalone APK** has been released and you can find it [here](https://drive.google.com/open?id=0B2fFW2t9-qW3LWFDNXVHUE9rV3M). Just open your browser on your Android device and download the APK file. When the file has been downloaded it should begin installing on your device after you grant the required permissions.

GPUs are not currently supported by TensorFlow on Android. If you have a decent Android device you will have around two frames per second of processed images. 

Here is a [video](http://youtu.be/EhMrf4G5Wf0) showing a small demo of the app.

Nataniel Ruiz  
School of Interactive Computing  
Georgia Institute of Technology  

Credits:

App launch icon made by [Freepik](http://www.freepik.com) from [Flaticon](http://www.flaticon.com) is licensed by [Creative Commons BY 3.0](http://creativecommons.org/licenses/by/3.0/).



Name: Evaluate Android Yolo app 
 
Date Started: 18/07/17
 
Using:
Android Studio
Java
Android Yolo App
 
Why?
To evaluate the object detection of the classes specified in it and check the confidence by taking pictures of the objects from different angles
 
How?
Fork the Android Yolo App repository from github.
Clone Android Yolo App repository.
Run the source code.
Examine the source code - try to change the apk version in the build files if any error.
Examine time to detect the objects.
Focus on object.
Try to recognize the faces in images.
Testing the app by focusing on two objects placing close to each other.
  
Outcome
Source code of Android Yolo is successfully executed. It is able to detect the objects and the probability score is displayed on top of the screen.
 
Date Completed:  20/07/2017
 
What?
Android Yolo
Android Yolo can detect the different objects.
Time required to detect the object is good.
Detect only basic objects (Limited objects)
Probability of the object detected is given there.
Flat objects like notebook, book, screens are difficult to detect.
This app only detects single object in frame.
It is difficult to identify the object if it is behind another object.




Notes:
Object must be in green frame of camera while using Android Yolo.

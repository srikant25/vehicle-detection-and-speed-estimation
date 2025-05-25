🚗  **Vehicle Detection and Speed Estimation**

This project detects moving vehicles in a video and estimates their speed using computer vision techniques. It leverages Haar cascade classifiers for detection and Dlib correlation trackers for tracking. Speed is estimated based on the time taken to travel a known distance in the video frame.

📌 **Features**

Real-time vehicle detection using Haar cascades

Object tracking with unique IDs using Dlib

Speed estimation based on pixel-to-meter conversion

Lightweight, beginner-friendly Python implementation

📽️ **Algorithm Overview**

Load the Video: Read the input video using OpenCV.

Vehicle Detection: Apply a pre-trained Haar cascade classifier to detect vehicles.

Object Tracking: Use Dlib’s correlation tracker to assign and maintain vehicle IDs across frames.

Time Tracking: Start a timer as soon as a vehicle enters the detection zone.

Distance Estimation: Calculate the real-world distance traveled using pixel-to-meter scaling.

Stop Timer: Stop the timer when the vehicle reaches the end of the detection zone.

Speed Estimation: Estimate speed using:

Speed (m/s) = Distance (m)/ Time (s)

​
 





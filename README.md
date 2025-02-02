# Autonomous_Robotics_Ex2 - ArUco Marker Detection in Video
## Contributors
* Raz Saad
* Maor Or
* Shlomit Ashkenazi
# PART A:
## How to run
* Clone the repo to a local machine
* Open Part_A folder
* Open the Aruco_detector_PART_A.ipynb file in Jupyter and run each block one by one
* output files will update in the repo's directory
## Description

This project focuses on detecting ArUco markers in a video stream using computer vision techniques. Each frame of the video is processed in real-time to extract various parameters of detected ArUco markers such as ID, 2D corner coordinates in frame space, and 3D information including distance to the camera, yaw, pitch, and roll angles.

The implementation ensures that each frame processing does not exceed 30 ms, making it suitable for real-time applications. Detected ArUco markers are annotated in a video output and logged into a CSV file for further analysis.
## Output frames example from video
![image](https://github.com/Raz-Saad/Autonomous_Robotics_Ex2/assets/118377261/99902517-29f7-4a05-ab72-fb35dbe475b6)
![image](https://github.com/Raz-Saad/Autonomous_Robotics_Ex2/assets/118377261/abcab524-687d-4c8c-b00c-e6d7f54285e6)
<br/><b> Average processing time for a single frame: 9ms </b>

# PART B:
## How to run
* Clone the repo to a local machine
* Open Part_B folder
* Open the Aruco_detector_PART_B.ipynb file in Jupyter and run each block one by one
  
## Requirements
* Connect a webcam / your phone's camera
  
## Description
Detecting ArUco marker in a live stream video using computer vision techniques and instructing the user with 8 commands (left, right, forward, backward, up, down, turn-left , turn-right) in order to align the live feed with the desired pre-recored ArUco marker pose. 

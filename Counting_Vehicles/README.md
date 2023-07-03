# Counting vehicles using OpenCV
A project using OpenCV with Python.
## description
This project aims to detect and track vehicles on the camera data and count the vehicles.
By web camera or using video file, the project displays the traffic videos on the screen. Then, the project will recognize all the moving vehicles and count the vehicles as they pass through the certain line.
## Technical Specifications
This project has the following technical specifications.
* Removing background using subtractor
  * It bases on the difference between previous and current frame of the video
*	Detecting vehicle regions using contours
  * The region is calculated by the bounding rectangle of the detected vehicle contour.
* Counting the vehicles using information about each tracked vehicle
  * Check if the detected vehicle is new or already existing 
  * Count the vehicles that are pass through the certain line.


# Face Recognition Attendance System

This project uses face recognition to mark attendance in real-time. The system captures video from the camera and identifies individuals in the video stream by matching their faces with pre-stored images.

## How it works

1. The system captures video from the camera.
2. Each frame of the video is analyzed to identify faces.
3. The faces are compared against a pre-stored set of images to identify
   individuals.
4. If a face matches a pre-stored image, the system marks that individual as "present" and records their name and the current time in a CSV file.
5. The system displays the video stream with names of identified individuals marked as "present".

## Requirements
 * Python 3.6 or later
 * face_recognition library
 * opencv-python library
 * numpy library

# Usage

1. Clone this repository
2. Install the required libraries: 'pip install face_recognition opencv-python numpy'
3. Create a 'photos' directory and add the images of individuals you want to recognize.
4. Run 'python attendance.py' to start the system.
5. The program will automatically detect faces in the camera's feed, recognize them, and mark their attendance by writing their name and the current time to a CSV file.
6. Press 'q' to exit the system.

## Credits
This project was created by Rahul Mk and was inspired by the face_recognition library created by Adam Geitgey. Special thanks to Adam for making this project possible.

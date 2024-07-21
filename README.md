# Smart-Attendance-System
This is a system made using python which checks and matches the faces by facial recognition, OpenCV, cmake. 
Modules and Libraries Used: 
face_recognition: This library is used for facial recognition. It provides functions to load images, find faces, and encode face features.
cv2 (OpenCV): OpenCV is used for capturing video from the webcam, resizing frames, and displaying the video feed with annotations.
numpy: This library is used for numerical operations, particularly for handling arrays and mathematical computations.
csv: This module is used for writing the attendance data to a CSV file.
datetime: This module is used to handle date and time operations, such as getting the current date and time.
Lists and Strings are used as Data Structures.
Lists:
known_face_encodings: A list to store the encoded face data of known individuals.
known_face_names: A list to store the names corresponding to the known face encodings.
students: A list to store the names of students who are expected to attend.
Strings: Used for storing names and file paths.
Face Recognition Algorithm is used for Load and encode the known faces, Capture frames from the webcam, Resize and convert the frame to RGB format, 
Detect face locations and encodings in the current frame, Compare detected face encodings with known face encodings to identify matches, 
Calculate the face distance to find the best match.
Features: Loading Known Faces, Capturing Video, Face Recognition, Attendance Logging, Real-Time Updates.

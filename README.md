# Number-plate-detection-
This GitHub repository contains a real-time license plate detection project using OpenCV in Python. The application uses the Haar Cascade classifier to identify license plates from live video feeds or pre-recorded videos and highlights them with bounding boxes. Detected license plates can also be saved as separate image files.
Features:
Real-time license plate detection using OpenCV and Haar Cascade classifier.
Supports live video feed from the default camera.
Detects and highlights license plates with bounding boxes.
Saves detected license plates as separate image files.
Easy-to-use and customizable code.
How it Works:
The project captures video frames from the default camera in real time.
Each frame is converted to grayscale for faster processing.
The Haar Cascade classifier for Russian license plates is used to detect regions that resemble license plates.
Detected regions with an area greater than a specified threshold are considered license plates and are highlighted with bounding boxes.
The user can press the 'q' key to save the last detected license plate as an image.
The saved images are stored in the "Resources/Scanned/" directory.

Object Detection Application
This Python-based object detection application leverages the YOLO (You Only Look Once) model for real-time object detection within images. It provides a user-friendly graphical interface, built using tkinter and enhanced with modern styling through the ttkbootstrap library.

Key Features:
Image Loading: Users can load images from their local file system.
Object Detection: The YOLO model detects objects within the loaded image and displays both the modified image with bounding boxes and a list of detected objects.
Dynamic Resizing: The GUI elements, including the displayed image and detected object list, dynamically resize with the application window, maintaining usability and aesthetics.
Flow and Functionality:
GUI Initialization:

The application window is created with tkinter, and ttkbootstrap is used to apply a modern theme.
The main layout consists of a main_frame divided into two sub-frames: left_frame for displaying images and right_frame for control buttons and detected objects list.
Image Loading:

Users can click the "Load Image" button to open a file dialog and select an image file (.jpg, .jpeg, .png).
The selected image is loaded, resized (while maintaining its aspect ratio), and displayed in the left_frame.
Object Detection:

Upon clicking the "Detect Objects" button, the YOLO model processes the loaded image to identify objects.
The detected objects are visually marked with bounding boxes on the image, which is then updated in the left_frame.
A summary of detected objects, including their count and types, is displayed in a list format in the right_frame.
Dynamic Resizing:

The GUI components are configured to resize dynamically with the application window, ensuring that the image and object list expand and contract as the user resizes the window.
Core Components:
ObjectDetectionApp Class:

Initializes the main window and sets up the layout.
Contains methods for loading images (load_image_dialog), displaying images (load_image), performing object detection (detect), and displaying detection results (display_detected_image and process_detected_objects).
YOLO Model:

Utilizes the ultralytics library to load the pre-trained YOLO model (yolov8x.pt).
Processes images to detect objects and outputs results, which include bounding boxes and class labels.
Usage:
Run the application script.
Load an image by clicking the "Load Image" button and selecting a file.
Click the "Detect Objects" button to perform object detection.
View the processed image with bounding boxes and the list of detected objects.
This application provides an intuitive interface for users to interact with object detection capabilities, making it suitable for both demonstration purposes and practical use cases in various projects.


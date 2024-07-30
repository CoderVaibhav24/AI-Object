# AI-powered Object Identification App

This Python-based object detection application leverages the YOLO (You Only Look Once) model for real-time object detection within images. It provides a user-friendly graphical interface, built using `tkinter` and enhanced with modern styling through the `ttkbootstrap` library. Users can load images, detect objects, and view the results dynamically.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
pip install pillow
pip install ultralytics
pip install ttkbootstrap
```


### Installing

A step-by-step series of examples that tell you how to get a development environment running

Install the necessary libraries

```
pip install pillow
pip install ultralytics
pip install ttkbootstrap
```


Download the YOLO model

```
Ensure you have the "yolov8x.pt" model file in your working directory
```

Run the application script

```
python object_detection_app.py
```


End with an example of getting some data out of the system or using it for a little demo

1. Load an image by clicking the "Load Image" button and selecting a file.
2. Click the "Detect Objects" button to perform object detection.
3. View the processed image with bounding boxes and the list of detected objects.

## Running the tests

Explain how to run the automated tests for this system

### Break down into end-to-end tests

Explain what these tests test and why

```
Test image loading
Test object detection accuracy
```


### And coding style tests

Explain what these tests test and why


```
Ensure PEP 8 compliance
Verify code quality with pylint
```


## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [ttkbootstrap](https://ttkbootstrap.readthedocs.io/en/latest/) - Used for the modern GUI
* [Pillow](https://python-pillow.org/) - Used for image processing
* [Ultralytics YOLO](https://github.com/ultralytics/yolov5) - YOLO model for object detection
* [Tkinter](https://docs.python.org/3/library/tkinter.html) - Standard Python interface to the Tk GUI toolkit

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Vaibhav** - *Object Detection* - [Your GitHub Profile](https://github.com/CoderVaibhav24)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc




















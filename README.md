# FlaskCBIR

A Content Based Image Retrieval System made with Flask and OpenCV.

![alt text](https://i.imgur.com/OgjxXez.jpg)

Technologies used : Flask and OpenCV.

## Basic overview

The application makes use of Image Descriptors to create a mathematical description of an image to be saved as a trained model.
Then, these same descriptors are used to find similar images when a new image is given as input.

The chi squared distance is calculated to find similar images.

Made with the help of Adrian Rosebrock from [PyImageSearch](https://www.pyimagesearch.com)

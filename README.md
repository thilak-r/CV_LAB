# Lab Program 1: Image Convolution and Edge Detection Using Sobel Operation

This lab program focuses on various image processing techniques, particularly convolution and edge detection. It utilizes the Sobel operation to identify edges in images, providing insight into the spatial frequency of pixel intensities. The following sections detail the steps involved in applying different edge detection methods and transformations.

![Notebook Sample Screenshot](https://raw.githubusercontent.com/thilak-r/CV_LAB/main/pik.png)


## Sobel Edge Detection (Combined)

In this section, the Sobel operator is used to detect edges in an image by calculating the gradient of the image intensity. The combined Sobel result highlights edges by merging both the horizontal and vertical gradients, effectively outlining features within the image. This method is essential in various applications, including image analysis and computer vision.

## Gaussian Blurred Original Image

Gaussian blurring is applied to the original image to reduce noise and detail, smoothing out the pixel values. This pre-processing step is crucial before applying edge detection techniques, as it helps to enhance the quality of the edge-detected output. The Gaussian kernel is used to perform the blurring, creating a softer version of the original image.

## Gabor Filters

Gabor filters are used for texture analysis and feature extraction in images. These filters combine Gaussian envelopes with sinusoidal functions, allowing them to respond to specific frequencies and orientations. In this section, we explore how Gabor filters can enhance specific textures in images, aiding in edge detection and pattern recognition tasks.

## Laplacian Edge Detection

The Laplacian operator detects edges by calculating the second derivative of the image intensity function. This method emphasizes regions of rapid intensity change, making it effective for identifying edges. In this section, we demonstrate how Laplacian edge detection can be applied to highlight structural details within an image, complementing the Sobel method.

## Magnitude Spectrum Transformation

Magnitude spectrum transformation involves analyzing the frequency components of an image using Fourier Transform. This section illustrates how to visualize the magnitude spectrum, allowing us to see the distribution of frequencies within the image. Understanding the magnitude spectrum is crucial for various image processing tasks, including filtering and image reconstruction.

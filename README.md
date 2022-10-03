# TIC4005 GPU-Kernel Project

**Completed by:**

Koh Shao Wei A0211507U

## Project Overview
For this project, students are required to develop and evaluate a small set of original image processing functions using GPU.js that can run on a GPU or CPU platform. Students will then apply this processing functions to a video stream from their camera.

## Implementation
For this project implementation, different image processing functions utilitzes the GPU kernels created using GPU.js to define textures for each of the functionality to apply onto the video stream so they can run concurrently based on what user has selected via a pipeline.

## Limitation
Since image processing requires alot of processing power, the image processing functionalities are only available to the user if they have checked the "GPU enabled" option. 

## How to use
Users are able to try it out by opening the HTML page "htmlproj.html" in this repo or visiting the URL: https://ksw95.github.io/kernelproject/htmlproj.html where it is currently live.

Once user has checked the "GPU Enabled" checkbox, users will be able apply and remove different image processing functions by checking or unchecking the tick boxes and adjusting the slider bar displayed on the HTML page as seen in the picture below.

![image](https://user-images.githubusercontent.com/73837999/193533113-e28a6e2e-9bff-4e58-8a8d-e1b39894302a.png)

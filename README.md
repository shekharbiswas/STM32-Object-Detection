# STM32 Object Detection with TensorFlow Lite

This project demonstrates how to deploy a Convolutional Neural Network (CNN) model to detect the number of objects in an image captured by an STM32 microcontroller using TensorFlow Lite. 
The model will be trained to identify and count objects in an image and will be optimized for the resource constraints of the STM32 environment.

Our aim to deploy a CNN model on an STM32 microcontroller to detect and count objects from the camera feed. 
The model will be trained using TensorFlow, converted to TensorFlow Lite format.
Then, we will deploy it to the STM32 microcontroller. 

Initially we are using a simulator and then will be deployed to physical STM32 hardware.

**STM32H747I-DISCO Applications**:
[![Watch the video](https://img.youtube.com/vi/bSeQp56Qz1k/maxresdefault.jpg)](https://www.youtube.com/watch?v=66LIrdb07pY&list=PLnMKNibPkDnF6-h0x06AATx1kAuBiPRTE)





## Requirements
- STM32CubeIDE
- Python 3.x
- TensorFlow and TensorFlow Lite
- OpenCV (for image processing)
- QEMU-based STM32 simulator (e.g., Renode or STM32CubeIDE QEMU)

## Object Detection Task

For object detection and counting with TensorFlow and TensorFlow Lite, we will use a pre-trained model like MobileNet SSD (Single Shot MultiBox Detector).
This is quite efficient for object detection tasks on mobile and embedded devices. 

A first step is to use TensorFlow's Object Detection API to perform object detection-
(and count the number of detected objects, such as balls, flowers etc.)


Face recognition:

[![Watch the video](https://img.youtube.com/vi/bSeQp56Qz1k/maxresdefau66LIrdb07pYlt.jpg)](https://www.youtube.com/watch?v=bSeQp56Qz1k&list=PLnMKNibPkDnF6-h0x06AATx1kAuBiPRTE)


# STM32 Object Detection with TensorFlow Lite (Simulator)

This project demonstrates how to deploy a Convolutional Neural Network (CNN) model to detect the number of objects in an image captured by an STM32 microcontroller using TensorFlow Lite. 
The model will be trained to identify and count objects in an image and will be optimized for the resource constraints of the STM32 environment.

This project aims to deploy a CNN model on an STM32 microcontroller to detect and count objects from the camera feed. The model is trained using TensorFlow, converted to TensorFlow Lite format, and then deployed to the STM32 microcontroller. Since we are using a simulator, no physical STM32 hardware is required.

## Requirements
- STM32CubeIDE
- Python 3.x
- TensorFlow and TensorFlow Lite
- OpenCV (for image processing)
- QEMU-based STM32 simulator (e.g., Renode or STM32CubeIDE QEMU)


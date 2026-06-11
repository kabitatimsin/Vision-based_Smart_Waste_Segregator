# Vision-Based Smart Waste Segregator

## Project Overview

The Vision-Based Smart Waste Segregator is an automated waste management system that uses Raspberry Pi and computer vision to identify and classify waste materials into five categories as Glass, Metal, Paper, Plastic and Organic. Once the waste type is detected, the system automatically directs the waste into the appropriate compartment, improving waste segregation efficiency and promoting recycling.

## Objectives

* Automate the waste segregation process.
* Reduce human effort in waste sorting.
* Improve waste management.
* Demonstrate the use of computer vision in real-world applications.

## Features

* Real-time image capture using a camera module.
* Waste classification using computer vision.
* Automatic bin selection mechanism.
* Raspberry Pi-based processing.
* Environment-friendly smart solution.

## Hardware Components

* Raspberry Pi 4
* Raspberry Pi Camera Module
* Servo Motor
* Stepper Motor
* Power Supply
* Waste Collection Bins
* Jumper Wires
* Tof Sensor

## Software Requirements

* Raspberry Pi OS
* Python 3
* OpenCV
* NumPy

## Project Workflow

1. The camera captures an image of the waste item.
2. The Raspberry Pi processes the image.
3. The waste type is identified using computer vision techniques.
4. The servo motor rotates to the corresponding waste bin.
5. The waste is deposited into the appropriate compartment.

## Installation

1. Clone the repository.
2. Install the required libraries.

```bash
pip install opencv-python numpy
```

3. Connect the camera and servo motor to the Raspberry Pi.
4. Run the main program.

```bash
python main.py
```

## Future Enhancements

* Deep Learning-based classification.
* IoT monitoring dashboard.
* Mobile application integration.
* Cloud-based waste analytics.

## Author

Kabita Timsina

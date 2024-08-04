# Real-Time Face Recognition System

## Overview

This project implements a real-time face recognition system using OpenCV and Python. The system is designed to recognize faces in real-time using a webcam, making it suitable for applications such as access control and surveillance.

## Features

- Real-time face detection and recognition.
- High accuracy and speed using OpenCV's Haar Cascades for face detection and Eigenfaces algorithm for recognition.
- Suitable for security, surveillance, and access control applications.

## Installation

To run this project, you'll need to install the required Python libraries:

1. Clone the repository:
    ```bash
    git clone https://github.com/AkashR-16/Face-Recognition-System.git
    cd your-repo-name
    ```

## Usage

To run the face recognition system:

1. Ensure your webcam is connected.
2. Run the main script:
    ```bash
    python face_recognition.py
    ```

The system will start detecting and recognizing faces in real-time.

## Methodology

The system uses the following methodology:

1. **Face Detection:** OpenCV's Haar Cascades are used to detect faces in each frame of the video stream.
2. **Face Recognition:** The Eigenfaces algorithm is employed to recognize detected faces based on pre-encoded data.

## Results

The system has been tested for accuracy, speed, and robustness. It performs well under various conditions, making it a reliable solution for real-time face recognition.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


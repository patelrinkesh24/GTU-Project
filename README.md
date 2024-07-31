# Real-Time Object Detection Module

This repository contains a real-time object detection module built using TensorFlow, YOLOv3, NumPy, Matplotlib, and Pyttsx3. The module is designed to identify and label objects within a live video stream or pre-recorded video in real-time. This project demonstrates the integration of computer vision with real-time processing capabilities, enhancing applications such as surveillance, autonomous systems, and interactive AI-driven environments.

## Features

- **Real-Time Detection**: Leverages YOLOv3 for high-speed, high-accuracy object detection.
- **Audio Feedback**: Uses Pyttsx3 to provide verbal feedback on detected objects, enhancing accessibility.
- **Customizable**: Easily modifiable to detect specific object classes or to work with custom-trained models.
- **Visualization**: Displays bounding boxes and labels on the detected objects in real-time using Matplotlib.
- **Scalable**: Designed to be extended or integrated with larger systems requiring object detection capabilities.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/RealTime-Object-Detection.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download pre-trained YOLOv3 weights and configuration files:
    ```bash
    # Commands or instructions to download the required files
    ```

4. Run the module:
    ```bash
    python main.py
    ```

## Dependencies

- Python 3.x
- TensorFlow
- YOLOv3
- NumPy
- Matplotlib
- Pyttsx3
- OpenCV

## Usage

- **Live Video Stream**: Connect a camera and start the script to detect objects in real-time.
- **Pre-recorded Video**: Provide the path to a video file, and the module will process it, detecting and labeling objects frame by frame.
- **Custom Objects**: Modify the configuration to include your custom-trained YOLOv3 model.

## Example Output



## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/yourusername/RealTime-Object-Detection/issues) if you want to contribute.



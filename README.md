# Driver Drowsiness Detection System

## Overview
This project presents a **Driver Drowsiness Detection System** aimed at enhancing road safety through real-time monitoring. The system utilizes **OpenCV** for face and eye detection, combined with a **Convolutional Neural Network (CNN)** to identify signs of drowsiness and trigger an alarm when necessary.

## Features
- **Face & Eye Detection**: Utilizes **Haar Cascade Classifier** for object detection.
- **Deep Learning Model**: Implements a **CNN** for classifying eye states (open/closed).
- **Real-time Processing**: Captures live video feed to analyze driver fatigue.
- **Alarm System**: Alerts the driver if drowsiness is detected.
- **Simulation & Testing**: Evaluates accuracy through real-world scenarios.

## Methodology
1. **Object Detection**: Identifies the driver's face using OpenCV.
2. **Emotion Recognition**: Analyzes facial features to detect signs of fatigue.
3. **Drowsiness Detection**: Uses a CNN model to classify eye states and track drowsiness levels.
4. **Trigger Alert**: If the driver's eyes remain closed for a specified duration, an alarm is activated.

## Technologies Used
- **OpenCV** for real-time face and eye detection
- **Convolutional Neural Networks (CNNs)** for eye state classification
- **YOLO V5** for object detection
- **Mobilenet** for emotion recognition
- **Python** and **TensorFlow/Keras** for deep learning model development

## Dataset
The dataset used includes images categorized into **open/closed eyes** and **yawning/no yawning** for effective model training. Data augmentation techniques were applied to improve accuracy.

## Performance & Results
- Achieved **97.32% accuracy** in real-time analysis.
- Successfully integrated **YOLO V5** for object detection.
- Implemented **Mobilenet-based emotion recognition** for enhanced detection.
- Developed a robust **alarm trigger mechanism** based on drowsiness scores.

## Installation & Usage
1. Clone my repository;
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the system:
   ```bash
   python drowsiness_detection.py
   ```

## Future Enhancements
- **Integration with IoT**: Connect with vehicle safety systems.
- **Edge Computing**: Deploy on low-power devices for real-time inference.
- **Advanced AI Models**: Implement LSTMs or transformers for better prediction.



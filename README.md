# Emotion-Recognition-Software

This emotion recognition software is designed to assist individuals with autism spectrum disorder (ASD) in understanding emotions and social cues. By analyzing facial expressions in real-time, the software helps users interpret the emotions of others, enhancing their social interactions and communication skills.

## Features

- Real-time emotion recognition from live video streams.
- Support for a wide range of emotions including happiness, sadness, surprise, and more.
- User-friendly interface for easy interaction.
- Customizable feedback options to suit individual needs.

## Screenshots:
![happy](https://github.com/ravishshardha/Emotion-Recognition-Software/assets/90361755/4c416b57-108b-455a-8c13-cb21359ef06a)
![sad](https://github.com/ravishshardha/Emotion-Recognition-Software/assets/90361755/31cde751-e48d-4ce5-8712-d09a251f56f5)
![suprised](https://github.com/ravishshardha/Emotion-Recognition-Software/assets/90361755/b9776249-e2fb-43b9-a957-e0407278133b)


## Implementation Steps:

- **Data Collection**: We gathered hundreds of images representing a range of emotions, including happiness, sadness, and surprise, from online databases and AI-generated sources.
- **Feature Extraction**: Using OpenCV and custom scripts, we extracted facial landmarks and other relevant features from the images, which serve as inputs for our machine-learning models.
- **Model Training**: We utilized the Scikit-Learn library to train our facial expression recognition model, focusing on optimizing accuracy, precision, recall, and F1 score.
- **Integration and Real-Time Processing**: The trained model was integrated with real-time video processing capabilities using the OpenCV library. This setup allows the software to analyze video streams from a computer’s webcam, identify facial expressions frame by frame, and provide immediate feedback to the user.

## Getting Started
To get started with the emotion recognition software, follow these steps:

### Prerequisites
- Python 3.x installed on your system.
- Ensure that the following libraries are installed:
  - OpenCV
  - Scikit-Learn

```bash
cd emotion-recognition

pip install opencv-python
pip install scikit-learn

python emotion_recognition_app.py
```

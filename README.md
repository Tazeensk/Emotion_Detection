# Emotion Detection Project with GUI

This project aims to detect emotions from live webcam feed or video files. It uses a convolutional neural network (CNN) model trained on facial emotion images. The GUI interface allows for real-time detection of emotions on faces.
Download Dataset from:: https://www.kaggle.com/datasets/msambare/fer2013

## Features

- Real-time emotion detection from webcam or video files.
- Utilizes OpenCV for face detection and visualization.
- Trained CNN model for recognizing facial emotions.
- Provides a dictionary mapping for emotions detected.
- Easy-to-use graphical user interface (GUI).

## Setup and Usage

1. **Clone Repository:**

git clone <repository_url>

2. **Install Dependencies:**
pip install -r requirements.txt


3. **Run the Application:**
python emotion_detection.py


This will start the application with webcam feed or video input (modify `cap = cv2.VideoCapture("path_to_video.mp4")` for video file).

## Requirements

- Python 3.x
- OpenCV
- TensorFlow
- NumPy

## File Structure

- `emotion_detection.py`: Main script for running the emotion detection application.
- `data/`: Directory containing training and testing data.
- `haarcascades/`: Directory containing Haar cascade XML files for face detection.
- `live_videos/`: Directory containing sample video files for testing.
- `Weights/`: Directory containing model weights and architecture in JSON format.

## Credits

This project is developed by [Tazeen Shaikh].

## Outputs:


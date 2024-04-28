# Real-time Facial Emotion Recognition

This project implements real-time facial emotion recognition using OpenCV for face detection and Keras for emotion prediction. It streams video from a webcam and annotates faces with predicted emotions in real-time.

## Dataset
The facial expression recognition model used in this project was trained on the "Face Expression Recognition Dataset" available on Kaggle. You can download the dataset from the following link:
[Face Expression Recognition Dataset](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset)

## Requirements
- Python 3.x
- OpenCV (cv2)
- Keras
- NumPy

To install the required packages, run: pip install -r requirements.txt

## Usage
1. Download the pre-trained model files (`emotiondetector.json` and `emotiondetector.h5`) from the repository.
2. Clone this repository.
3. Install the required packages using the provided requirements file.
4. Run the script using Python: python emotion_recognition.py
5. 5. The webcam feed will open, and faces will be annotated with predicted emotions in real-time.

## Files
- `emotion_recognition.py`: The main script for real-time facial emotion recognition.
- `emotiondetector.json`: The JSON file containing the architecture of the pre-trained Keras model.
- `emotiondetector.h5`: The weights file of the pre-trained Keras model.

## Credits
- Original dataset: [Face Expression Recognition Dataset](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset)
- OpenCV: https://opencv.org/
- Keras: https://keras.io/

## License
This project is licensed under the [MIT License](LICENSE).



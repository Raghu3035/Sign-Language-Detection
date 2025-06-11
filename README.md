# Sign-Language-Detection
Problem Statement:
Communication barriers can be a real challenge for those who use sign language. Since many people aren't familiar with it, conversations can become quite tricky. This project aims to tackle that issue by developing a real-time system that captures sign language gestures through a webcam and converts them into text.

Solution:
This project harnesses the power of computer vision and machine learning to identify hand gestures in real time. It utilizes MediaPipe for pinpointing hand landmarks and employs Scikit-Learn’s RandomForestClassifier to classify the signs. The system can recognize various hand gestures and translate them into letters or words.

Features:
1. Real-time hand tracking using MediaPipe.
2. Gesture classification with Scikit-Learn.
3. Webcam-based interaction for ease of use.
4. Expandable dataset to include more gestures.

Tech Stack:
1. Python (Programming Language)
2. OpenCV (Computer Vision)
3. MediaPipe (Hand Landmark Detection)
4. Scikit-Learn (Machine Learning Classifier)
5. NumPy & Pickle (Data Processing & Storage)

Steps and Instructions:
1. Install Dependencies
   Ensure you have Python 3.6+ installed, then run: pip install -r requirements.txt
2. Collect Sign Language Data
   Run the script to capture hand gesture images: python collect_imgs.py
3.  Create the Dataset
   Convert collected images into a structured dataset: python create_dataset.py
4. Train the Model
   Train a RandomForestClassifier to classify sign gestures: python train_classifier.py
   Once training is complete, it saves the trained model.
6. Run the Real-Time Detection
   Use the trained model for real-time sign detection: python inference_classifier.py
   This will open a webcam feed and recognize gestures in real time.

Demo Video:
https://drive.google.com/file/d/1AMx3TscSTdKXud862zEKE1m5IRsS0mCT/view?usp=sharing

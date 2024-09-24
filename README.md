# Soccer Pose Decoder

**Soccer Pose Decoder** is a machine learning application that detects and analyzes famous soccer players' poses in real-time video feeds. Built using Python, OpenCV, and MediaPipe, this project classifies specific body movements associated with soccer players. The model is trained using a neural network optimized for pose detection accuracy.

## Features

- **Real-Time Video Processing**: Analyze and predict soccer players' poses using live video feeds.
- **Player-Specific Pose Recognition**: Detect famous soccer celebrities' poses, including Cristiano Ronaldo, Erling Haaland and Neymar.
- **High Detection Accuracy**: Neural network model optimized for pose recognition, with over 95% accuracy.
- **OpenCV Integration**: Real-time video feed processing.
- **MediaPipe Integration**: Accurate pose detection using landmarks for various body parts.

## Technologies Used

- **Python**: Core language used for development.
- **OpenCV**: For handling video feeds and image processing.
- **MediaPipe**: For pose detection and key landmark identification.
- **TensorFlow/Keras**: Used for training the neural network model.
- **NumPy & Pandas**: For data manipulation and preprocessing.

## Project Structure

- **body_detect.py**: Main script for handling video input and pose detection.
- **coords.cvs/**: Directory containing the dataset used for training.
- **body_language.pkl/**: Storing the model using the pickle library

## Future Features

- **Additional Players**: Extend the model to recognize more players and their iconic poses.
- **Multi-Person Pose Detection**: Enable detection of multiple players in the same frame.
- **Action Prediction**: Predict the next possible action based on the detected pose.
- **Performance Analytics**: Provide feedback on the similarity between detected poses and real player movements.

## Screenshots

| Pose Detection | Real-Time Analysis | Model Training |
|----------------|--------------------|----------------|
| ![Pose Detection](screenshots/pose_detection.png) | ![Real-Time Analysis](screenshots/real_time.png) | ![Model Training](screenshots/model_training.png) |

# Sign Language Detection with Python and Scikit-Learn

This project demonstrates sign language detection using machine learning techniques with Python and Scikit-Learn. The goal is to create a model that can recognize sign language gestures from images or video frames.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Training](#training)
- [Evaluation](#evaluation)
- [Final Result](#final-result)

## Features
- Detect and recognize sign language gestures.
- Utilizes Scikit-Learn for machine learning.
- Supports image and video frame input.

## Requirements
- Python 3.x
- Scikit-Learn
- OpenCV
- NumPy
- Matplotlib

You can install the necessary Python packages using the following command:

```bash
pip install scikit-learn opencv-python numpy matplotlib
```

## Setup
1. **Clone the repository** or download the project files:

   ```bash
   git clone https://github.com/safacharfi/Sign-language-detection-with-Python-and-Scikit.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Sign-language-detection-with-Python-and-Scikit
   ```

## Usage
1. **Collect Images**: Use `collect_img.py` to capture images of the sign language gestures you want to train the model on.

2. **Prepare Dataset**: Use `create_dataset.py` to organize and prepare your dataset of sign language images.

3. **Train the Model**: Run `training.py` to build and train the model using the prepared dataset.

4. **Test the Model**: Use `testing.py` to evaluate the performance of the trained model on new images or video frames.

## Training
To train the model, ensure you have prepared your dataset using `create_dataset.py`. Then, execute `training.py` to start the training process. The script will save the trained model to a file for future use.

## Evaluation
Evaluate the model's performance by running `testing.py` with test images or video frames. The script will provide metrics and visual feedback on the model’s accuracy and predictions.

## Final Result

### Example A
![Example A](https://github.com/user-attachments/assets/1b6d0a1e-07a4-47e9-9a13-021ed0e7643f)

### Example B
![Example B](https://github.com/user-attachments/assets/79becfbf-0a9b-43dd-920e-83cbe3501469)

### Example L
![image](https://github.com/user-attachments/assets/d936c717-c695-4c4d-9657-c614fed99737)



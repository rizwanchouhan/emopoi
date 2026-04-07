# EmoPOI: Emotion-Based Point of Interest Recommendation

<img style="max-width: 100%;" src="https://github.com/rizwanchouhan/DT3DPE/blob/main/resources/wax.png" alt="VERHM Overview">

# Overview

This work introduces an emotion-aware POI recommendation system that uses facial features and video-based emotion recognition (CNN + LSTM) along with age and gender. It also proposes the EmoPOI dataset and achieves improved accuracy over existing methods.

# 👁️💬 Architecture

The overview of the proposed methodology.

<img style="max-width: 100%;" src="https://github.com/rizwanchouhan/emopoi/blob/main/resources/architecture.png" alt="EMOPOI Overview">

# Workflow

To get started, ensure you have the necessary libraries installed:

1. TensorFlow
2. OpenCV
3. Numpy
4. Dlib
5. EmoPOI files
6. GUI (Tkinter)

# Installation

1. Install TensorFlow:
   ```
   pip install tensorflow
   ```

2. Install OpenCV:
   ```
   pip install opencv-python
   ```

3. Install Numpy:
   ```
   pip install numpy
   ```

4. **Option 1:** Download the Dlib and EmoPOI files as external zip files and extract them into the main project directory/folder where your project files are stored.

   **Option 2:** If you're using PyCharm IDE, you can install the Dlib library directly in the project settings by navigating to Configure Interpreter and adding your required libraries from there.

# Datasets

- **FER-2013:** You can download the FER2013 dataset from [here](https://www.kaggle.com/datasets/msambare/fer2013).

- **EmoPOI:** EmoPOI dataset samples are available [here](https://drive.google.com/file/d/1TtJNkrWSFkIMW72-xnpBuRD7LTuxSEal/view?usp=sharing). The complete EmoPOI dataset will be available upon request for research purposes after the paper is accepted.
_age_gender_recognition.py` (provide the proper path to your video). Based on the recognized emotion, gender, and age group, you will receive personalized POI recommendations suited to the user's preferences.

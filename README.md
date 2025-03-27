# Qur'anic Sign Language Recognition System (QSLRS)

## Overview
This project implements a **CNN-based Qur'anic Sign Language Recognition System** to assist **deaf and dumb Muslims** in learning and practicing **Islamic ceremonies** by recognizing **Arabic sign language hand motions** associated with Qur'anic letters. The system is designed to classify **dynamic and static gestures** using **deep learning models**.

## Features
- **Gesture Recognition:** Recognizes Arabic sign language gestures representing Qur'anic letters.
- **Dataset Preparation:** Includes image preprocessing and augmentation for better model performance.
- **Deep Learning Model:** Utilizes **Convolutional Neural Networks (CNNs)** for feature extraction and classification.

## Dataset
- The dataset consists of images representing **Qur'anic letters** in sign language.
- Preprocessing includes **normalization, augmentation, and filtering** to enhance recognition accuracy.

## Technologies Used
- **Python**
- **TensorFlow / Keras** (for CNN model training)
- **OpenCV** (for image processing)
- **Jupyter Notebook** (for development and experimentation)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/qslrs.git
   cd qslrs
   ```
2. Run the notebook:
   ```bash
   jupyter notebook qslrs.ipynb
   ```

## Model Training
- The CNN model is trained on the dataset using multiple layers for **feature extraction** and **classification**.
- Hyperparameters such as learning rate, batch size, and number of epochs are tuned for optimal performance.
- The model aims to achieve **high accuracy** in recognizing Qur'anic sign language gestures.

## Usage
1. **Train the model** using the dataset.
2. **Use the trained model** to recognize real-time sign gestures.
3. **Evaluate performance** using test images and validation metrics.



## Acknowledgment
This project is inspired by research on sign language recognition and aims to make Islamic education more accessible to the **deaf and dumb community**.


# DisasterVision Classification: AI for Earthquake Impact Analysis

## Overview

DisasterVision Classification is a cutting-edge deep learning framework developed to categorize the degree of damage to buildings from satellite imagery following earthquakes. Utilizing the sophisticated U-Net convolutional neural network architecture, this tool distinguishes various levels of structural damage, assigning color codes for clear visual interpretation.

## Key Features

- Automated classification of building damage post-earthquake.
- Advanced image segmentation capabilities using the U-Net model.
- Data augmentation for improved model robustness.
- Evaluation metrics including IoU, Precision, and Recall for performance assessment.

## Getting Started

### Prerequisites

Ensure you have the following requirements installed:

- Python 3.x
- Keras, TensorFlow
- Numpy, OpenCV
- Matplotlib
- Scikit-learn

### Installation

To set up the project environment:

1. Clone the repository
2. Navigate to the project directory: cd DisasterVision-Classification
3.  Install the required dependencies: pip install -r requirements.txt


### Usage

Follow these steps to prepare your dataset and train the model:

1. Place your image files in `Images/` and label files in `Labels/`.
2. Run `augment.py` to augment the data: python3 augment.py
3. Execute `mask.py` to generate masks for training: python3 mask.py


4. Open and run the Jupyter notebook `Proposed_model.ipynb` to train the model.

5. After training, use the model to classify new images and view the results.

## Model Architecture

Our U-Net architecture is tailored for precise image segmentation tasks, which is critical for accurate damage assessment in post-disaster scenarios.

## Results

The trained model achieves a high degree of accuracy, with performance metrics to back its reliability. Below are some of the classified images depicting the model's accuracy.






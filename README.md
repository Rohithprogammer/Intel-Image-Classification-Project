# Scene Classification Using CNN and Transfer Learning

## Dataset
Intel Image Classification Dataset

https://www.kaggle.com/datasets/puneet6060/intel-image-classification

## Project Overview

This project performs scene classification using the Intel Image Classification Dataset.

Two deep learning approaches were implemented:

1. Custom CNN with Data Augmentation
2. MobileNetV2 Transfer Learning

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn

## Results

Model Test Accuracy 

| CNN + Data Augmentation | 81.2% |
| MobileNetV2 | 88.3% |

## Best Model

MobileNetV2 achieved the highest test accuracy of 88.3%.

## Repository Contents

- Scene_Classification_CNN_MobileNetV2.ipynb
- cnn_accuracy_loss_curve.png
- cnn_confusion_matrix.png
- model_comparison.png
- error_analysis.png
- classification_report.txt
- ## How to Run

1. Open the Kaggle Notebook or Jupyter Notebook.
2. Install the required libraries:
   - TensorFlow
   - NumPy
   - Matplotlib
   - Seaborn
   - Scikit-learn
3. Download the Intel Image Classification Dataset from Kaggle.
4. Update the dataset path if necessary.
5. Run all notebook cells sequentially.
6. View the generated evaluation metrics, confusion matrix, and comparison results.

# Cat vs Dog Image Classification using Transfer Learning

This project implements a deep learning image classifier that distinguishes between cats and dogs using Transfer Learning with MobileNetV2 and TensorFlow.

## Project Overview

The objective of this project is to explore the effectiveness of Transfer Learning for image classification tasks. A pre-trained MobileNetV2 model was fine-tuned to classify images into two categories: Cat and Dog.

Data augmentation techniques were applied to improve generalization and reduce overfitting.

## Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Techniques Implemented

- Image Preprocessing
- Data Augmentation
- Transfer Learning
- Fine-Tuning
- Binary Image Classification
- Performance Evaluation

## Results

| Metric | Score |
|----------|----------|
| Test Accuracy | 98.95% |
| Test Loss | 0.0336 |
| Precision | 0.99 |
| Recall | 0.99 |
| F1-Score | 0.99 |

The model correctly classified 1979 out of 2000 test images, with only 21 misclassifications.

## Repository Structure

- `Cat_vs_Dog_CNN.ipynb` - Complete implementation
- `requirements.txt` - Required libraries
- `images/` - Training curves, confusion matrix, and prediction outputs

## Conclusion

The MobileNetV2 transfer learning model achieved excellent classification performance on unseen images. The high accuracy, precision, recall, and F1-score demonstrate the effectiveness of transfer learning for image classification tasks.

This project highlights the practical application of CNNs, Transfer Learning, Data Augmentation, and Performance Evaluation techniques in solving a real-world image classification problem.

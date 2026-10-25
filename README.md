CNN

**IT Elective 3 (DSS Technologies)**

## Overview

This notebook is a laboratory activity focused on building and evaluating a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset. The project demonstrates the full workflow of deep learning for computer vision, including data loading, preprocessing, model construction, training, validation, and evaluation.

The activity is designed to be run in Google Colab with GPU acceleration and emphasizes understanding the CNN workflow and interpreting model performance.

---

## Dataset

**Dataset:** CIFAR-10  
**Image size:** 32 × 32 RGB  
**Classes:** 10  
**Total images:** 60,000

Class names:
- airplane
- automobile
- bird
- cat
- deer
- dog
- frog
- horse
- ship
- truck

### Data split
- Training: 45,000 images
- Validation: 5,000 images
- Test: 10,000 images

The dataset is loaded using TensorFlow/Keras and split into training and validation sets with a fixed random seed and stratification to preserve class balance.

---

## Framework and Libraries

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## Objective

Train a CNN model to classify images into one of 10 classes and evaluate its performance using:

- accuracy
- confusion matrix
- classification report
- validation and test metrics

---

## Requirements

### Recommended environment
- Google Colab
- GPU runtime enabled
- Internet access for dataset download

### Runtime note
> Run in Google Colab (Runtime → Change runtime type → GPU). Take a screenshot of the output of each task section.

---

## Setup

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Ensure the runtime is set to **GPU**.
3. Run all cells in order.
4. Keep the dataset available in the working directory or allow the notebook to download it automatically.

---

## Workflow

The notebook follows a typical deep learning pipeline:

1. Import required libraries
2. Set random seeds for reproducibility
3. Load CIFAR-10 dataset
4. Prepare train/validation/test split
5. Inspect class distribution
6. Build CNN model
7. Train the model
8. Validate performance
9. Evaluate on test data
10. Generate confusion matrix and classification report
11. Interpret and document results

---

## Expected Outputs

The notebook should produce:

- dataset summary
- class distribution table
- model training results
- validation metrics
- test metrics
- confusion matrix
- classification report
- final assessment of model performance

---

## Notes

This project is intended for a classroom lab or educational exercise. It demonstrates how image classification models are built in practice using CNNs and how evaluation metrics are used to understand model behavior.

---

## License and Source

The dataset used in this activity is the CIFAR-10 dataset, commonly used for benchmarking image classification models in machine learning and computer vision research.

---

## Summary

This CNN laboratory activity provides a practical introduction to deep learning for image classification, using one of the most widely used benchmark datasets in computer vision. It is useful for learning model design, training strategies, and evaluation methods in a structured and hands-on way.

# ECG-Arrhythmia-Classification-CNN
This project presents a Convolutional Neural Network (CNN)-based approach for classifying ECG heartbeat images generated from the MIT-BIH Arrhythmia Dataset. The original ECG signals are stored in CSV format and are first converted into waveform images. These images are then used to train and evaluate a CNN model for automatic heartbeat classification.

The project demonstrates how one-dimensional ECG signals can be transformed into two-dimensional images and classified using image-based deep learning techniques.

## Features

- Load ECG heartbeat data from CSV files.
- Convert ECG signals into waveform images.
- Automatically organize images into class-specific folders.
- Preprocess images using PyTorch transforms.
- Train a Convolutional Neural Network (CNN).
- Evaluate model performance on the test dataset.
- Calculate:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Generate a Confusion Matrix for performance visualization.

---
## Dataset

This project uses the **MIT-BIH Arrhythmia Dataset** in CSV format.

**Dataset:** https://physionet.org/content/mitdb/1.0.0/

The dataset contains:

- **Training samples:** 87,554
- **Testing samples:** 21,892
- **Signal length:** 187 ECG values per heartbeat
- **Classes:** 5 heartbeat categories

| Class | Description |
|-------|-------------|
| 0 | Normal Beat (N) |
| 1 | Supraventricular Ectopic Beat (S) |
| 2 | Ventricular Ectopic Beat (V) |
| 3 | Fusion Beat (F) |
| 4 | Unknown Beat (Q) |

---

## Technologies Used

- Python
- PyTorch
- torchvision
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

---

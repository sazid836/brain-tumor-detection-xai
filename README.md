# brain-tumor-detection-xai

````md
# Brain Tumor Detection with Ensemble Learning and Explainable AI

## Overview
This project presents an advanced deep learning framework for detecting brain tumors from MRI scans using ensemble learning and Explainable AI (XAI) techniques. The system combines multiple CNN architectures including EfficientNetB7, InceptionV3, and Xception to improve classification accuracy and robustness.

To increase model interpretability, Grad-CAM++ is used for heatmap visualization, helping users understand which regions of the MRI contributed most to the prediction.

---

## Features
- Brain tumor classification using MRI images
- Ensemble learning with multiple CNN models
- Explainable AI using Grad-CAM++
- Hyperparameter tuning with Optuna
- K-Fold Cross Validation
- High accuracy and robust performance
- Heatmap visualization for model interpretation

---

## Technologies Used
- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- LightGBM
- Grad-CAM++

---

## Model Architecture
The project combines:
- EfficientNetB7
- InceptionV3
- Xception

These models are integrated using a soft-voting ensemble strategy with LightGBM as a meta-learner.

---

## Dataset
MRI brain tumor image datasets were used for training and evaluation.

Dataset includes:
- Tumor MRI images
- Non-tumor MRI images

---

## Project Structure
```bash
brain-tumor-detection-xai/
│
├── dataset/
├── notebooks/
├── models/
├── results/
├── images/
├── src/
│   ├── train.py
│   ├── predict.py
│   ├── preprocessing.py
│   └── gradcam.py
├── requirements.txt
├── README.md
└── LICENSE
````

---

## Installation

```bash
git clone https://github.com/yourusername/brain-tumor-detection-xai.git
cd brain-tumor-detection-xai
pip install -r requirements.txt
```

---

## Run the Project

```bash
python src/train.py
```

For prediction:

```bash
python src/predict.py
```

---

## Results

* Achieved 99.83% accuracy
* Improved prediction stability using ensemble learning
* Generated Grad-CAM++ heatmaps for explainability

---

## Future Improvements

* Deploy as a web application
* Add real-time MRI prediction
* Improve multi-class classification
* Integrate cloud deployment

---

## Author

Zawad Al Sazid
AI & Big Data Student, Woosong University

---

## License

This project is for educational and research purposes.



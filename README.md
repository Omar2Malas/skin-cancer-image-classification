# skin-cancer-image-classification
Machine learning project for skin cancer classification using image feature extraction and Random Forest Classifier .
🧠 Skin Cancer Classification
📌 Project Overview

This project aims to classify skin lesion images to determine whether they correspond to skin cancer and, when applicable, identify the cancer type.
A machine learning approach based on feature extraction and a Random Forest classifier was implemented.

Due to tight project deadlines, the focus was on building a functional baseline model, achieving an accuracy of 62%.

🛠️ Methodology

Image preprocessing (basic)

Feature extraction from skin lesion images

Training a Random Forest classifier

Model evaluation using accuracy and classification metrics

📊 Results

Model: Random Forest

Accuracy: ~62%

Note: Accuracy is reported as a baseline metric. For medical diagnosis tasks, metrics such as recall and AUC are more informative, particularly to reduce false negatives.

🚧 Limitations

Limited image preprocessing due to time constraints

No data augmentation

Classical ML approach instead of deep learning (CNNs)

🚀 Future Improvements

Advanced image preprocessing and segmentation

Data augmentation techniques

Use of convolutional neural networks (CNNs)

Hyperparameter optimization

Evaluation using medical-oriented metrics (Recall, AUC, F1-score)

📁 Technologies Used

Python

scikit-learn

NumPy

OpenCV

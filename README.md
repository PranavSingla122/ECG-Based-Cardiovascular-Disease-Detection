# ECG-Based-Cardiovascular-Disease-Detection

Overview
This project focuses on classifying ECG images into four categories using a fine-tuned ResNet50 deep learning model. The dataset consists of 928 ECG images categorized into:
✅ Myocardial Infarction (MI) Patients
✅ Patients with a History of MI
✅ Patients with Abnormal Heartbeats
✅ Normal ECGs

Performance Summary
The model achieved 99% accuracy on the test dataset, demonstrating high precision and recall across all categories.

Class	Precision	Recall	F1-score	Support
Myocardial Infarction Patients	1.00	1.00	1.00	44
History of MI Patients	0.96	0.96	0.96	26
Abnormal Heartbeat Patients	0.98	1.00	0.99	45
Normal ECGs	1.00	0.96	0.98	25

🔹 Final Test Accuracy: 98.57%
🔹 Best Validation Accuracy: 94.96%
🔹 Best Validation Loss: 0.1116

Model Details
Architecture: ResNet50 (Fine-tuned)
Optimized Using: Adam Optimizer (lr=0.0001, weight_decay=1e-4)
Loss Function: Cross-Entropy Loss with Class Weights
Regularization: Dropout (0.4), L2 Weight Decay
Early Stopping & LR Scheduler: Prevents overfitting and optimizes training
Data Augmentation: Rotation, Scaling, Color Jitter, Gaussian Blur, Perspective Transform

Training Progress
Training was conducted for 10 epochs, showing steady improvement:
📉 Train Loss: From 1.10 → 0.17
📈 Train Accuracy: From 52.2% → 94.6%
📉 Validation Loss: From 1.06 → 0.11
📈 Validation Accuracy: From 53.9% → 94.9%


This project showcases a powerful deep learning approach to ECG analysis for cardiovascular disease detection.

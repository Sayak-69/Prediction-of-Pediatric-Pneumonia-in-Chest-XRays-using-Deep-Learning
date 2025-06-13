# Dataset: https://www.kaggle.com/datasets/andrewmvd/pediatric-pneumonia-chest-xray/code
# Prediction-of-Pediatric-Pneumonia-in-Chest-XRays-using-Deep-Learning
# Abstract
Pneumonia is a potentially life-threatening infection, especially dangerous for children under
the age of five. Traditional methods of diagnosing pneumonia involve manual inspection
of chest X-rays by medical professionals, which can be time-consuming and susceptible to
human error. This project explores the application of deep learning in automating the
detection of pediatric pneumonia using chest X-ray images.
Using MobileNetV2 as the core deep learning model, the project implements a transfer
learning approach with preprocessing, data augmentation, and fine-tuning strategies. The
model is evaluated using a range of metrics including accuracy, precision, recall, F1-score,
confusion matrix, ROC and PR curves. Moreover, model explainability is addressed through
Grad-CAM heatmaps and an analysis of misclassified samples. The overall objective is to
build a trustworthy, interpretable, and accurate model suitable for deployment in medical
diagnostics.
# Introduction
Pneumonia is an acute respiratory infection that affects the lungs. It is one of the leading
causes of morbidity and mortality among children worldwide, particularly in low and middleincome countries. The World Health Organization (WHO) reports that pneumonia accounts for approximately 15% of all deaths of children under 5 years old, killing over 800,000 children in 2017 alone. Early diagnosis and timely treatment of pneumonia can significantly improve outcomes and reduce mortality. Chest radiography is the most commonly used diagnostic tool for
pneumonia, but its interpretation requires expertise and is often subject to intra- and interobserver variability. Moreover, the shortage of radiologists in many regions further delays timely diagnosis. Recent advancements in Artificial Intelligence (AI), particularly in Deep Learning (DL), have shown promising results in medical image analysis. Convolutional Neural Networks (CNNs) are especially adept at image classification and have been successfully applied to detect diseases such as diabetic retinopathy, skin cancer, and pneumonia from medical images. This project proposes a deep learning-based solution for the automatic classification of chest X-ray images into ”Pneumonia” and ”Normal” categories using MobileNetV2. By utilizing transfer learning, the model benefits from pre-learned features from the ImageNet dataset and adapts to the pneumonia classification task through fine-tuning. Additionally, interpretability techniques like Grad-CAM are used to visualize and validate the model’s
focus regions during prediction.

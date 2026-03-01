# Lungs-Disease-Project
Lung diseases affect the respiratory system and reduce the ability to breathe properly. Common conditions include Asthma, Chronic Obstructive Pulmonary Disease, Pneumonia, and Tuberculosis. Causes include smoking, pollution, and infections. Early diagnosis and proper treatment improve quality of life.
This project applies Deep Learning and Convolutional Neural Networks (CNN) to detect and classify lung diseases from Chest X-Ray images.

The model classifies images into 4 categories:

🦠 COVID-19

🫁 Normal (Healthy)

🦠 Viral Pneumonia

🦠 Bacterial Pneumonia

We used transfer learning with ResNet50 to improve performance and reduce training time.

The final model achieved an F1-Score of 0.82 (82% accuracy)
Dataset Information

Total Images: 532

Each class contains: 133 images

Training Split: 80% (428 images)

Validation Split: 20% (104 images)
Label	Category
0	COVID-19
1	Normal
2	Viral Pneumonia
3	Bacterial Pneumonia
Technologies Used

Python 🐍

TensorFlow / Keras

NumPy

Matplotlib

Scikit-learn

Google Colab

Transfer Learning

CNN (Convolutional Neural Network)

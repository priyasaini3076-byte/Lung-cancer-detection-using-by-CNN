# Lung Cancer Detection using CNN

**Name:** Priya  

**Registered Email:**  priyasaini3076@gmail.com 

**Course & Batch:** PBEL 2.2 Artificial Intelligence – Batch 8  

## Project Overview

Lung cancer is one of the leading causes of cancer-related deaths worldwide. Early detection plays a crucial role in improving patient survival rates.

This project builds a Convolutional Neural Network (CNN) model that analyzes CT scan images and predicts the type of lung cancer.

The application allows users to upload a CT scan image and receive a predicted cancer type along with a confidence score.

 ## PROBLEM STATEMENT
 
• Detecting lung cancer from CT scan images is a complex and time-consuming task.

• Doctors must manually analyze many medical images.

• Manual diagnosis may lead to human errors.

• Therefore, an automated AI-based detection system is needed to assist doctors.
  ## Objectives
  
• Detect lung cancer using a CNN model.

• Improve early diagnosis accuracy.

• Reduce manual effort in medical image analysis.

• Provide faster and more reliable detection.
## Dataset
The dataset contains CT scan images categorized into four classes:
• Adenocarcinoma

• Large Cell Carcinoma

• Squamous Cell Carcinoma

• Normal

The dataset is divided into:

• Training Set

• Validation Set

• Test Set

These images are used to train and evaluate the CNN model.
## Methodology
The project follows these steps:

Data Collection – Collect CT scan images.

Image Preprocessing – Resize and normalize images.

Model Development – Build the CNN architecture.

Model Training – Train the model using the dataset.

Testing and Prediction – Evaluate the model performance.
## CNN Architecture
The CNN model includes the following layers:

• Convolution Layer – Extracts important image features.

• MaxPooling Layer – Reduces image size while keeping key information.

• Flatten Layer – Converts feature maps into a 1D vector.

• Dense Layer – Performs classification.

• Softmax Output Layer – Predicts the probability of each class.
## Model Training
• The CNN model is trained using the training dataset.

• The model learns patterns and features from medical images.

• Training improves the prediction capability of the model.

• TensorFlow/Keras libraries are used for training.
## Project Structure

lung-cancer-cnn/
│
├── notebooks/

│   └── lung_cancer_training.ipynb
│
├── models/

│   └── lung_cancer_cnn.h5
│
├── data/

│   └── Lung Cancer Detection Dataset
│
├── app.py

├── requirements.txt

├── README.md

└── .gitignore

## Results
After training the CNN model, the following results were achieved:

• Training Accuracy – ~96%

• Validation Accuracy – ~94%

• Test Accuracy – ~93%

The results show that the model can effectively detect lung cancer from CT scan images.
## Confusion Matrix
A confusion matrix is used to evaluate the classification performance of the model.

It helps to:

• Compare predicted results with actual results

• Identify classification errors

• Evaluate accuracy for each cancer category
## Advantages
• Helps in early detection of lung cancer.

• Provides faster diagnosis using AI.

• Achieves high prediction accuracy.

• Reduces the manual workload of doctors.

## Future Work
• Use larger and more diverse datasets.

• Apply advanced deep learning models like ResNet or EfficientNet.

• Improve model accuracy and performance.

• Deploy the system for real hospital applications. 
## Auther
Priya

B.Tech (CSE)

Email:
priyasaini3076@gmail.com

## License

This project is developed for educational and research purposes.

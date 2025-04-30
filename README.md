PCOS Detection using Clinical and Ultrasound Data
📌 Overview
This project aims to build an intelligent diagnostic system for Polycystic Ovary Syndrome (PCOS) using a combination of machine learning and deep learning (CNN) techniques. It integrates clinical features (like hormone levels, BMI, and follicle count) with ultrasound imaging data to enhance diagnostic accuracy and support early intervention.

🎯 Objectives
Develop predictive models for identifying PCOS using structured clinical data.

Apply convolutional neural networks (CNNs) to classify PCOS from ultrasound images.

Combine clinical and image-based insights for multi-modal diagnosis.

🗂️ Dataset
Clinical Dataset: Includes features like follicle count, FSH, LH, AMH levels, weight, BMI, etc. (/content/Pcos_data.csv)

Image Dataset: Ultrasound scans of ovaries collected from open-source datasets (e.g., Telkom University PCOS Ultrasound Dataset)

🛠️ Technologies & Tools
Languages: Python

Libraries: Pandas, Scikit-learn, Seaborn, Matplotlib, TensorFlow/Keras

Techniques: Random Forest, SVM, Logistic Regression, CNNs

Platforms: Google Colab, GitHub

📈 ML Models
Trained and evaluated Logistic Regression, Random Forest, and Support Vector Machine models on the clinical data.

Achieved high accuracy through feature selection and hyperparameter tuning.

🧠 Deep Learning (CNN)
Preprocessed ovarian ultrasound images using OpenCV and augmentation techniques.

Trained a Convolutional Neural Network to classify images into PCOS and non-PCOS categories.

🔗 Multi-Modal Fusion
Combined clinical and image model outputs to improve final prediction confidence using ensemble averaging or neural fusion techniques.

✅ Results
Clinical model accuracy: ~92%

CNN image classification accuracy: ~88%

Combined model performance: ~94% accuracy

📄 Outcome
A robust PCOS detection pipeline that can assist doctors in clinical decision-making.

Potential for extension into mobile diagnostic apps or hospital software integration.


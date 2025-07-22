# Heart_Attack_prediction


📌 Project Title: Heart Attack Prediction using CNN (Image Classification)
📷 Input Type: ECG Images
🎯 Goal: Classify ECG images into 4 categories related to heart health using a Convolutional Neural Network (CNN)

🧠 Core Components from Notebook:
📁 Dataset Structure:

4 classes: Myocardial Infarction, Abnormal Heartbeat, History, Normal

Images structured in train/test directories

📦 Preprocessing:

Image size resized to (224x224)

Normalization applied

Image augmentation used via ImageDataGenerator

🧠 CNN Model:

Custom CNN built using:

Conv2D + MaxPooling

Dropout, BatchNormalization

Flatten + Dense layers

Used Adam optimizer and categorical crossentropy

Added callbacks: EarlyStopping, ModelCheckpoint

📉 Evaluation:

Plotted accuracy/loss graphs

Confusion matrix

Classification report

Model accuracy achieved: [You can insert exact result here]

💾 Model Saved as: .h5 file (e.g., cnn_model.h5)

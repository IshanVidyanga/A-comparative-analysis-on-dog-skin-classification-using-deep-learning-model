🐶 Deep Learning Techniques for Canine Dermatology: A comparative analysis based on Sri Lanka

This repository contains the implementation of a comparative study of deep learning models to classify canine skin diseases such as canine scabies, hypersensitivity allergies, fungal infections, and healthy skin conditions.
The project was conducted as part of an undergraduate research study, focusing on enhancing the diagnosis of dog skin diseases through artificial intelligence techniques.

📄 Project Overview
Canine skin diseases are a common issue and are often misdiagnosed due to the similarity of clinical symptoms. This research aims to develop an automated skin disease prediction system using deep learning models to assist veterinarians and pet owners in early and accurate diagnosis.

A total of five deep learning models were implemented and evaluated:

Baseline CNN Model

Hybrid Model (CNN + ResNet50)

ResNet152V2 Model

EfficientNetB1 Model

MobileNetV3 Model

📁 Dataset
Total Images: 2,511 (original dataset)

Augmented Dataset: 12,565 images

Classes:

Canine Scabies

Fungal Infection

Hypersensitivity Allergies

Healthy

Data augmentation techniques were used to overcome dataset imbalance and improve model performance.

🚀 Models & Architecture
Each model was implemented using TensorFlow and Keras with transfer learning techniques.
The models were trained for 30 epochs with early stopping and fine-tuning applied.

Model	Training Accuracy	Validation Accuracy
Baseline CNN Model	90.23%	75.33%
Hybrid CNN + ResNet50	99.20%	96.70%
ResNet152V2 Model	92.05%	87.47%
EfficientNetB1 Model	99.95%	98.96%
MobileNetV3 Model	99.97%	98.76%
📌 Best performing models:
EfficientNetB1 and MobileNetV3

📝 Future Work
Improve model interpretability using Explainable AI (XAI) techniques.

Develop a real-time mobile/web application for practical deployment.

Expand the dataset by collecting more real-world images.

Explore lightweight model optimization for mobile environments.

🤝 Acknowledgement
This project was completed as part of the Undergraduate Final Year Research Project at Informatics Institute of Technology.
Special thanks to academic supervisors, veterinary consultants, and the local community who contributed to the dataset preparation.

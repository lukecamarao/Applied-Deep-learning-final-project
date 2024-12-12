Deep Learning Project: ACL Tear Classification using Axial MRI Slices
Project Overview
This project focuses on classifying ACL tears from axial MRI slices using deep learning techniques. By leveraging pre-trained models and custom architectures, the goal is to accurately identify ACL tears for medical diagnosis.
Dataset
* Input: Axial MRI slices of the knee.
* Classes: Normal, ACL Tear.
* Training: Stratified split ensuring balanced representation of ACL tears across splits.
Model Architecture
* Utilizes advanced convolutional neural networks such as InceptionV3, InceptionResNetV2, and EfficientNetB0 for feature extraction.
* Custom layers including GlobalMaxPooling2D and Dense layers are added for fine-tuning and classification.
Training
* The models are trained using a binary classification setup with Adam optimizer and learning rate scheduling.
Results 
Modified Efficient Net:   
Modified Efficient Net Saliency:
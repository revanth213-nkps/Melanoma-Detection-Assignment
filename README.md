# Melanoma-Detection-Assignment
# Project Name
> Melanoma Detection using Custom CNN

> A multiclass classification model built from scratch in TensorFlow to detect melanoma and other skin diseases from dermatoscopic images.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Project Pipeline](#project-pipeline)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project aims to automate the classification of malignant and benign oncological skin diseases, specifically focusing on detecting melanoma, which accounts for 75% of skin cancer deaths.
- A custom Convolutional Neural Network (CNN) was built to classify dermatoscopic images into 9 classes.
- The dataset used is from the **International Skin Imaging Collaboration (ISIC)**, containing 2357 labeled images.
- The problem addressed: Helping dermatologists quickly and accurately diagnose skin cancer types, potentially saving lives and reducing manual effort.

## Project Pipeline
1. **Data Reading & Understanding**:
   - Dataset loaded and visualized (180x180 resized images).
2. **Dataset Creation**:
   - Train & validation datasets created with batch size = 32.
3. **Initial Model Building & Training**:
   - Custom CNN model designed without pre-trained weights.
   - Trained for 20 epochs.
   - Performance analyzed for overfitting/underfitting.
4. **Data Augmentation**:
   - Techniques like flipping, rotation, zoom applied to improve model generalization.
   - Retrained model for 20 epochs.
5. **Class Imbalance Handling**:
   - Dataset analyzed for class imbalance.
   - Under-represented classes augmented using **Augmentor library**.
   - Final model trained for 30 epochs.
6. **Evaluation & Conclusion**:
   - Accuracy, loss trends, and class-wise performance analyzed after each stage.

## Technologies Used
- Python 3.x
- TensorFlow 2.x
- Keras
- Augmentor library
- Google Colab GPU
- Matplotlib & Seaborn
- NumPy & Pandas

## Conclusions
- Data augmentation significantly improved the model's ability to generalize.
- Class imbalance correction further stabilized the performance across minority classes.
- Final model achieved satisfactory accuracy with balanced class-wise results.
- The approach shows promise in assisting dermatologists for early detection of melanoma.

## Acknowledgements
- Dataset: [International Skin Imaging Collaboration (ISIC)](https://www.isic-archive.com/)
- Starter code and problem inspiration provided by course instructors.
- This project is based on the assignment from CNN specialization coursework.

## Contact
Created by Revanth
revanth.nkps@gmail.com
- Feel free to contact me if you need anything!


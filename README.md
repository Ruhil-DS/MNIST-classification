# MNIST-classification

Under this project, i took the MNIST dataset which is a dataset of images(stored in form of arrays of pixel intensity) of digits from 0-9

This project predicts the digit on the image with about 90% accuracy. 
This accuracy is low, and i am working on improving it with approximately 97% accuracy. 

With this classification project, i learnt many new tricks and concepts.

Concepts like :
- Using OvO & OvR used for multiclass classification
- Confusion matrix
- cross_val_predict and cross_val_score
- Precision recall tradeoff
- ROC curve, area under roc curve
- Displaying the digit using the pixel intensities provided.
- Error analysis


I mainly used SGDClassifier and RandomForestClassifier for my predictions and am currently working on improving the accuracy using KNN model.

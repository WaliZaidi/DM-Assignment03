# Anomaly Detection in Credit Card Transactions using Transformer Autoencoder

This repository contains code for building a Transformer-based Autoencoder for anomaly detection in credit card transactions. The model is trained on the [Credit Card Fraud Detection dataset] from Kaggle.

## Requirements

- Python 3.x
- pandas
- numpy
- TensorFlow 2.x

## Model Evaluation

After training, the model's performance is evaluated using precision, recall, and F1-score metrics. Here are the evaluation results on the test set:

```
              precision    recall  f1-score   support

           0       1.00      0.95      0.97    284315
           1       0.00      0.09      0.01       492

    accuracy                           0.95    284807
   macro avg       0.50      0.52      0.49    284807
weighted avg       1.00      0.95      0.97    284807
```

## Statistics 

![image](https://github.com/WaliZaidi/DM-Assignment03/assets/109783661/62d3d257-de5d-4277-9057-2eb85f4f31bf)

The above is the ROC AUC graph for our model, as you can see its quite accurate at differenciating the non-anomoulous from the anomolous data points.

![image](https://github.com/WaliZaidi/DM-Assignment03/assets/109783661/04312dd5-959f-4c33-a5ed-3a4d8debb70f)

The above is the confusion matrix for the model, which reflects the data in the ROC AUC graph in a more digestable manner.

---

Feel free to customize this README according to your project's specific details and requirements.

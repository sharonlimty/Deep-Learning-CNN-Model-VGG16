# Deep Learning application using Transfer Learning

## 1. Objective

A Convolutional Neural Network (CNN) model, using Transfer Learning, has been developed to classify the Pokémon dataset into their respective categories.

## 2. Dataset

5 categories of Pokémon

## 3. Summary of results obtained

The performance evaluation of the CNN model has been carried out using the following metrices:

## • Training and Validation Accuracy/ Loss

Upon finetuning of the CNN model, the validation accuracy has improved over more epochs of training. However, the validation loss remained steady with minimal improvement.

## • Precision At Recall

Precision at recall rate was within a good range of 83.3%, outperforming the baseline of 50%. 

## • Area Under Curve (AUC)

Test AUC was achieved at 96.5%, indicating good true positive rate (recall) and false positive rate trade off.

## • Prediction Validation Results

Good prediction validation results were obtained with 15 out of 16 Pokémons being predicted correctly as plotted.

## • Confusion Matrix

Slightly higher than average false positives of category '3' which corresponds to the above validation results where blue Charmanders were observed. 

## 4. Conclusion

A CNN model has been successfully built using Transfer Learning to classify the categories from the Pokémon dataset. Improvements can be made to train the CNN model with a large and general enough dataset. Using transfer learning enables one to take advantage of the previously learned feature maps, without having to start from scratch by training a large model on a large dataset.

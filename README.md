# Plant-Pathology-Image-Classification
A model which includes Exploratory Data Analysis and the classification model of a dataset of images of plant leaves. The leaves are divided into 4 different categories, that are healthy, scab, rust and mulriple diseases. 

# Data Description
Data has been taken from kaggle. It includes 3 csv files: test, train and submission. It also includes a folder with the images of the plant leaves. 
## train.csv
image_id: the foreign key
combinations: one of the target labels
healthy: one of the target labels
rust: one of the target labels
scab: one of the target labels

## images
A folder containing the train and test images, in jpg format.

## test.csv
image_id: the foreign key
sample_submission.csv
image_id: the foreign key
combinations: one of the target labels
healthy: one of the target labels
rust: one of the target labels
scab: one of the target labels

On this data, thorough EDA has been performed along with the application of models such as Gradient Boosting, Random Forest and SVM. The results have thus been compared to find which of the traditional models perform best on this.

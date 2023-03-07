# ML_on_CIFAR-10
Implementing 5 Machine Learning methods to CIFAR-10 dataset and comparing the results.

## Explanation of the project
CIFAR-10 classification problem is an image classification problem where we are required to 
build models to classify the correct images into correct categories. For example, when input a 
bird image the model is expected to put it in the class named as “Bird”, which is one of the 10 
different classes in CIFAR-10 dataset. There are 60000 32x32 colour images in these 10 classes, 
with 6000 images per class. In this project I applied 5 different ML method, namely KNN, Linear Regression, SVM, MLP, and CNN.

As can be predicted Linear Regression has produced a high error (12.18% accuracy) since 
this is a classification problem and LR is used for regression problems. However, CNN has 
yielded the best result (55% accuracy) out of all models. This is not surprising, since CNN is mainly used for 
image processing and classification. By changing the parameters of CNN, like the number of 
layers, we could even increase this accuracy score to higher levels. The second-best result is 
noticed in KNN. The accuracy of the model may not be good enough since the dataset is large 
and the model complexity is very low. MLP and SVM follows KNN in accuracy score. I used 
PCA to apply SVM which improved its efficiency and increased its accuracy. Besides, in each 
model, I tried to perform additional pre-processing steps on the dataset to achieve better 
performance, like normalization



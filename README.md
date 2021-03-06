# Automating breast cancer diagnosis in histopathology

- Dataset was provided by [ICIAR2018 Challenge](https://iciar2018-challenge.grand-challenge.org).
- Data comprised by 400 images [1535x2048x3] of 4 classes (100 each): Benign, InSitu, Invasive, Normal.


Two approaches developed:
1. Traditional machine learning: Extract Fisher Vector representation from histopathology images and train a SVM classifier.
2. Deep learning: Learn representation automatically using a Convolutional Neural Network (CNN) in Pytorch (to be updated).

## Jupyter notebooks:

### 1) Reading and visualising images
[1-Data_Visualisation.ipynb](/notebooks/1-Data_Visualisation.ipynb)

### 2) Classification: FisherVector+SVM (80% test acc.)
[2-FisherVector_SVM.ipynb](/notebooks/2-FisherVector_SVM.ipynb)


![alt text](/src/utils/class_examples.png)


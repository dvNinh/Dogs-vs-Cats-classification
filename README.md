# Dogs and Cats classifications using CNN
### Dataset
The training dataset consists of 25000 pictures of dogs and cats. \
Purpose: label the images in the test1.zip dataset (12500 images). \
Data source: https://www.kaggle.com/c/dogs-vs-cats

### Dependencies
- Google colab
- Python 3.10.12
- Tensorflow 2.17
- Numpy
- Pandas
- Matplotlib
- Scikit-Learn

### Description
The training dataset contains 25,000 images, including 12,500 dog images and 12,500 cat images. I split those into 80% for training and 20% for testing. \
All images are brought to the same size of 128x128 for model training and testing. \
Model architecture: \
![image](https://github.com/user-attachments/assets/f9f2beb1-fb3c-46a9-b75f-a78cd1eede00)

### Accuracy
The accuracy was 81.38% on the test set of the CNN model trained on GPU.

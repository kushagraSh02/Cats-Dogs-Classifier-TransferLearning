# Cats-Dogs-Classifier-TransferLearning
A Cats and Dogs Image Classifier created using pretrained InceptionV3 Model.

Created an ImageClassifier using Transfer Learning.

Transfer Learning is a research problem in machine learning (ML) that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem.

I used the Inception Model V3, it is a deep learning model based on Convolutional Neural Networks, which is used for image classification. The inception V3 is a superior version of the basic model Inception V1 which was introduced as GoogLeNet in 2014.

We use pretrained layers of InceptionV3 upto the 'mixed7' layer, because the original last layer might be too specialized in what it has learned so it might not translate well into our application. Then we add our own dense layers to train the model specific to our dataset.

The dataset was taken from googleapi, named 'cats and dogs filtered'. The dataset contains images of cats and dogs divided into training and validation data.

Dataset URL: https://storage.googleapis.com/tensorflow-1-public/course2/cats_and_dogs_filtered.zip

Pretrained Inception Model weights file URL: https://github.com/kohpangwei/influence-release/tree/master/inception

# Data Science Projects

In this repository we have a set of projects related to Data Science that have as inputs, images and texts.

Among the algorithms used, we can highlight the Machine Learnign classification algorithms, such as SVM (Support Vector Machine), Naive Bayes and Random Forest.

Among the algorithms based on Deep Learning, we can mention the use of Convolutional Neural Networks such as VGG16, VGG19 and Resnet50. In addition, we have the use of a Recurrent Neural Network, the LSTM (Long Short Term Memory) for classification tasks.

---
# Sumary

- [Ulcer Image Recognition](#ulcer-image-recognition-medtech-dataset)
- [Handcrafted Features and Deep Features for Image Classification](#handcrafted-features-and-deep-features-for-image-classification-caltech-101-dataset)
- [Handwritten Digit Classification](#handwritten-digit-classification-mnist-dataset)
- [Fake News Detector](#fake-news-detector-fake-news-dataset)
- [Review Text Classification](#review-text-classification-amazon-review-dataset)
- [Wordcloud](#word-cloud-top-android-games-dataset)
---

## [Ulcer Image Recognition (Medtech Dataset)]()

In this project, we created a new approach to segmentation of pressure ulcer images. We compared the influence of superpixels (DISF, SLIC, LSC, ERS, SNIC, SEEDS) in the segmentation process in the pre-processing stage and adapted the segmentation algorithms such as IFT and DynIFT in the post-processing stage. The inclusion of the DISF method in the pre-processing stage allowed an increase in the evaluation metrics, compared to previous results.

Within the languages and tools that I have been working with, I have adapted a Java program that offers a pipeline for the entire process that uses, among others, the OPENCV library and other computer vision resources. In addition, we use languages such as Matlab and Python to include new methods in the program's pipeline.

## [Handcrafted Features and Deep Features for Image Classification (Caltech 101 Dataset)](https://www.instagram.com/fellipeassuncao/)

Recognition of objects from the extraction of color features, associated with the penultimate layer of a CNN such as (Resnet50, VGG16 and VGG19). The results showed that the fusion of color descriptors with the second-to-last layer of CNN does not contribute to the increase in accuracy. Thus, CNNs perform well in the process of feature extraction and object recognition.

## [Handwritten Digit Classification (Mnist Dataset)]()

Mnist is a dataset of 60,000 small grayscale 28×28 pixel square images of handwritten digits between 0 and 9. The task is to classify a given image of a handwritten digit into one of 10 classes that represent integer values from 0 to 9, inclusive.

This is a widely used classification example and can be considered a "solved" problem, since its accuracy reaches very good values for CNNs, reaching more than 99%. From this example it is possible to understand the classification pipeline of a model, make an adjustment of the parameters, propose improvements from the analysis and visualization of the results.

## [Fake News Detector (Fake News Dataset)]()

In this practice we will classify a text from classification algorithms based on Recurrent Neural Networks (RNN), specifically Long Short Term Memory (LSTM). 

We can classify texts using Natural Language Processing and different Classification Algorithms based on Deep Learning such as LSTMs and CNNs.

There are many classic classification algorithms like Decision Trees, Random Forest, SVM which can do a good job, but sometimes is a good idea use Deep Learning algorithms like LSTM.

A good reason to use the LSTM is that it is effective at memorizing important information. If we look at other non-neural network classification techniques, they are trained on multiple words as separate inputs which are just words with no real meaning like a sentence, and predicting the class will give the output according to statistics and not according to the meaning. This means that each word is classified into one of the categories.

This occurs differently in LSTM. In LSTM, we can use a multi-word string to find out which class it belongs to. This is very useful when working with Natural Language Processing. If we use proper layers of embedding and encoding in LSTM, the model will be able to figure out the real meaning in the input string and provide the most accurate output class. The following code will elaborate on the idea of how text classification is done using LSTM.

## [Review Text Classification (Amazon Review Dataset)]()

Text Classification is an automated process of classifying into predefined categories. We can classify emails into spam or non-spam, news articles into different categories like politics, stock market, sports, etc.

This can be done with the help of Natural Language Processing and different Classification Algorithms like Naive Bayes, SVM and even Neural Networks in Python.

## [Word Cloud (Top Android Games Dataset)]()

Word Cloud or Tag Clouds is a technique of visualizing texts that are used natively to visualize the tags or keywords of the websites. Below, we report some features:
- Each word in this cloud has a variable font size and color tone. Thus, this representation helps to determine highlight words.
- A larger font size of a word portrays its prominence more relative to other words in the cluster.
- Word Cloud can be built in various shapes and sizes based on the creators' vision.
- The number of words plays an important role when creating a word cloud.
- A greater number of words does not always mean a better word cloud, as it becomes confusing and difficult to read.
- A Word Cloud must always be semantically meaningful and must represent what it is intended for.

## [Analise and Data Visualization]()

In this project, I work with an example of data analysis and visualization based on a government database. To exemplify the use of the main Python libraries such as Pandas and Numpy, I elaborated some cases in which we can retrieve and manipulate data in a dataframe and use visualization features with MatplotLib.



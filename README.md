[![View on Medium](https://img.shields.io/badge/Medium-View%20on%20Medium-red?logo=medium)](https://towardsdatascience.com/how-to-create-an-app-to-classify-dogs-using-fastai-and-streamlit-af3e75f0ee28)  [![View on Streamlit](https://img.shields.io/badge/Streamlit-View%20on%20Streamlit%20app-ff69b4?logo=streamlit)](https://share.streamlit.io/khuyentran1401/dog_classifier/main/dog_classifier.py)
# Dog Classifier

This is a simple app to classify dogs using [fastai](https://docs.fast.ai/) and [streamlit](https://www.streamlit.io/). The app is deployed using Streamlit Sharing. Click [here](https://share.streamlit.io/khuyentran1401/dog_classifier/main/dog_classifier.py) to view and play with the app.  This project is inspired by Chapter 2 of the book Deep Learning for Coders with fastai & PyTorch.

Find the tutorial on how to create your own dog classifier in [this Medium article](https://towardsdatascience.com/how-to-create-an-app-to-classify-dogs-using-fastai-and-streamlit-af3e75f0ee28).

## Overview
### Dataset
450 different dog images are obtained using [Bing Image Search API](https://www.microsoft.com/en-us/bing/apis/bing-image-search-api). There are 150 images of each type of dog. The non-relevant images are removed. 
### Model
The model was trained to recognize 3 types of dog: Winner, Chihuahua, and Basset Hound using fastai. You can find the details of the training in [train_dog_classifier.ipnb](./train_dog_classifier.ipynb) notebook. The model was saved to [dog.pkl](./dog.pkl).


## How to use the app


Click Browse files to upload a dog image. Note that since the app is trained on just 3 kinds of dogs: Winner, Chihuahua, and Basset, make sure to upload only images of these dogs. 
![image](images/app_usage.gif)

## Results
I use my dog's photos and other photos I found from Facebook to test the performance of the model. Note that these images were not used to train the model. The model can recognize dogs with high accuracy. Here are some results I got:

![image](images/chihuahua_result.png)
![image](images/winner3_result.png)
![image](images/basset_hound_result.png)
![image](images/winner_result.png)


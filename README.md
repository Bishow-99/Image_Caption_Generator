# Image Caption Generator using Deep Learning

## Introduction
Image Caption Generator is the model to predict the caption of the
images based on their past experiences. The dataset used in this 
project is [Flickr8k](https://www.kaggle.com/datasets/adityajn105/flickr8k)
dataset which consist of more than 8000images and each image contain five differents
caption.



## Steps

1. In the first steps, a model is designed using a pretrained model
called VGG19 where inputs and outputs are imported to our model except
the prediction or final parts.
![VGG19](https://github.com/Bishow-99/Image_Caption_Generator/blob/main/Screenshots/1.png?raw=true)

2. Here, first of all, I preprocessed the input images then predict 
the features for them and finally store in the dictionary.

3. Moreover, from lowering the text to removing the punctuation I have
done each and every steps to preprocess the captions and store them in the list as well as I have added two
 same cls at the beginning and sep at the end of each caption.

4. In this steps, I have used 85% of the input images for training
purpose and remaining are for testing purpose.

5. Furthermore, This is a crucial steps where I have designed a functional
model using LSTM and Word Embedding method, where LSTM is used to train or track
the sequences of the text or caption of the images and Embedding is used for
halding tokenizer.
![Model](https://github.com/Bishow-99/Image_Caption_Generator/blob/main/Screenshots/2.png?raw=true)

6. In this steps I have test my model using Bleu score(Bleu score is
the method to testing the model using canditate and reference text)

7. Here, I have predict the caption of the image and display image using PIL libary.

Here is our all caption predicted by our model
![caption1](https://github.com/Bishow-99/Image_Caption_Generator/blob/main/Screenshots/3.png?raw=true)


![caption2](https://github.com/Bishow-99/Image_Caption_Generator/blob/main/Screenshots/4.png?raw=true)

![caption3](https://github.com/Bishow-99/Image_Caption_Generator/blob/main/Screenshots/5.png?raw=true)

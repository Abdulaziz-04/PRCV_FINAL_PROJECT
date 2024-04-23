Project Title - ImageNarrative : From Conventional to Cutting-Edge Captioning

Team Members :
- Abdulaziz Arif Suria
- Hussain Kanchwala
- Surabhi Gade
- Prem Sukhadwala

Project Description :
In this project we delved deep into the concept of image captioning and have build a CNN-RNN based image captioning model from scratch and also developed a Attention based CNN-RNN model. The models are trained on Flicker8k dataset and a comparitive analysis of these two models along with Vit-GPT2 based model from hugging face is done based on the following metrics:
- Peformance and loss graphs of models
- Rouge-L F-scores on Test dataset
- Top words distributions in predicted captions and original best matching caption of test dataset
- Top best captions and worst captions

The point of exploring the full transformer based image captioning architecture is that RNN has limitations with long subsequences and transformers provide room for parallel processing as well so it would provide a good insight into state of the art methods used in the domain.

Project Update  and File Structure: 
After discussing with the Professor, we have shifted our dataset from COCO to Flickr8K due to issues with memory and compute power. We have 2 models and compared with Vit-GPT2 model from Hugging Face, the files and folders for which are defined below:

- CNN RNN based architecture (FOLDER : CNN_RNN_Code)
    -   model.py : Code which defines the model architecture
    -   data_loader.py : Peforms preprocessing on data and establishes a complete data loader 
    -   cnn_rnn_network.ipynb : Performs training of the network, printing of loss functions and evalution of results

- CNN RNN with Attention based architecture (FOLDER : Attention_CNN_RNN)
    -   main.py : This file is where the model is defined, pre processing is done, model is trained and evaluation is done on the trained model.
    -   data_loader.py : Defines functions for preprocessing the data and generating dataloader

- Presentation Video : 
- Dataset URL : Flickr8K dataset (https://www.kaggle.com/datasets/adityajn105/flickr8k/data)
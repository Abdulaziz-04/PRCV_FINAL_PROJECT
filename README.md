Project Title - ImageNarrative : From Conventional to Cutting-Edge Captioning

Team Members :
- Abdulaziz Arif Suria
- Hussain Kanchwala
- Surabhi Gade
- Prem Sukhadwala

Project Description :
In this project we are delving deep into the concept of image captioning and would be building a CNN-RNN based image captioning model from scratch and also look towards implementing a similar approach following Pure Transformer based image captioning model which adopts the paper “CPTR: FULL TRANSFORMER NETWORK FOR IMAGE CAPTIONING”. The models will be trained on COCO dataset and we will provide relevant visualizations for comparative analysis. We will visualize and compare our models based on the following metrics:
- Peformance and loss graphs of models
- Rouge-L F-scores on Test dataset
- Top words distributions in predicted captions and original best matching caption of test dataset
- Top best captions and worst captions

The point of exploring the full transformer based image captioning architecture is that RNN has limitations with long subsequences and transformers provide room for parallel processing.

Project Update  and File Structure: 
After discussing with the Professor, we have shifted our dataset from COCO to Flickr8K due to issues with memory and compute power. We have developed 3 models in total which are defined below:

- CNN RNN based architecture (FOLDER : CNN_RNN_Code)
    -   model.py : Code which defines the model architecture
    -   data_loader.py : Peforms preprocessing on data and establishes a complete data loader 
    -   cnn_rnn_network.ipynb : Performs training of the network, printing of loss functions and evalution of results





- Dataset URL : Flickr8K dataset (https://www.kaggle.com/datasets/adityajn105/flickr8k/data)
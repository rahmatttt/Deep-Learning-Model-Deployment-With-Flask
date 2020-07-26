# Deep-Learning-Model-Deployment-With-Flask
A simple model deployment with flask

Directory Map :

| - Data (Contains dataset)
|
| - Model (Contains classification model)   
|
| - Src (Contains source code)
    | 
    | - templates (html code)
    | - Sentiment Analysis using BiLSTM.ipynb => source code for classification on jupyter notebook
    | - Model.py => source code contains functions for preprocessing
    | - app.py => source code to create the API
    | - request.py => source code to make request on the API

- The dataset is a movie review dataset consist of 6000 review with 2 labels (positive and negative).
- The model used is simple BiLSTM and trained with only 2 epochs

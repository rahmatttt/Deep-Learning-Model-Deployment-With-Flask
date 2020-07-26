# Deep-Learning-Model-Deployment-With-Flask
A simple model deployment with flask

Directory Map :

| - Data (Contains dataset) <br/>
| <br/>
| - Model (Contains classification model) <br/>   
| <br/>
| - Src (Contains source code)<br/>
    | <br/>
    | - templates (html code) <br/>
    | - Sentiment Analysis using BiLSTM.ipynb => source code for classification on jupyter notebook <br/>
    | - Model.py => source code contains functions for preprocessing <br/>
    | - app.py => source code to create the API <br/>
    | - request.py => source code to make request on the API <br/>

- The dataset is a movie review dataset consist of 6000 review with 2 labels (positive and negative).
- The model used is simple BiLSTM and trained with only 2 epochs

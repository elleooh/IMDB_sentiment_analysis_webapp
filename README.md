# IMDB Sentiment Analysis Webapp

This project creates and deploys a simple and interactive web app that performs sentiment analysis on IMDB movie reviews using PyTorch recurrent neural network library and utilizing AWS SageMaker.

1. [Tools](#tools)
2. [File Descriptions](#files)
3. [Selected Results](#results)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Tools <a name="tools"></a>

Model Creation and Tuning: PyTorch with AWS SageMaker
Model Deployment: AWS SageMaker
Interative Web App: AWS Lambda and AWS API Gateway

## File Descriptions <a name="files"></a>

- `SageMaker Project.ipynb`: end-to-end script detailing the steps from downloading and processing data to training and deploying the model for the web app. 

- `train/model.py` and `train/train.py`: scripts to construct and train the RNN model

- `serve/utils.py`, `serve/model.py`, and `serve/predict.py`: scripts to pre-process raw data, construct model, and perform prediction using the model

- `train/requirements.txt` and `serve/requirements.txt`: python libraries required to run training and inference code

-  `website/index.html`: simple HTML file to render the web app front-end


## Selected Results <a name="results"></a>

[image1]: ./website/screenshot/LOR-Positive.png "Positive Review"
[image2]: ./website/screenshot/StarWar-Negative.png "Negative Review"

## Licensing, Authors, and Acknowledgements <a name="licensing"></a>

[IMDB Dataset](http://ai.stanford.edu/~amaas/data/sentiment/)

Maas, Andrew L., et al. [Learning Word Vectors for Sentiment Analysis](http://ai.stanford.edu/~amaas/data/sentiment/). In Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies. Association for Computational Linguistics, 2011.

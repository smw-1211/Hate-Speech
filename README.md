[Python Project](https://www.python.org/downloads/)  

# Hate-Speech Detection using LSTM

##What is LSTM?

Long short-term memory network is a recurrent neural network, aimed to deal with the vanishing gradient problem present in traditional RNNs. Its relative insensitivity to gap length is its advantage over other RNNs, hidden Markov models and other sequence learning methods.


## Data used

To identify hate speech, I have extracted data from twitter as tweets and created 2 datasets as train and test with 70% train data and 30% test data which I have used to train and test the model.

When we train the model against this data with 10epochs, we achieve a commendable accuracy of 97.59%


## Installation  

There are 2 ways to run this project:
  
> Install python and setup the environment.

> Or upload this notebook to 
> 1. Google Colab (https://colab.google/) 
> 2. Jupyter Notebook (https://jupyter.org/try-jupyter/lab/?path=notebooks%2FIntro.ipynb)

  

## Run the Notebook

  

### If you are using Jupyter Notebook or Google Colab:

  

> Once you upload the notebook, ensure you add in the csv file to the same.

  

> Once both the files are uploaded, you are free to run the notebook online and view the insights gathered by me :star_struck:.

  

### If you are using Python environment

  

> Make sure python is rightly installed in the system using the following command -> python -v

  

> Create a directory and keep both the files in that directory.

  

> Once done, run all the cells of the notebook and check the insights.

  
## Insights of the model

> Here are some of the images which show words that the model has identified as hate speech

![lstm-output-images](./images/image.png)

![image-of-predicted-output](./images/output_image.png)


## Issues

  

Incase you have any difficulties or issues while trying to run the app you can raise it on the issues section.

  

## Pull Requests

  

If you have something to add or new idea to implement, you are welcome to create a pull requests on improvement.

  

## Give it a Star

  

If you find this repo useful , give it a star :star: so as many people can get to know it.
# AI: What Even _Is_ That Thing!?

This repo contains code related to the [AI: What Even _Is_ That Thing!?](https://docs.google.com/presentation/d/1bejmou_qyuVOtVRio4fi4lgdzkPPqxBQXJvX8cPlLVU/edit?usp=sharing) presentation.

[Fill out the News Classification Form](https://goo.gl/forms/nLcf2ol0o5dAJxGw1)
to help generate training data. 


## Explore ##

### Install ###
The easiest way to explore machine learning with python is to [install the
Anaconda Distribution](https://www.anaconda.com/distribution/) which contains a
variety of useful python packages in a single installation. Alternatively, you
can [download and install python](https://www.python.org/downloads/) and then
use [pipenv](https://pipenv.readthedocs.io/en/latest/) to install the packages
specified in this repo's Pipfile using `pipenv update`. 

Once you have python and jupyter up and running, use the `jupyter notebook
NewsClassifier.ipynb` command. If you used pipenv, you'll want to run `pipenv
run jupyter notebook NewsClassifier.ipynb`.

### How it works ###

The notebook code loads the TrainingData.csv file, which contains URLs and
corresponding classification labels gathered from the [News Classification
Form](https://goo.gl/forms/nLcf2ol0o5dAJxGw1). 

The code then loops over each URL, scraping the text content from the articles using [the Newspaper3k library](https://newspaper.readthedocs.io/en/latest/). 

The article text is then processed and input into 




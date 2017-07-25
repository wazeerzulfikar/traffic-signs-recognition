# Udacity Machine Learning Nanodegree Capstone Project

This deep learning project detects and recognises traffic signs on the road using Computer Vision.

## Install

This project requires Python 2.7 and the following Python libraries installed:

- Keras   1.1.2 with Theano 0.8.2 (Backend) 
- Scikit Learn   0.18 
- Skimage   0.12.3
- Numpy   1.11.1
- Pandas   0.18.1 
- OpenCV   2.4.11 
- Matplotlib   1.5.1    

## Datasets

The datasets are available in the following dropbox link:

https://www.dropbox.com/s/5fzosssyyiw2ved/datasets.zip?dl=0

The downloaded 'datasets' folder must be put in the project folder first.

## Code

The following jupyter notebooks constitute the code:

- Data_Preparation.ipynb - Loads data from 'datasets' folder, if already downloaded.
- Data_Exploration.ipynb - Explores and analyzes the data.
- Data_Training_And_Testing.ipynb - Trains models and tests them against test set.
- Detect.ipynb - Combines detection and recognition to find traffic signs from images.

## Run

In a terminal or command window, navigate to the top-level project directory then move to /code/ directory and run the following command in this order:

- jupyter Data_Preparation.ipynb
- jupyter Data_Exploration.ipynb
- jupyter Data_Training_And_Testing.ipynb
- jupyter Detect.ipynb

The 'storage' folder stores the models and weights of the trained classifiers. It also stores the numpy arrays of the training and testing data.

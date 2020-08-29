# MetalArchive-ML-Project
A machine learning project of metalarchive data

## Motivation & Objective
metal-archives.com is one of the largest website to search for metal band info. There are more than 130,000 band records on the site and users are able to write reviews of albums. 

The goal of the project is to build a machine learning model to predict the review score for the albums.

## Data Exploration
After cleaning and merging (The data from the site was huge so only death metal bands data were used):

<img width="986" alt="Screen Shot 2019-12-01 at 23 52 37" src="https://user-images.githubusercontent.com/51385490/91625519-0d7e1180-e976-11ea-874b-87c1ba5df6b9.png">

The score distribution: 

<img width="935" alt="Screen Shot 2019-12-02 at 15 00 00" src="https://user-images.githubusercontent.com/51385490/91625596-9d23c000-e976-11ea-9e1a-57e8f3b5710d.png">

## Features 
In-detail feature engineering is in the notebook. NLP is required towards review title and review contents. 

## Models & Results
Tried regression, trees and boosting models. 

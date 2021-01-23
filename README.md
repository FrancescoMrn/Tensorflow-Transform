# Tensorflow Transform - Data Pipeline

## Overview
This repo uses TensorFlow Transform (tf.Transform) and Apache Beam pipelines to implement data preprocessing for machine learning (ML).

The combination of TFT and Apache Beam allows to use resources on GCP in the most appropriate way - especially when expensive GPUs are used.
It can be used as template for later development of more complex pipelines.

## Data

Attributes Description:
| Column name        |                  Description                  |
|--------------------|:---------------------------------------------:|
| POSTED_BY          |  Category marking who has listed the property |
| UNDER_CONSTRUCTION |  Under Construction or Not                    |
| RERA               |  Rera approved or Not                         |
| BHK_NO             |  Number of Rooms                              |
| BHKORRK            |  Type of property                             |
| SQUARE_FT          |  Total area of the house in square feet       |
| READYTOMOVE        |  Category marking Ready to move or Not        |
| RESALE             |  Category marking Resale or not               |
| ADDRESS            |  Address of the property                      |
| LONGITUDE          |  Longitude of the property                    |   
| LATITUDE           |  Latitude of the property                     |   



[Link to the original Kaggle page](https://www.kaggle.com/anmolkumar/house-price-prediction-challenge?select=train.csv)

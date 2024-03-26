# ML_SGDRegressor-Toronto_apartment-
Applying machine learning to predict rentals price

## What is that mean ,  SGDRegressor ? 
SGDRegressor is a machine learning algorithm in Scikit-Learn that implements Stochastic Gradient Descent (SGD) to solve regression problems. It is a popular choice for large-scale regression tasks due to its ability to handle high-dimensional datasets and its fast training time.

![gradient_descent_1](https://github.com/ChaiouraMohammed/ML_SGDRegressor-Toronto_apartment-/assets/91562298/c10b1248-05ad-4529-97b4-ec32b9ddc293)

## Libraries to use 
In this project , we tried to use some basics of libraries for Machine learning in Python as pandas , matplotlib for visualization , seaborn for getting Linear Model and sklearn .
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from seaborn.linear_model import SGDRegressor
from sklearn.model_selection import train_test_split
from sklearn.metrics import *
```

##  Dataset description 
- Bedroom - How many bedrooms available
- Bathroom - How many bathrooms available
- Den - Whether den is available or not
- Address - Location
- Lat - Lattitude
- Long - Longitude
- Price - Apartment Rental price per month in CAD
- Dataset Link : https://www.kaggle.com/datasets/rajacsp/toronto-apartment-price

  ![image](https://github.com/ChaiouraMohammed/ML_SGDRegressor-Toronto_apartment-/assets/91562298/40733899-448d-46a6-a8dc-311cfe424f2b)

  ## Error management
  
  ![image](https://github.com/ChaiouraMohammed/ML_SGDRegressor-Toronto_apartment-/assets/91562298/27eb0d53-42de-4837-b23e-41194f462e7f)


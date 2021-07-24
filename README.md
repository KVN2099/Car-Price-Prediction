# Car Price Prediction
In this Python program, I developed a multilinear regression machine learning model able to predict a car's price in USD. The dataset I used can be found [here](https://www.kaggle.com/hellbuoy/car-price-prediction).

In this dataset, I separated the ```carname``` column into ```make``` and ```model```. Since the ```model``` column has specific values, I did not include it as a required parameter.

Additionally, I encoded all columns using ```sklearn.preprocessing.LabelEncoder```, as well as normalizing all columns except ```car_ID``` and ```price```.

This is my first solo machine learning model, so feel free to leave any positive and constructive feedback.

# Creadit-Card-Anomaly-Detection

In this project I used this [dataset](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud) from Kaggle.
It is 1 million rows of credit card fraud data,
it has 8 columns (['distance_from_home', 'distance_from_last_transaction',
       'ratio_to_median_purchase_price', 'repeat_retailer', 'used_chip',
       'used_pin_number', 'online_order', 'fraud'])

# Model
for model,I used tensorflow 2.12.0 and Sequential model.

## Neurons
I made 128 x 64 x 16 x 64 x 7 neurons for my model,each neuron has 'ReLu' as activation function except last one,it has 'Sigmoid'.
I used tensorflow.keras.layers.Dropout for help prevent overfitting.

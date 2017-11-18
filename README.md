# linear_regression
Basic implementation of linear regression and logistic regression using cloud datalab

Activate cloudshell and run following commands to create a new datalab instance:

``` bash
gcloud components install datalab
datalab create <name>
```

If there is an existing instance, then connect to datalab instance using following command:

``` bash
datalab connect <name>
```

# Dataset
We use stock market data downloaded from yahoo. Its placed in 'data/' folder

# Upload
Rather than creating a new notebook and dataset on cloud datalab, upload all contents in this repository to your cloud datalab instance

# Project Description

Initially we will build a linear regression model using a single layer neural net with Affine Transform. 
We perform linear regression for GOOGLE vs S&P 500 data for same range of dates (%age returns month over month). 
The model is expected to converge with following values of weight and bias. 
```
After 4999 iteration:
w: 1.067686
b: 0.008465
cost: 0.004600
```


We will extend this model to a Multiple regression model, where returns of Exxon stock price depends on NASDAQ share index and US Oil price.

This model will have two weights "NASDAQ" and "Oil price" and one bias.

The model is expected to converge with following values of weights and bias.
```
After 4999 iteration:
W1: [[ 0.25118706]]
W2: [[ 0.14642762]]
b: 0.003206
cost: 0.001672
```

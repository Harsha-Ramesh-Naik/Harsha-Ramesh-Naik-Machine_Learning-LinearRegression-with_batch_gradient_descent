# Harsha-Ramesh-Naik-Machine_Learning-LinearRegression-with_batch_gradient_descent
In this project you will train a linear regression model using a dataset that contains a collection of real estate listings in San Luis Obispo county. Given the square footage, the model can then predict the price of the house.

The dataset contains the multiple fields:
1. MLS: Multiple listing service number for the house (unique ID).
2. Price: the most recent listing price of the house (in dollars).
3. Bedrooms: number of bedrooms.
4. Bathrooms: number of bathrooms.
5. Size: size of the house in square feet.
6. Price/SQ.ft: price of the house per square foot.
   
The start-up python code reads the dataset, chooses the field size to create a 1D training set and
normalizes it with min-max scaling. Complete this code to perform the following tasks:
• Train the model with gradient descent.
o Loop for 2000 epochs. This number is small enough to allow you to debug the code
quickly. You’re welcome to increase the number of epochs to get better results.
o Initialize the parameter vector w with random numbers.
o Initialize the learning rate to 0.5.
• Generate a graph of MSE as a function of the number of epochs
• Plot the regression line over the training examples. The line is defined by ww = [ww0 ww1]TT
• Print the predicted price of a 5000 square foot house. Remember to “normalize” the square
footage first.

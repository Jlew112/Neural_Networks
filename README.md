# Neural_Networks

## Overview
For this project, we wanted to review investment opportunities for  companies and non-profit organizations across the country. We used many features like application type, Organization type, income ammount, and ask amount to see if we could predict whether the donation would be successful in helping these charities achieve their goals. Our goal is to hit 75% accuracy on our predictive model.

## Results
After attempting multiple iterations of our deep learning model, we were unable to successfully predict better than 63%. Our "IS_SUCCESSFUL" column was the target that we used to train our data.

Features used:
  - Application Type
  - Affiliation
  - Classification
  - Use Case
  - Organizaion Type
  - Income Amount
  - Ask Amount
  - Special Considerations

We removed the Name and EIN columns from the data as they are unique, and do not help the deep learning model detect, forecast, or recognize patterns in the success.
My BEST attempt (63%) was completed with 2 Hidden Layers with 8 and 6 Neurons each. That one used the RELU activation function, but I also tried Sigmoid to try to fit the machine better. Through my many interations, I added Layers, changed Neurons, changed activation functions, and tried to bin some of the infrequent occurences of variables in the data. Overall, I was UNABLE to hit the 75% success rate on predictions.

## Summary
I would also like to try a Random Forest model on this data set. I've really liked how they preform in my past experience, and the data set is just simple enough to work with that model type. I also like the interpertability of Rand Forest. Couple that with the high accuracy, and we may be able to train a model that would be able to hit the desired 75% accuracy.

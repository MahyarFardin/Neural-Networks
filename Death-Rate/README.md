# Overviwe

In this project I tried to predict death rate in differant palces using keras and neural
networsks.

# Dataset

The datset containes information about countries and their death rate and other features
, each row stands for one country and each column is the avrage data we have about that country.

# Walkthrough

  First I imported libraries which are needed for basic feature engineering and data-visualization
and dataset itself, then I extracted information about the general affairs of dataset to see the data type
of each column and to find the missing values. I removed some columns which were containing a lot on non 
numeric information then I started the hardest part which was filling some missing values. I found thath one of
them is duplicated so I dropped it then I realized that the second feature which I want to repair has a good correlation
with some columns so I applied LINEAR REGRESSION on that to find and replace missing values with best parameters.
Finally I applied a basic neural networsks on it in order to predict and I tried to excel it in every step.


# Results

- At the first model which did not have anything except neural networsks it self we got a 1225 MSE which stands for 35
MAE. This leads us to a 81 percent accuracy which is good for a model without anything but the imported point is we good
a pretty good history plot at the first move.

![](https://ibb.co/7z8zpWN)

- In the second step we added an early call back to avoid over fitting which worked perfect indeed.
 We could get a 27.5 MAE which leads us to a 85 percent accuracy.
 
- Adding dropouts did not act well it shows us that the number of nodes we have chosen were the best possible
and shrinking it led us to a 60 MAE or 56 percent accuracy.

- And at the final I decided to add batch size to control the amount of inputs and acted almost the same as the first model with 38 MAE.
 But the point is that in this model the output plot showed that our model did not trained well because there was a gap between validation loss and 
training evaluation.

![](https://ibb.co/YD7Ps9v)

# Feedback

If you have any feedback, please reach out to us at Mahyarfardinfar@gmail.com
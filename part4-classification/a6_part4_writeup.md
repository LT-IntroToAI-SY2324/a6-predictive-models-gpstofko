# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
Not very accurate, as many of the predicted genders compared to the actual genders are wrong. Standard scalar centers the values around the mean and allows for more accurate predictions. Also the accurarcy of the model without the standard scaler was 0.6875 which is quite low and not above 75% which is needed to justify correlation.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
The model is much more accurate with the standard scaler, 
With the standard scaler the accuracy is 0.8625, while without the standard scaler the accuracy of the model was 0.6875. The model is accurate enough with the standard scaler as 0.8625 is close to 1 so its mostly accurate.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
There was no pattern I could see, and the model did pretty well as especially with the standard scaler with 86% accurary.

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
No they would not.

# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
The R Squared coefficient for my model was 0.86, this means the model in relation to my testing data was pretty accurate, and is decently accurate 
2. Is your model accurate? Why or why not?
My model is decently accurate as the predicted values compared to the actual values are decently close and a 0.84 r-squared value is quite high for correlation.
3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
The 10-year-old car with 89000 miles is worth $9404
The 20 year old car with 150000 miles is worth $933
4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
The actual value of the car is so low compared to the others,that any significant error or off rounding causes the car value to drop below 0 instead of being positive and just less than it actual value.
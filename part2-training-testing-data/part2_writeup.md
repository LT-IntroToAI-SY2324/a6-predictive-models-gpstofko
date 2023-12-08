# Part 2 - Training and Testing Data Writeup

After completing `a6_part2.py` answer the following questions

## Questions to answer

1. What makes this model more effective than the model you created in the previous lesson?
This model trains itself then tests its own training making sure that the trainig is effective instead of assuming it is 100% of the time.

2. What does the R squared coefficient tell you about the model?
The r_squared value is 0.6 which means the model is not that correlated and effective at predicting.

3. Would you say that your model is accurate? What evidence supports your conclusion? Consider the meaning of the predicted and actual values in the context of the chart below from the American Heart Association’s website on understanding blood pressure.
I'd say the model is partly accurate, as there is some corelation with blood pressure and age in real life, and a R^2 value of 0.6 isn't too bad for telling correlation. As the arteries change with age, so does blood pressure, which is reflected in the data as while age increases so does blood pressure.
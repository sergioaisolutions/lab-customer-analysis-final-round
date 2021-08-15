# CONCLUSION ABOUT THE CREATED MODELS

After performing a One Hot Encoding process, the dimensions of the data increases exponentially, so is mandatory trying to reduce the number of features used by the model. In this case, we used a feature selection method called "Forward Feature Selection", and using only 20 features of the dataset, we were be able to achieve the same results as using all the features. The model used was Linear Regression Model.

# CONCLUSION ABOUT THE FEATURES CORRELATED WITH THE TOTAL CLAIM AMOUNT

After performing a deep EDA, we got some insights about what are the features that are more important to achieve a higher total claim amount from the customers. Lets start with the numerical features:

- Customer lifetime value: after some research, we concluded that the customer lifetime value is a metric that measures the relation of the customer with the company over time. We can see that the feature has a high positive correlation with the target, and this scenario makes sense if we read carefully the description of the metric. The higher the relation is with the customer, the bigger is the total claim amount obtained.

- Monthly premium auto: using the human sense, the most likely outcome for the meaning of this feature is a fee to pay each month by the customers for using some services and products from the company. The correlation is very high, so it makes sense in relation with the suggested meaning.

- Income: this feature is very rare, because the correlation that it has with the target is negative and high. The higher the income is, the lower the total claim amount is. Curious.

The categorical features that shows a bigger total claim amount difference between their categories are the next ones:

- Location code: suburban has a higher total claim amount. At the same time, rural has the lowest one.
- Policy type: Personal auto tends to have higher values in relation to the total claim amount.
- Renew offer type: the offer 1 looks the bring back a higher total claim amount.

# RECOMMENDATIONS

- Increase the engagement with the customers to get a higher customer lifetime value by each one.
- Try to increase the monthly premium auto subscriptions using, for example, some discounts.
- Focus the communication in the suburban area, and try to get insights of the other areas to increase the benefit from them.
- Discover why offer 1 works better and try to apply the found variables to the other offers.

# NEXT STEPS

- Get access to the real meanings of the features to get better insights.
- Try other models that maybe works better with this type of data.
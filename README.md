![boston png](https://cdn.passporthealthusa.com/wp-content/uploads/2017/04/passport-health-downtown-boston-travel-clinic.jpg?x90298)
# Boston AirB&B. Price prediction and objects clustering.

With one small data set available for free we will try to get some insights on the AirB&B market in Boston. 
Is it possible to predict rent price of the bed based on the apartment specification? What are the most common amenities and do they
matter in price prediction? Can we clearly cluster the objects and do those clusters fit into the Boston neighborhood map? 

Data set available here: https://www.kaggle.com/airbnb/boston has a lot of the data we need to clean and change before using in the prediction. We need to decide which fields are not benificial to our prediction and we can drop and wich ones are worth the trouble of cleaning. After cleanup and numeric fields generation I ended up with 2736 rows and 63 columns of clean and usefull data. Base on it our simple linear regression ended up with the following squered error values:
-test: 0.5878648832764807
-train: 0.5840263594330857
Those results are not perfect but acceptable so I am sure that with further data analysis we could achieve better predictions.





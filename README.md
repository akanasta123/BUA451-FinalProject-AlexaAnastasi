# BUA451-FinalProject-AlexaAnastasi

In this project, I analyzed an e-commerce dataset to extract business-relevant insights. After initially exploring the data, I decided the relevant insights to further analyze would be the order status breakdowns and monthly order volumes. 

The dataset used in my project was the Big Query Public Dataset: `thelook_ecommerce.orders`

I put together two bar graphs, one for each insight, to get a bigger picture view of the data for those insights. The Order Status Breakdown bar graph helped me understand fulfillment and return rates. The Monthly Order Volume helped me identify seasonal trends.

For predictive modeling, I used Logistic Regression to be able to predict whether or not an order would be returned. Due to class imbalance with this method, it had difficulty detecting returned orders. I then used a Decision Tree Classifier with class weighting to try to better predict if an order would be returned.

I found that the overall accuracy of the Decision Tree Classifier model was lower, however, it was able to better predict orders returned than the Logistic Regression.

This project used a simple linear regression model from Scikitlearn with Flipkart reviews borrowed from Kaggle as a means to replicate reviews of A.I chatbots, in turn, this model gives us a trend of whether or not to continue with improving and distributing A.I chatbots into the market.

## How It Works  

1. **Data Preprocessing**  
   - With the Flipkart reviews Cleans and preprocesses the Flipkart reviews dataset.
   - Calculate the sentiment scores of each review using the transformers pipeline.
   - Have all the sentiments normalised into -1 and 1, this is to show if there is a positive or negative trend of public satisfaction.

2. **Model Development**  
   - Sentiments calculated with the Transformers pipeline.
   - Imported Scikit Learn's Linear Regression.

3. **Visualization**  
   - Seaborn's scatterplot was used along with Matplotlib's Title for the X and Y axis.

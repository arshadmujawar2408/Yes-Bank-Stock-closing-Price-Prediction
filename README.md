# ML for Yes Bank Stock closing price priction
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock's closing price of the month.

**Programming Language** : Python

**Libraries used** : Pandas, Numpy, Matplotlib, Seaborn

**Notebook** : Google Colab

**Dataset Source** : Provided by Almabetter themself.

## Dataset 
We are given a dataset. It contains the following features.
```
- Date: It denotes date of investment done (in our case we have month and year).
- Open: Open means the price at which a stock started trading when the opening bell rang.
- High: High refer to the maximum prices in a given time period.
- Low: Low refer to the minimum prices in a given time period.
- Close: Close refers to the price of an individual stock when the stock exchange closed for the day.
```

- Total number of rows in data: 185
- Total number of columns: 5

## Data Cleaning and Manipulation
As you can see we have done 2 manipulations in the dataset and we found that we are good to go now as we changing date colunn datatype to datetime formats as well as we have created seperate columns for month and year from date column for better visualisation.

## Data Preparation
#

 1) Combine the categories of children and babies into a single category called "kids."
 2) Calculate the total number of bookings by adding the counts of kids and adults.
 3) Convert the data types of the following columns to string: ArrivingYear, ArrivingMonth, ArrivingDate, Canceled, and RepeatGuest.
 4) Convert the arrival date column to the datetime data type for accurate date and time calculations and analysis.


## Exploratory Data Analysis
Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:
   - Bar Plot.
   - KDE Plot.
   - Pie Chart.
   - Line Chart.
   - Violin Plot.
   - Box Plot.
   - Hist Plot.
   - Scatter Plot.
   - Pair Plot.

## ML Model Used:
Several machine learning algorithms were utilized in this project. These models include:
```
1. Mulltiple Linear regression
2. Lasso Regression
3. Ridge Regression
 ```
             
## Conclusion
```
1. At first we do the data wrangling then data cleaning and data transformation after that we do the Modeling part.
2. The trend of the price of Yes Bank's stock increased until 2018 and then Close,Open,High,Low price decreased.
3. Based on the open vs. close price graph, we concluded that Yes Bank's stock fell significantly after 2018.
4. Visualization has allowed us to notice that the closing price of the stock has suddenly fallen starting in 2018. It seems reasonable that the Yes Bank stock price was significantly impacted by the Rana Kapoor case fraud.
5. High, Low, Open are directly correlate with the Closing price of stocks.
6. The target variable is highly dependent on input variables.
7. Linear Regression has given the best results with lowest MAE, MSE, RMSE and MAPE scores.
8. Ridge regression shrunk the parameters to reduce complexity and multicollinearity, but ended up affecting the evaluation metrics.
9. Lasso regression did feature selection and ended up giving up worse results than ridge which again reflects the fact that each feature is important (as previously discussed).
10. The accuracy for each model is more than 90%.
```

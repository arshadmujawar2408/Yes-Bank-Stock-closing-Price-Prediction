# ML for Yes Bank Stock closing price priction

**Programming Language** : Python

**Libraries used** : Pandas, Numpy, Matplotlib, Seaborn

**Notebook** : Google Colab

**Dataset Source** : Provided by Almabetter themself.

## Dataset 
We are given a dataset. It contains the following features.
```
- Date: It denotes date of investment done (in our case we have month and year).
* **Open:** Open means the price at which a stock started trading when the opening bell rang.
* **High:**  High refer to the maximum prices in a given time period.
* **Low:**  Low refer to the minimum prices in a given time period.
* **Close:** Close refers to the price of an individual stock when the stock exchange closed for the day.
```

- Total number of rows in data: 119390
- Total number of columns: 32

## Data Cleaning and Manipulation

### (1) Handling null values
Null values in columns `company` and `agent` were dropped.

### (2) Removing Duplicate rows
All duplicate rows were dropped.

### (3) Identify Continuous and Categorical Variables
The dataset consists of 12 continuous variables and 18 categorical variables. 

### (3) Converting columns to appropriate naming conventionsdata types

## Data Preparation
#

 1) Combine the categories of children and babies into a single category called "kids."
 2) Calculate the total number of bookings by adding the counts of kids and adults.
 3) Convert the data types of the following columns to string: ArrivingYear, ArrivingMonth, ArrivingDate, Canceled, and RepeatGuest.
 4) Convert the arrival date column to the datetime data type for accurate date and time calculations and analysis.


## Exploratory Data Analysis

Performed EDA and tried answering the following questions:

```
 Q1) Which hotel has more no of bookings and What is the  percentage of bookings in each hotel ?
 Q2) Hotel Wise Bookings based on Month and year also What is the trend of bookings within a month ?
 Q3) Which meal type is the  most preffered meal of customers ?
 Q4) Which room type is in most demand and which room type generates the  highest average daily rate?
 Q5) How long do people stay at the hotels?
 Q6) What is preferred stay length in each hotel based on weekday nights and weekend nights ?
 Q7) Which Booking is preffered with the deposite type?
 Q8) Cancellation rates in both the hotels also arival year and  lead time?
 Q9) What is the Average daily rate month wise also which are the most busy months??
 Q10) What is the Average daily rate with respect to per person?
 Q11) Which types of customers mostly make bookings?
```

Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:
   - Bar Plot.
   - Count Plot
   - Pie Chart.
   - Line Plot.
   - Heatmap.
   - Box Plot
             
## Analysis:

Performed analysis and made following conclusions:
```
1} Cancellations: Approximately 27% of the bookings, amounting to 23,987 bookings, were canceled.
2} Bookings by Country: The majority of bookings, around 31%, were made from Portugal, followed by Great Britain with 12% and France with 10%.
3} Occupancy by Month: August is the busiest month with 12.91% of the bookings, while January is the least occupied month with only 5.33% of the bookings.
4} Booking Channels: Around 59% of the bookings were made through Online Travel Agents (OTAs), approximately 15% through Offline Travel Agents, and less than 13% were direct bookings without involving any other agents.
5} Bookings by Year: In terms of the distribution of bookings over the years, 48% were made in 2016, 36% in 2017, and 15% in 2015, indicating an increasing trend in bookings year by year.
6} Meal Preferences: The most ordered meal option was Bed & Breakfast (BB), accounting for approximately 77.7% of the bookings. This was followed by bookings without any meal package specified (SC), Half Board (HB), Undefined, and Full Board (FB).
7} Customer Type: The majority of customers, around 82%, belonged to the Transient customer type, indicating a higher proportion of individual and short-stay guests.
8} Check-Out and Cancellation Rates: Approximately 72% of the visitors checked out as planned, while 26% of the bookings were canceled.
```
## Conclusion

```
1} Majority of the hotels booked are city hotel. Definitely need to spend the most targeting fund on those hotel.
2} We also realise that the high rate of cancellations can be due high no deposit policies.
3} We should also target months between May to Aug. Those are peak months due to the summer period.
4} Majority of the guests are from Western Europe. We should spend a significant amount of our budget on those area.
5} Given that we do not have repeated guests, we should target our advertisement on guests to increase returning guests.	
6} Bed and Breakfast (BB) is the most preferred meal package, indicating the potential to introduce offers and promotions for other meal packages like Full Board (FB) to increase revenue.
7) The distribution channel TA/TO (Travel Agents/Tour Operators) accounts for 80% of bookings, highlighting the importance of collaborating with these channels for marketing and promotions.
And many more conclusions.
```
## Challenges
```
(1) Lot of null values were present in the dataset.
(2) Data type of some Data was in wrong format.
(3) Lot of duplicate data.
(4) Which visualization techniques to use was a challenge?

                                    Hotel booking system data - Exploratory Data Analysis

Objective:   Acquired is a Hotel-booking data of two hotels - City Hotel and Resort Hotel. do an EDA on the information to gain useful insights and build visualizations for a better understanding. 

Data cleaning and manipulation: 
→ Found more than 100000 null values and filled them with zeros since we needed the other data to make necessary conclusions and dropping them would mean losing on useful data. 
→ About 30000 duplicates values were found and dropped
→ Applying descriptive statistics on numerical and categorical data
→ Detected outliers and replaced them with their mean and max values as per requirements

Exploratory Data Analysis conclusions:
→ Created new features, series and dataframes using groupby, merge, pivot and other functions to understanding the underlying data conclusions
→ used matplotlib, seaborn and plotly to draw visualizations

Conclusions: 
→ Overall, city hotels were found to be having a high number of guests  with 61% of all choosing to book in city hotels. Also average prices of rooms are higher in city hotels, thereby contributing to the majority of revenue. The cancellations were mostly made for city hotels
→ Spatial analysis was used to retrieve where the guests are from which revealed a high majority of guests to be from Portugal, Great Britain, France and Spain.
→ Also both hotels were able to assign 80 to 90 percent of  Guests with their reserved room type
→ Highest number of bookings were made through online TA followed by offline TA and direct bookings. 
→ Room types with highest price generation were determined
→ Most busy months were found to be June till September (summer and autumn) with least busy months as winter months(october to february) 
→ Most guests stayed for an average of 4 to 5 days in both hotels
→ Most preferred meal was BB. 
→ High cancellations were made in city hotels compared to resort hotel and the market segment through which high number of cancellations were made are online TA’s and groups
→ Cancellations (in proportion to bookings ) were also high in the months of April till october.
→ More conclusions and insights were additionally noted in the jupyter notebook


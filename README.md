# EDA-Hotel Booking-project![hotel image](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/461131d1-fd2f-4b14-a28f-583d279b6401)
# Project By :-   Rohit Sonawane 
# Project Summary -
The given dataset is of hotel booking. I explored and analyzed the given dataset and discovered some important factors regarding hotel booking. For this, I first read the given data in my collab notebook and then understand the whole data like what are variables in the given data. After that cleaned the data frame in data wrangling. For that I used some functions like drop(), fillna(), isna()/isnull() functions. Then I added some columns which are required in the analysis and removed some columns which are not required. Using this data frame I explored some variables using visualization charts like pie charts, count plots, barplot, and heatmaps and I can find out some insights which are important factors. From these insights, I can suggest some business objectives to clients.
# Problem Statement  :-
   Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? This hotel booking dataset can help you explore those questions! 
	This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyze the data to discover important factors that  govern the bookings.
# Approach
Here are the key steps for conducting an exploratory data analysis (EDA) for Hotel Booking analysis:

1) Data cleaning: Remove any missing or incomplete data, and ensure that the data is in a format that can be easily analyzed.
2) Data visualization: Use plots and charts to visualize the data and identify trends and patterns. For example, you might create histograms to understand the distribution of customer stay  or scatter plots to identify correlations between different variables.
3) Data summarization: Use statistical techniques to summarize the data and understand the relationships between different variables. For example, you might calculate means, medians, and standard deviations to understand the distribution of customer stay or hotel ADR. Overall, the goal of EDA for Hotel Booking analysis is to understand the factors that contribute to increase ADR and to help customer to Select best hotel to stay by targeting those factors.
# Conclusion :-
1) City hotel is mostly preferred hotel by guests.

![1h](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/30cefca3-0a3d-43ec-8929-a4beaf6e1a67)

2) Agent no. 9 made the most bookings.
![agent](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/e25d9db6-3d25-4b15-a004-97b9875866ce)

3) Percentage of repeated guest is less which is 3.15%.

![guest rep](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/b07a6763-561f-4815-b0b0-7716fecd9b0e)

4) Room type A is mostly preferred room type.
![pref room](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/05453d26-78c7-4944-be3d-3a3e87d6647b)

5) Mostly preferred food type is BB type food.
![pref food](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/69d2c53d-f983-4e7c-b09e-ad880a1884b7)

6) August month has most bookings and after august july has most bookings.
![booking by month](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/ecd5914b-72fb-49cd-874f-e38a62748fbe)

7) TA/TO distribution channel is mostly used and percentage is 82.00 %.
![channel](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/c38e10c7-864e-42b6-b9c7-e862ca2c03f2)

8) City hotel has highest ADR. Highest ADR means more revenue.
![avg adr](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/8368173b-7aeb-49ad-be07-546670e6d8d1)

9) 2016 year had highest bookings and bookings were 56622.
![book by year](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/b31a9362-1d01-4d2c-96db-728fde60686f)

10) City hotel has higher waiting time means city hotel is busier hotel.
![waiting time](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/a012653d-1d90-4b72-bc3f-462aad9b5953)

11) GDS distribution channel contributed most in ADR in city hotel but no contribution in resoert hotel.
![dis adr](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/c8e7e90b-37b4-4c05-84c1-6b48c8719225)

12) Optimal stay length in both hotel type is less than 7 days.
![opt stay](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/b6e05729-7f89-4ecd-8617-615ffc4051f5)

13) Repeated guests do not cancel their bookings but not repeated guests cancel.
![book not canc](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/f4a3f4e3-97a1-446b-a60e-5b72fd5cf0fc)

14) If number of people is more then ADR is also increases means revenue increases.
![ADR vs Total](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/d02fadcb-a1a4-4252-ab39-9097e3e46aa5)

15) arrival_date_year and arrival_date_week_number columns has negative correlation which is -0.54.
![Correla hotel](https://github.com/rohit-sonawane9/EDA-capstone-project/assets/119409524/fbc2a664-392f-4f61-985c-5db35d0a1bb5)

16) stays_in_week_nights and total_stays has positive correlation which is 0.94.

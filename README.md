# Objective

It is very important for a company to always analyze its business performance. On this occasion, we will delve deeper into business in the hospitality sector. Our focus is to find out how our customers behave in making hotel reservations, and its relationship to the rate of cancellation of hotel reservations. We will present the results of the insights we find in the form of data visualization to make it easier to understand and more persuasive.

# Data Information

Data description can be found [here](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

# Programming Language
Python

## Data Exploration and Data Cleaning
1. Data Exploration:  
   At this stage, exploration of the data is carried out with the aim of finding out the suitability of the data type and 
whether there are any suspicious values ​in the data.  
2. Data Cleaning:  
   After obtaining information through data exploration, a data cleaning process is carried out which includes
handling missing values ​and handling inappropriate values.

## Exploratory Data Analysis  

### Hotel type  
![hotel type](https://github.com/nishrinarawi/hotel_investigation/blob/88eda88d9634e54dad5836c88b4c7cfcd95dd482/assets/hotel%20type.png)
> City hotels are booked more often than resort hotels. 66.55% of the booking history consists of city hotel bookings, while the rest are resort hotel bookings.

### Hotel Cancellation
![cancellation](https://github.com/nishrinarawi/hotel_investigation/blob/55c1ebf5e7ef59b618e1e4794365a7bccffd4802/assets/cancel.png)  
> From the entire hotel booking history, it is known that 37.26% of the bookings were canceled by customers.

### Repeated Customer
![repeated](https://github.com/nishrinarawi/hotel_investigation/blob/55c1ebf5e7ef59b618e1e4794365a7bccffd4802/assets/repeat.png)  
> Only 2.95% of bookings are made by repeat customers

### Deposit Type
![deposit](https://github.com/nishrinarawi/hotel_investigation/blob/55c1ebf5e7ef59b618e1e4794365a7bccffd4802/assets/deposit.png)
> 87.56% of bookings are made without a deposit. To lower the cancellation rate, management could implement a deposit policy.

### Monthly Hotel Booking Analysis Based on Hotel Type
![booking](https://github.com/nishrinarawi/hotel_investigation/blob/55c1ebf5e7ef59b618e1e4794365a7bccffd4802/assets/monthly.png)
> The patterns in average monthly bookings for City Hotels and Resort Hotels are similar, both experiencing fluctuations from month to month. However, the average monthly bookings for City Hotels are consistently higher than those for Resort Hotels, due to the greater volume of bookings at City Hotels. Notably, there are increases during the holiday seasons in Indonesia, particularly from May to July and at the end of the year. The peak in average hotel bookings occurs in July.

### Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rates
![stay duration](https://github.com/nishrinarawi/hotel_investigation/blob/55c1ebf5e7ef59b618e1e4794365a7bccffd4802/assets/cancelation.png)
> The cancellation rates of resort hotels fluctuate based on stay duration categories, whereas for city hotels, the cancellation rate increases linearly with stay duration. The longer the stay duration at booking, the higher the cancellation rate of those reservations. For stays longer than 25 days, the cancellation rate reaches 93.5%.

### Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate
![lead time](https://github.com/nishrinarawi/hotel_investigation/blob/55c1ebf5e7ef59b618e1e4794365a7bccffd4802/assets/lead%20time.png)
> Both city hotel and resort hotel cancellation rates are more likely to increase as the time between booking and  the hotel check-in date lengthens (lead time)

## Business Recommendation
- Offering discount vouchers to customers who have booked and stayed at the hotel multiple times is a strategy to encourage repeat bookings.
- Implementing a deposit policy can help reduce the cancellation rate. When customers are required to pay a deposit, they are more likely to commit to their bookings, as they have a financial stake in the reservation. This reduces the likelihood of cancellations and helps ensure more stable occupancy rates.
- Implement dynamic pricing and flexible cancellation policies to manage fluctuations in bookings, especially  during peak holiday seasons. For City Hotels, consider offering discounts or incentives for longer stays to mitigate the higher cancellation rates associated with extended bookings.
- Customers with a good booking history may be less likely to cancel their reservations compared to first-time or infrequent guests. By prioritizing these customers, hotels can potentially reduce the risk of cancellations during high-demand periods, ensuring more stable occupancy rates. 

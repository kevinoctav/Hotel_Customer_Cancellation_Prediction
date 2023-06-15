# Hotel_Customer_Cancellation_Prediction
Analysis Using Machine Learning For Hotel Customer Cancellation

Background :
Hotels play a significant role in supporting the tourism industry. A hotel is defined as a place that provides accommodation, food and beverages, and other services for temporary rental to individuals and guests. However, with the advancement of time, hotels have evolved beyond just accommodation and now serve as venues for business meetings, seminars, weddings, and other events. Hotel reservations can now be made through various channels such as websites, applications, email, WhatsApp, and telephone. This makes it easier for travelers who are located far away to contact the hotel and make reservations easily.

In this dataset, the hotels are located in Portugal. The median price per night for hotels in Portugal is $85. The occupancy rate of the hotels is unknown, so it is assumed that the occupancy rate of hotels in Portugal is 49%. The customers in this dataset come from various countries, as there are bookings from 162 different countries. It is not known during which period the data in this dataset was collected. Customers can book hotel rooms either offline (by visiting the hotel) or online (via applications/websites/telephone). The hotel wants to identify customers who truly intend to stay as it can help maximize revenue. The dataset includes customer data such as country of origin, market segment, number of previous cancellations, number of changes made to the reservation, type of deposit, waiting time, type of reserved room, required parking spaces, and special requests.

Target:
0: The customer stayed or had a night(s) stay at the hotel (not canceled)
1: The booking was canceled.

Problem :
Customers who cancel hotel room reservations will result in vacancies in the rooms that were supposed to be occupied by them. Sudden cancellations cause losses for the hotel as the canceled hotel rooms may not have enough time to be remarketed. In this dataset, the timing of when customers cancel their hotel room reservations is unknown, so it is assumed that customers cancel their reservations on the same day as the booked date. The hotel does not have much time to remarket the rooms and has already incurred costs in preparing the hotel rooms. As a result, the hotel does not generate revenue from customers who cancel their hotel room reservations. The hotel needs to lower the room rates in the last moments in order to sell those rooms. This results in reducing the profits obtained by the hotel. It is assumed that the hotel requires confirmation from customers one week before the reservation date, and if customers do not respond, the hotel will market and sell the rooms. The rooms will be sold at discounted prices to attract customers for overnight stays, and the hotel will not incur revenue losses.

Based on the available customer data, the hotel wants to determine the influence of the available variables on the decision of customers to cancel hotel room reservations. This is intended to enable the hotel to predict which customers are likely to cancel their room reservations. The hotel wants to identify the variables or factors that can affect whether a customer cancels a hotel room reservation or not, so that the hotel can make better plans regarding customers who genuinely intend to stay and contingency plans for customers who want to cancel their hotel room reservations. Therefore, the hotel employs a data scientist to predict which customers are likely to cancel their reservations in order to maximize revenue by identifying customers who are likely to cancel their reservations. The hotel aims to create a machine learning model using appropriate algorithms to accurately predict customer cancellations and provide recommendations based on the model's results. By creating a machine learning model, it is expected to automate the prediction of customers who will cancel their reservations.

This analysis is directed towards the hotel's marketing team to remarket the predicted canceled room reservations. With a confirmation deadline of 7 days before the stay date, the marketing team can remarket those rooms and prepare marketing strategies. It is also directed towards the manager responsible for hotel room reservations to consider necessary actions for customers who are predicted to cancel their reservations.

Metrics :
True Positive: Customers who are predicted to cancel hotel room reservations and actually do cancel their reservations.

True Negative: Customers who are predicted not to cancel hotel room reservations and actually do not cancel their reservations.

False Positive / Type 1 Error: Customers who are predicted to cancel hotel room reservations but actually do not cancel their reservations.
Loss for the company:

There is a possibility of overbooking. Based on the dataset, the exact occupancy rate of hotel rooms is unknown, so it is assumed to be 49% based on the data from Portugal.
False Negative / Type 2 Error: Customers who are predicted not to cancel hotel room reservations but actually do cancel their reservations.
Loss for the company:

The hotel incurs losses because the reserved rooms have been prepared but the customers cancel their reservations. The company should have been able to sell those rooms to other customers. The company suffers a loss of rental revenue that should have been obtained.






Using F2 Score

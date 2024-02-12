# PHASE 5 CAPSTONE PROJECT
## Predictive Modeling for Flight Passenger Preferences and   Booking Patterns in Horizon Airlines
### Group Members
Kamande Karigi

Lewis Otsieka

Marion Jelimo

Titus Kilonzo Mutuku

Yusra Noor

## BUSINESS UNDERSTANDING
## INTRODUCTION

Horizon Airlines, a prominent player in the aviation industry, stands as a cornerstone of reliable air travel services. As a leading airline company, Horizon Airlines is dedicated to providing safe, efficient, and seamless travel experiences for passengers across Kenya. With a fleet of modern aircraft and a commitment to operational excellence, Horizon Airlines has positioned itself as a trailblazer in the aviation sector. Recognizing the challenges and complexities inherent in managing a vast network of flights, passenger preferences, and operational logistics, Horizon Airlines has enlisted our expertise. Our team has been entrusted with the task of implementing advanced analytics to derive valuable insights from the company's extensive datasets. By harnessing the power of data-driven decision-making, our goal is to assist Horizon Airlines in optimizing its operations, enhancing customer experiences, and maintaining a competitive edge in the dynamic aviation landscape.


## PROBLEM STATEMENT

In the aftermath of the COVID-19 pandemic, the aviation industry is grappling with a multifaceted challenge to revitalize its operations and regain passenger trust. The problem revolves around understanding the intricate dynamics of customer behavior post-COVID, with a focus on influencing factors such as travel preferences, safety concerns, and the demand for additional services. It is crucial for airlines to tailor their services effectively with respect to the specific needs and concerns of passengers, utilising available data to inform effective safety measures, extra baggage, preferred seating, in-flight meals and other passenger preferences. This project provides an opportunity to investigate post-pandemic travel, and guide Horizon airlines to craft strategies that align with evolving customer expectations and foster a robust recovery.


## THE MAIN OBJECTIVES
To develop a model that learns over the available customer booking data, whose inferences improve or smooth out Horizon airlines' services.


## THE SPECIFIC OBJECTIVES
1. To improve booking conversion rates.

2. To enhance customer segmentation by identifying distinct customer segments based on booking patterns and use the information to tailor marketing strategies, services or offers to specific groups.

3. To increase ancilliary service adoption and optimize marketing or pricing strategies for these services.

4. Optimize Operational Efficiency using patterns related to flight_day and flight_hour to optimize flight schedules, staffing, and other operational aspects.

5. Improve route specific strategies.

These objectives can be interconnected, and addressing one may positively impact others.

## RESEARCH QUESTIONS
1. Booking conversion analysis: What are the primary factors inluencing booking completion and how do the vary across different sales channels? Can the purchase_lead time be optimized to improve booking conversion rates without adversely affecting other aspects?

The most important factor with a predictive model is the quality of the data you use to train the machine learning algorithms. For this task, you must manipulate and prepare the provided customer booking data so that you can build a high-quality predictive model.


With your predictive model, it is important to interpret the results in order to understand how “predictive” the data really was and whether we can feasibly use it to predict the target outcome. Therefore, you should evaluate the model's performance and output how each variable contributes to the predictive model's power.



2. Flight duration: Which features are most significant in trying to predict flight duration? How do aspects such as num of passengers and length of stay relate to flight duration?

3. Customer segmentation: What are the distinct customer segments based on booking patterns, and how do these segments differ in terms of preferences and behaviors? How can personalized marketing strategies be developed for each identified segment?

4. Ancillary Service Adoption: What factors drive customers to opt for extra baggage, preferred seats, or in-flight meals, and are there cross-correlations between these preferences? Can targeted promotions or bundling strategies be implemented to increase the adoption of these services?

5. Operational Efficiency Optimization: How do flight_day and flight_hour affect booking patterns, and how can flight schedules be optimized to match demand? Are there specific routes (route) that exhibit distinct patterns in terms of demand and booking behavior?

6. Route-specific Strategies: How do customer preferences and behaviors vary across different flight routes, and what marketing or pricing strategies can be implemented for each route? Are there external factors, such as events or seasons, that significantly impact booking patterns on specific routes?

## DEFINING METRICS OF SUCCESS
1. Booking Conversion Rates: Metric: Percentage of completed bookings (booking_complete). Success Criteria: Increase in overall booking conversion rates, with a target improvement percentage.


2. Flight Duration Prediction: Metric: Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE) in predicting flight_duration. Success Criteria: Decrease in prediction error, indicating more accurate flight duration predictions.


3. Customer Segmentation: Metric: Silhouette Score or Homogeneity Score for clustering quality. Success Criteria: Improved cluster separation and cohesion, indicating well-defined customer segments.


4. Ancillary Service Adoption: Metric: Percentage of customers opting for extra baggage, preferred seats, or in-flight meals. Success Criteria: Increase in adoption rates for targeted ancillary services.


5. Operational Efficiency Optimization: Metric: Percentage of flights scheduled during peak demand days. Success Criteria: Optimization of flight schedules with an increase in the proportion of flights scheduled during peak demand times.


6. Route-specific Strategies: Metric: Percentage increase in bookings for specific routes. Success Criteria: Successful implementation of targeted marketing or pricing strategies leading to increased bookings on selected routes.


7. Customer Experience Enhancement: Metric: Customer Satisfaction Score (CSAT) based on post-travel surveys. Success Criteria: Increase in overall CSAT scores, indicating enhanced customer experience.


Each metric aligns with the specific objectives and is measurable over time. Feedback will be used to adjust strategies or models as needed to continuously improve performance.


## DATA UNDERSTANDING

The dataset consists of 50,000 entries and comprises 15 columns. It includes both numerical and categorical features, providing insights into flight passenger preferences and booking patterns. Below is an overview of the dataset columns:


num_passengers - Represents the number of passengers for each booking.


sales_channel - Denotes the specific channel through which flight bookings were made.


trip_type - Indicates the type of trip, distinguishing between one-way and round-trip bookings.


purchase_lead - Represents the lead time (in days) between considering and making a flight purchase.


length_of_stay - Captures the duration of the stay associated with each flight booking.


flight_hour - Specifies the hour of the day at which the flight is scheduled.


flight_day - Records the date of the flight booking.


route - Describes the specific route of the flight.


booking_origin - Indicates the origin of the booking, providing insight into the geographic source.


wants_extra_baggage - Binary variable indicating whether passengers express a desire for additional baggage.


wants_preferred_seat - Binary variable indicating whether passengers express a preference for specific seating.


wants_in_flight_meals - Binary variable indicating whether passengers express a desire for in-flight meals.


flight_duration - Captures the total duration of the flight for each booking.


booking_complete - Binary variable indicating whether the flight booking process is completed.

## Exploratory Data Analysis
## Modelling
## Recommendation
## Conclusion 
## Future Steps

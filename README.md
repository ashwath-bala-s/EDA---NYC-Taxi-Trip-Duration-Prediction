# EDA - NYC Taxi Trip Duration Prediction

**Introduction:**

Exploratory Data Analysis (EDA) is a crucial step in understanding and gaining insights from any dataset. It involves summarizing the main characteristics, often using visual methods. This project focuses on performing EDA on the NYC-trip duration dataset, which contains detailed information about taxi trips in New York City. By analyzing this dataset, we aim to uncover patterns and insights that can help understand the factors influencing trip durations.

**Problem Statement:**

The objective of this project is to perform Exploratory Data Analysis (EDA) on the NYC-trip duration dataset to uncover patterns, trends, and insights. By analyzing features such as trip duration, pickup and dropoff times and locations, passenger count, and vendor information, we aim to understand the factors influencing trip durations and identify any interesting patterns within the data. 

**Dataset:**
The dataset used for this project has records and includes the following variables:

•	id: A unique identifier for each trip

•	vendor_id: A code indicating the provider associated with the trip record

•	pickup_datetime: Date and time when the meter was engaged

•	dropoff_datetime: Date and time when the meter was disengaged

•	passenger_count: The number of passengers in the vehicle (driver entered value)

•	pickup_longitude: The longitude where the meter was engaged

•	pickup_latitude: The latitude where the meter was engaged

•	dropoff_longitude: The longitude where the meter was disengaged

•	dropoff_latitude: The latitude where the meter was disengaged

•	store_and_fwd_flag: Indicates whether the trip record was held in vehicle memory before sending to the vendor due to lack of connection to the server (Y=store and forward; N=not a store and forward trip)

•	trip_duration: Duration of the trip in seconds (target variable)

The aim is to perform EDA on this dataset to identify trends, anomalies, and relationships among the variables, ultimately providing insights into factors affecting trip

**Project Description:**

•	Analyzed the NYC Taxi-Trip duration dataset to perform analysis and influence over the target variable.

•	Conducted Univariate and Bivariate Analysis, exploring all possible combinations of features, and presented findings through insightful visualizations. 

•	The analysis provided valuable conclusions and actionable recommendations for the dataset, enhancing my data analysis and visualization skills.

**Observation:**

(i)  The majority of rides follow a rather smooth distribution that looks almost log-normal with a peak just around exp(6.5) i.e. about 17 minutes.

(ii) There are several suspiciously short rides with less than 10 seconds duration.

(iii) There are a few huge outliers near 12.

(iv) Most of the trips involve only 1 passenger. There are trips with 7-9 passengers but they are very low in number.

(v) Vendor 2 has more number of trips as compared to vendor 1

(vi) Number of pickups for weekends is much lower than week days with a peak on Thursday (4). Note that here weekday is a decimal number, where 0 is Sunday and 6 is Saturday.

(vii) Number of pickups as expected is highest in late evenings. However, it is much lower during the morning peak hours.

(viii) We see that most trips are concentrated between these lat long only with a few significant clusters. These clusters are represented by the numerous peaks in the lattitude and longitude histograms

(ix) Trip durations are definitely shorter for late night and early morning hours that can be attributed to low traffic density.

(x) Median trip duration does not vary much as can be seen from the above plot for different vendors.

(xi) From the boxplot we can conclude that there not much of a difference in distribution for the most frequently occuring passenger count values - 1, 2, 3.

(xii) Another key observation is that the number of outliers are reduced for higher passenger counts but that only comes down to the individual frequencies of each passenger count.

(xiii) From the correlation heatmap we can conclude that the lattitude and longitude features have higher correlation with the target as compared to the other features.


**Skills:** Exploratory Data Analysis

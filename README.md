# TPS-Crime-data
* Analyze the crime data from Toronto police service to help provide recommendations on how to better allocate their resources and reduce the overall crime rate.

* This project aimed to analyze the features that impact the level of crime in Toronto to help provide TPS recommendations on how to better allocate their resources 
and ultimately reduce the overall crime rate. I built predictive models based on historical data to forecast crime hotspots (both locations and divisions), 
the number of crimes, and periods of elevated criminal activity. 
## EDA
* Added 18 new features to the crime dataset, enhancing the predictive modeling process and potentially capturing more relevant patterns and insights

* Looked at the distributions of the data and the value counts for the various categorical variables.

![download](https://github.com/GraceLiruohan/TPS-Crime-data/assets/139920767/da213736-24be-49f3-b1c0-96b01c7d4528)

![download (1)](https://github.com/GraceLiruohan/TPS-Crime-data/assets/139920767/f277717c-563f-4e32-9e17-3b30ebfcfd5c)

## Model Building
* Linear Regression – Predict the number of Crimes per Division by year

* Ordinal & Logistic – Amount of crime prediction

K-Means clustering - Police division performance evaluation
## Key Observation and Conclusion
* Crime occurs most frequently at midnight and one o clock, typically on Fridays and continuing into Saturdays. We can assign an increased number of police officers as a minimum requirement in the model

* K-means Clustering identified that division 55 has the highest average expenditure and average crime rate by square kilometres as well as crime per capita. We can determine the resources needed for this division from our Linear Regression model

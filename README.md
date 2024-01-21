Classifying the severity of accidents based on their impact on the traffic
- This Machine Learning Project aims to classify the severity of the impact on traffic made by accidents in the US.
- The number of records in the dataset is huge. Hence instead of using the tradiditonal Pandas dataframe I have used a Dask Dataframe for all operations.
- I have used a CatBoostClassifer to train the model and achieved a test accuracy of 85%

Some of the key findings from the dataset are:
- Traffic signals and crossings have the highest impact on the Severity of an accident
- The city of Miami, county of Los Angeles, state of California have faced the highest number of accidents
- The highest number of accidents have happened in the Easter timezone
- Majority of the accidents have happened during the daytime
- Majority of the accidents have happened when the wind was calm and the weather condition was fair
- Majority of the accidents have affected the traffic with a severity of degree 2
- The average distance of traffic affected by the accidents is 0.56 miles
- 25% of the accidents have not had any impact on the traffic in terms of distance
- 25% of the accidents have affected the traffic for over a mile in terms of distance


Another interesting data is that a particular accident has caused traffic for a whopping 441.75 miles!

This Machine Learning Project aims to classify the severity of the impact road accidents make on traffic in the US.
The number of records in the dataset is huge. Hence instead of using the tradiditonal Pandas dataframe I have used a Dask Dataframe for all operations.
I have used a CatBoostClassifer to train the model and achieved a test accuracy of 85%
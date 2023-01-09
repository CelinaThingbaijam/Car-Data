It is a classification data in which we try to predict car ownership depending upon  Car_Name,year,Selling_Price,Present_price,Kms_Driven,Fuel_Type,Transmission

 - we EDA (Exploratory data analysis)
   - Check null value
   - data types
   - finding correlation
   - cross checking the data 
   - crosstab of Car_Name with Owner and visualising it
   - crosstab of Car_Name and year with average of Present_Price
   - crosstab of Selling_Price and Present_Price with average of Selling_Price
   - crosstab of Transmission with Owner
   - crosstab of kms_driven with Fuel_Type
   - Explaining and Visualising the data of Kms_driven,Present_price and selling with the helps of bins for better understanding
 - Doing label encoding 
 - Splitting the data using train_test_split method and applying *LogisticRegresssion*( accuracy = 97)
 - Using Stratified kfold with n_splits(n=5) and applying *LogisticRegression* ( 95,96.6,96.6,96.6,9.6)
 - Visualising it using *roc_aoc_curve*
 - comparing the data with all the algorithms( not better than LogisticRegression)
 - comparing with all the *ensembles technique*
 - The best one is turn to be *LogisticRegression* with an accuracy of 96.5

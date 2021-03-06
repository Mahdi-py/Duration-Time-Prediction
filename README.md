# Duration Time Prediction
Three models are trained using a real-world data for rail transportation. The data set contains different transportation types (rail, buses etc..) for more than 25 cities. We are working in a single city (Berlin) and specific type of transportation which is rail. The original data set contains more than 6 million records, but we reduced it to half a million. 
link of data set from the nature journal: https://www.nature.com/articles/sdata201889
 ## The data preperation
In this file, the data is integrated and prepared. The missing and redundant data are dealt with. Also, added some disruptions to the trips that might be caused by some reasons like Fire, Brake, etc... The disruptions are added to make the model more realistic in the production because the trips may have some unexpected situations in which the trip is delayed.
 ## Modeling 
In this file, three models are constructed and trained. We did feature selection and feature engineering to reduce the number of features and get rid of the redundant features that does not contribute to the overall performance of the model.
  ### Algorithms 
  * Random Forest
  * Gradient  Boosting Machines
  * Supporting Vector Regressor
 
 ## Technologies 
 * Fastai
 *	Scikit-Learn
 * Python 
 *	Pandas
 * NumPy
 * SciPy

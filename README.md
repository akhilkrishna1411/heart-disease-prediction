# heart-disease-prediction

#importing the data set


#Exploratory Data Analysis


#plot target values


#We have 165 people with heart disease and 138 people without heart disease, so our problem is balanced.
# Checking for missing values
#observations from plot
#cp {Chest pain}: People with cp 1, 2, 3 are more likely to have heart disease than people with cp 0.
#restecg {resting EKG results}: People with a value of 1 (reporting an abnormal heart rhythm, which can range from mild symptoms to severe problems) are more likely to have heart disease.
#exang {exercise-induced angina}: people with a value of 0 (No ==> angina induced by exercise) have more heart disease than people with a value of 1 (Yes ==> angina induced by exercise)
#slope {the slope of the ST segment of peak exercise}: People with a slope value of 2 (Downslopins: signs of an unhealthy heart) are more likely to have heart disease than people with a slope value of 2 slope is 0 (Upsloping: best heart rate with exercise) or 1 (Flatsloping: minimal change (typical healthy heart)).
#ca {number of major vessels (0-3) stained by fluoroscopy}: the more blood movement the better, so people with ca equal to 0 are more likely to have heart disease.
#thal {thalium stress result}: People with a thal value of 2 (defect corrected: once was a defect but ok now) are more likely to have heart disease.

#Correlation Matrix
#Data Processing
#Applying Logistic Regression
#split the data into 70% training and 30% testing:
#train the machine learning model and print the classification report of our logistic regression model:

#Model	             Training Accuracy %	    Testing Accuracy %


#Logistic Regression	          86.79	                     86.81

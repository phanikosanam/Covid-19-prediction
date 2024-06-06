# Covid-19-prediction
COVID-19 Prediction Using SVM model 
Support Vector Machine (SVM), is a supervised machine learning algorithm used for classification and regression tasks. The primary goal of an SVM model is to find the best hyperplane that separates data points of different classes in a high-dimensional space.
Step 1: Data Collection 
First, we collect data that includes various symptoms experienced by the patients.
Step 2: Data Preprocessing 
We process the data to handle any missing values. To normalize the features if necessary, and split it into training and tests sets.
Step 3: Training the SVM Model:
1.	Choosing a kernel:
We can use linear kernel; polynomial kernel could be used depending upon the data complexity.

2.	Finding the optimal Hyperplane:
SVM algorithm works to find the hyperplane the best separates the data points of different classes, while maximising the margin between the closet points of each class (support vectors).

3.	Support vectors: 
There are critical data points, that lie closest to the hyperplane and are used to define the margin. 

Step 4: Making Predictions:
After training, we use the SVM model to predict the COVID-19 status of new patients based on their symptoms.

Step 5: Evaluation: 
This model’s accuracy is calculated based on the predictions.

Confusion Matrix: Used for classification tasks, it helps to visualize the performance of a classification algorithm.
Mean Absolute Error (MAE): Used for regression tasks, it measures the average magnitude of errors in predictions, without considering their direction.
Root Mean Square Error (RMSE): Also used for regression tasks, it measures the average magnitude of errors but gives more weight to larger errors.

![Screenshot 2024-06-05 205815](https://github.com/phanikosanam/Covid-19-prediction/assets/170285019/114bf41d-562f-4fcb-9e36-31db52ddb74e)


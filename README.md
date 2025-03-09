# neural-network-challenge-1
Module 18 Challenge
**Prepared the Data**
Read in the CSV file
Create the X features and the y target = credit_ranking.
Split the features and targets into training and testing datasets.
Use StandardScaler to scale the features.
**Create, Compile and Evaluate a Neural Network Model**
Create the model and use the features as inputs, add 2 hidden layers with 8 neurons for the first layer and 5 or the second layer.
Define the output neurons equal to 1.
Compile and fit the model using binary_crossentropy loss function, the adam optimizer and the evaluation metric = accuracy.
Evaluate the model using the test data and show the model's loss and accurancy
Save and export the model.
Reload the saved model and make predictions on the testing data.
Save the predictions to a new dataframe rounding the predictions to binary values.
Generate a classification report.
Lastly discuss what recommendation to the system you would add for the student loans, describe which filtering was chose and why, and describe 2 real-world challenges.
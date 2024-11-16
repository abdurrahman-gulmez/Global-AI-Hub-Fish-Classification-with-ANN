# ABOUT THE PROJECT
## PURPOSE
- Forecasting the types of the fishes in the photos that included 9 types of the fishes
  
## NECESSARY LİBRARIES
- pandas (data manipulation, data preprocessing)
- matplotlib (visualization)
- seaborn (visualization additionaly to matplotlib)
- sklearn (train-test split and success metrics)
- tensorflow (image processing)
- os (reading data from directoy and taking labels and paths of the images in the data)
  
## STAGES OF THE PROJECT
1. Importing the necessary libraries
2. Taking the paths and the labels of the photos that included the types of the fishes and creating a dataframe to concat them
3. Showing some information about the data (e.g. null value) and one photo for each type of the fish
4. Firstly, splitting the data into train and test, then splitting into train, validation and test sets by scaling
5. Creating a Sequential model and adding the 128 neurons input layer, 64 neurons hidden layer and 9 neurons neurons output layer to this model
6. Adding earlystopping into the model before fitting to prevent overfitting
7. Visualizing the loss and accuracy values of the train and test data to see the results of the model
8. Fitting model with the test data to see the actual result
9. Analizing the results by using the metrics such as loss, accuracy, confusion_matrix and classification report
    
## ACCESSING THE PROJECT
- Please [click](https://www.kaggle.com/code/abdurrahmangulmez46/global-ai-hub-fish-classification-with-ann) to access the details and contents of the project

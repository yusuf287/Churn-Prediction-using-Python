# Churn-Prediction-using-Python

# Task
    Explore the datasets and develop a model to predict customer churn over time.

# Solution:
    I have divided the process into 3 parts:
    Step 1. Data Pre-Processing: 
    It contains all the pre-processing and exploration of the data.
    Notebook name: Step_1_Data_PreProcessing.ipynb

    Step 2. Final Dataset Preparation 
    Preparation of the final dataset for model building.
    Notebook name: Step_2_Preparing_Final_Dataset.ipynb

    Step 3. Model Building and Prediction 
      Modeling and Validation has been done in this step.
    Notebook name: Step_3_Modeling_and_Validation.ipynb

# Instructions 
    •	Detailed explanation of the process is given clearly in the notebooks.
    •	All the data paths are relative. Just unzip the folder and run the notebooks in sequence.
    •	All the pickle files are present in the folder in case you don’t want to run notebooks in sequence. 
    •	You can directly run the Step_3_Modeling_and_Validation.ipynb notebook to see the results. Final data set has been saved as pickle object named ‘final.pickle’
    •	Conclusion has been given in 3rd notebook i.e. Step_3_Modeling_and_Validation.ipynb

Following csv files have been attached:
boxes.csv
    •	subscription_id
    •	box_id
    •	delivey_date (when the box was delivered)
    •	started_week (when the subscription first began)
    •	product (the type of box received)
    •	channel (the marketing channel through which the customer was acquired)
pauses.csv
    •	subscription_id
    •	pause_start
    •	pause_end
cancels.csv
    •	subscription_id
    •	event_type (either cancellation or reactivation)
    •	event_date (cancellation effective date)
errors.csv
    •	subscription_id
    •	reported_date (date error was reported)
    •	hellofresh_week_where_error_happened (week box with error was received)
    •	compensation_type
    •	compensation_amount (amount refunded to customer because of error)


Result 
I have achieved 100% accuracy with Random Forest Classifier.



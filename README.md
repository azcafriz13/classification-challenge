# Challenge Module 13
## Spam Detection Models: An ASU AIML Challenge by CA Frisby  

The exercise:  A data set that contains information about emails is analyzed 
to result in two possible classifications: spam or not spam.
Two classifications models are developed to analyze the data set, a Logistic
Regression model and a Ranom Forest model. 

This ASU AI / ML Bootcamp Challenge is divided into five steps, as follows:

* Step 1: Set up the repository.  The repository includes this markdown file,
the main code file "spam_detector", and a .ipynb checkpoints folder.  The data
is read directly 

    from
 [this link:    https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv).    

* Step 2: Split the data into training and testing sets.  
The spam column is the y-column.  The x columns will be the remaining columns.  
Split the data into training and testing datasets using train_test_split.

* Step 3: Scale the Data
The StandardScaler() Module from scikit-learn was
used to scale or normalize the data.  The normalized data was then used to
create a dataframe of the data for further analytics.

* Step 4: Create a Logistic Regression Model
Fit a logistic model with a random_state argument set to "1".  Calculate the
accuracy score of the model. 

* Step 5:  Create a Random Forest Model
Fit a Random Forest Model with the random_state argument set to "1".  Calculate
the accuracy score of the model.  

* Step 6:  Evaluate the Models
Which model performed better?  Which one was predicted to form better.


## Results
The Random Forest model proved slightly better at 96% vs 93%. 

Please note this is a fictional project for classroom training.

## References
Code for this challenge is supported by class activities from Module 13.
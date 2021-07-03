# Neural Network Charity Analysis

### Overview of the analysis
The purpose of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

### Results

- Data Preprocessing
In this model the variables considered target is 'is_successful'. The feature variables are 'application_type', 'affiliation', 'classification', ' use_case', 'organization', 'status', 'income_amt', 'special_considerations' and ' ask_amt'. The variables that were neither targets nor features and should be removed are 'ein' and 'name'.

- Compiling, Training, and Evaluating the Model
The neural networ model had two hidden layers with 80 and 30 neurons respectively. By using this characteristics we got an accuracy of:

<img width="488" alt="image" src="https://user-images.githubusercontent.com/78698456/124359425-da8a5700-dbf2-11eb-9a30-6651b037c486.png">

### Summary
The result of this analysis is to create a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet Soup. The neural network model gave a 73% accuracy in the prediction. 


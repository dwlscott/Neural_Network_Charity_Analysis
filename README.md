# Neural_Network_Charity_Analysis
Module 19 The Rise of Machine Learning 


## Background 

Here we aim to use our knowledge of machine learning and neural networks, using a provided data set to help create a binary classifier that is capable of predicting the success of applicants if they are funded by Alphabet soup. 

## Results: 

## Data processing 

 - The variables that are considered targets for this assignment are the “IS_SUCCESSFUL  columns. 

 - The Variables that are considered to be the features for the model would all them… except the ones that were dropped. For example Application_type, Affiliation, Classification, Use_case, Organization, Status, Income_amt, Special_considerations, Ask_amount, is Successful.

 - Ein and Name are the variables that are neither targets nor features and therefore should be removed from the data set.

## Compiling, Training, and Evaluating the Model

 - The model was made with one input model and two hidden layers as required by the challenge set. Where the first hidden layer had 80 neurons, and the second had 30.

 - No. we were not able to achieve the target model performance. But it was to be expected that it was going to be a little low. 

 - In order to increase the model performance, a few things were done. A SVM or a Support-Vector machine model was chosen at first. However, it was not running, it was just going in a constant loop. Therefore another model had to be tried which was a Random Forest Classifier.  Then I added a few more hidden layers, and changed the epochs 

##Summary 

Overall the goal was to have 75% accuracy. Which was not achieved.The first model gave us an accuracy score of 69% as shown in the image below. 

<img width="684" alt="Screen Shot 2022-08-07 at 18 18 20" src="https://user-images.githubusercontent.com/102453818/183321453-785bab01-e8d8-4492-b8e6-ca919c8bc015.png">

And the tweaked model gave us an even worse score of 53% as shown below.

<img width="676" alt="Screen Shot 2022-08-07 at 19 12 58" src="https://user-images.githubusercontent.com/102453818/183321391-52309cef-988b-4b4f-a854-c4684efba790.png">


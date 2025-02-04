# sprint_7
***
### Modeling
____
A mobile phone company has a decided too many long term customers are still on legacy plans. Our goal is to analyze customer behavior of those utilizing the newer plans available, creating a recommendation model for the legacy customers.

Additional info:<br>
* We have been provided with cleaned data 
* The new plans are smart or ultra
* They need the model to be at least 75% accurate

Once we load the data, it will be split into training, validation, and test sets. Comparing a Logistic Regression model against a Random Forest Classifier model, both out-of-the-box and with hyperparameter tuning by fitting on training data, adjusting on validation data, and grading on the test set.

Data description<br>
Every observation in the dataset contains monthly behavior information about one user. The information given is as follows: <br>
сalls — number of calls<br>
minutes — total call duration in minutes<br>
messages — number of text messages<br>
mb_used — Internet traffic used in MB<br>
is_ultra — plan for the current month (Ultra - 1, Smart - 0)<br>

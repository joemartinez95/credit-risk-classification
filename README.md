An analysis was completed on being able to use a machine learning model in order to predcit whether current loans would have potential to default or if the loan was in a healthy status. 
There was data provided including but not limited to, the total loan size, customer income, customer debt to income ratio, and customer total debt.
After determining that the ultimate goal prediction we wanted to make was whether a current loan would potentially default, we separated this target metric from the rest of the data. It was identified that of the 77536 current loan status records provided, there were 75036 healthy loans and 2500 loans at risk of defaulting.
Separating the variable feature data, we also separated data by X and Y for training and for testing respectively. Logistic regression was chosen as the machine learning model since the variable we wanted to predict was a binary choice between identifying a healthy loan and a loan at risk of defaulting.


* Machine Learning Model 1:
    * Accuracy of .99
    * Precision:
        - 0 (healthy loan): 1.00
        - 1 (loan at risk of defaulting): 0.85
    * Recall scores
        -0 (healthy loan): 0.99
        -1 (loan at risk of defaulting): 0.91



After conducting the Logistic Regression Machine Learning model to predict healthy loans and loans at risk of defaulting, based on the results we recommend using this model, based on the overall accuracy of .99.
The model has supporting Precision scores especially for predicting healthy loans at 1.00. For loans at risk of defaulting, a precision score .85 helps support that the majority of the time when relevant data is provided, it will be able to determine a loan that is at risk of defaulting.

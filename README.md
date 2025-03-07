# Drug-prediction-with-Decision-Tree-Classifier
Built a ML model to predict the drug that will be given to a patient based on the features such as Age, Blood Pressure, Na_to_K, Cholesterol Level.


![drug chart](https://github.com/user-attachments/assets/ed846a19-5fc0-412a-b06d-88813f0ecea9)


Drug Y and X has the highest prescription given to patients


![Drug Decision Tree](https://github.com/user-attachments/assets/54aadc41-1b4b-44e4-a4c9-e558352108be)

##### Drug Tree interpretation
The decision criterion for; 


**Drug Y** : Na_to_K > 14.627\
**Drug A** : Na_to_k <= 14.627, BP = High, Age < 50.5\
**Drug B** : Na_to_k <= 14.627, BP = High, Age > 50.5\
**Drug C** : Na_to_k <= 14.627, BP = Normal, Cholesterol = High\
**Drug X** : Na_to_k <= 14.627, (BP = Low, Cholesterol = High) or (BP = Normal/Low, Cholesterol = Normal)


This means that\
**Drug Y** is prescribed for patients whose Na_to_K is greater than 14.627\
**Drug A** is prescribed for patients whose Na_to_K is equal or less than 14.627 with High Bloop Pressure and are under the age of 50.5\
**Drug B** is prescribed for patients whose Na_to_K is equal or less than 14.627 with High Bloop Pressure and are over the age of 50.5\
**Drug C** is prescribed for patients whose Na_to_K is equal or less than 14.627 with Normal Bloop Pressure and High Cholesterol\
**Drug X** is prescribed for patients whose Na_to_K is equal or less than 14.627 with Low Bloop Pressure and High Cholesterol  or patients whose Na_to_K is equal or less than 14.627 with Normal or Low Blood Pressor with Normal Cholesterol.


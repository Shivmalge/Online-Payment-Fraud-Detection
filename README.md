# Online-Payment-Fraud-Detection
## This project is about to predict whether the payment done is fraud or not. Depending upon the features in the dataset, I have preidcted the output.
### The libraries used in this model are as follows:
- Numpy
- Pandas
- Matplotlib.pyplot
- Sklearn
### The dataset contains following features depending upon which I have predicted the output.
- Type of Payment
- Amount
- OldBalance
- NewBalance
- oldbalanceDest

### 1. I have imported the required libraries and Read the dataset.

![image](https://user-images.githubusercontent.com/104545490/175632180-c0b4fb79-4f3a-4ee1-a6ea-6db5398e03ec.png)

### 2. Feature Engineering : 
 In this I have checked whether the dataset contains any null values or not , In this case there is no null value. 
    If there is null values then I will replace with mean and median for contious and categorical features respectively.   
    
![image](https://user-images.githubusercontent.com/104545490/175637868-3542bd2c-6bbd-4502-9efb-e2f89fa511f5.png)

### 3. Data Visualization:
 Distributuion of transaction type is showed.
 
 ![image](https://user-images.githubusercontent.com/104545490/175645453-21a61812-3c10-4937-8f27-ab53c876aaa2.png)

 
### 4. Now I have obtained the correlation between the features of the data with the isFraud column.

![image](https://user-images.githubusercontent.com/104545490/175644881-f28759b8-b66e-42cd-82c8-9312dcbb96dd.png)

### 5. Divide the data into training and testing and trained the model using RandomForestClassifier algorithm

![image](https://user-images.githubusercontent.com/104545490/175645059-08a1e876-1320-4a91-88a0-97b914e9fe40.png)

### 6. Now I have classified/predicted whether a transaction is a fraud or not by feeding about a transaction into the model

![image](https://user-images.githubusercontent.com/104545490/175645195-fff8e63a-a00b-405a-892c-bef49e1e61fe.png)

## This is how I have built the Machine Learning Model which predicts the online payment is Fraud or Not.

Project by - Shivsharan Malage

[Github](https://github.com/Shivmalge)

[Linkedin](https://www.linkedin.com/in/shivsharan-malage-99802a230/)







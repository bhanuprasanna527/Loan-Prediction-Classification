
# Loan Prediction Classification

## Problem Statement
Dream Housing Finance company deals in all home loans. They have a presence across all urban, semi-urban, and rural areas. Customer-first applies for a home loan after that company validates the customer eligibility for a loan.

The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling the online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others. To automate this process, they have given a problem to identify the customer's segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.

### Dataset Information
   
Variable | Description
----------|--------------
Loan_ID | Unique Loan ID
Gender | Male/ Female
Married | Applicant married (Y/N)
Dependents | Number of dependents
Education | Applicant Education (Graduate/ Under Graduate)
Self_Employed | Self employed (Y/N)
ApplicantIncome | Applicant income
CoapplicantIncome | Coapplicant income
LoanAmount | Loan amount in thousands
Loan_Amount_Term | Term of loan in months
Credit_History | credit history meets guidelines
Property_Area | Urban/ Semi Urban/ Rural
Loan_Status | Loan approved (Y/N)



## Steps Involved in the Loan Prediction Classification

1. **Import modules**
2. **Loading the dataset**
3. **Preprocessing the dataset**
4. **Exploratory Data Analysis**
5. **Label Encoding**
6. **Train-Test Split**
7. **Model Training**
    * *LogisticRegression*
    * *DecisionTreeClassifier*
    * *RandomForestClassifier*
    * *ExtraTreesClassifier*

## Model Selection

![image](https://user-images.githubusercontent.com/79924017/159662508-eb7eea90-866c-42d8-9d15-e33175746939.png)


## Accuracy

![image](https://user-images.githubusercontent.com/79924017/159662355-ada4f0fc-a337-4528-988f-80768ad10140.png)
![image](https://user-images.githubusercontent.com/79924017/159662340-df448bfe-0911-44d5-9520-2cb8fca1bf75.png)


* Accuracy = ((95+24)/154) * 100 = 77.27%.
* **The Accuracy is 77.27% in test data.**


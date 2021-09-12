# Lending-Club-Loan-Analysis Spark

<b>Analyzing data about loan provided to borrowers by Lending Club Company for different reasons</b>

# Data

<b><br> Data is about loans provided by Lending Club from year 2007 - 2017 with details about loan taken by borrowers. Dataset can be downloaded from  here: https://www.kaggle.com/husainsb/lendingclub-issued-loans </b></br>

# Steps

<b><br>1: Loaded both the datasets and combine them into single dataset </b></br>
<b><br>2: Performed Data Cleaning and analysis in PySpark </b></br>
<b><br>3: Performed Spark Transformations and Actions & Exploratory Data Analysis to find insights and analyze data by plotting graphs and analysis </b></br>
<b><br>4: Exploring major reasons for Loan Taken by borrowers, Yearly Loan taken </br></b>
<br><b>5: Inspecting statewise loans taken and why some loans are taken more in some states</br></b>
<br><b>6: Analyzing by Income category, Home Ownership relation Loan Status </b></br>
<b><br>7: Inspecting terms period for loan taken and finding States with High Percentage of Good Loans and States with High Percenatge Bad Loans by relation with Debt to Income ratio (dti)</br></b>
<b><br>8: Tracking Interest Rate for Loan taken with respect to Loan Status and Installments for different reasons for loan taken with respect to Loan Status </br></b>

# Few SnapShots of the Analysis

<br>![image](https://user-images.githubusercontent.com/55294349/132809537-12416a42-af7f-4c9e-9df8-dae45edb1366.png)</br>
<br><b> Issuance of loans were very low till 2012.From 2013 the loans issuance are high </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132809570-dc444135-21b9-425e-a6a6-b5a152134a97.png)</br>
<br><b> Customers that made part of the high income category took higher loan amounts than people from low and medium income categories. Of course, people with higher annual incomes are more likely to pay loans with a higher amount</br></b>


<br>![image](https://user-images.githubusercontent.com/55294349/132971082-dd5a95f3-3496-4827-b42f-5056f83eab55.png)</br>
<br><b> Loans that were borrowed by the Low income category had a slightly higher change of becoming a bad loan</br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132971099-bdc303dc-e162-4146-84a9-dddbbb63f64b.png)</br>
<br><b>Customers with a lower income had on average higher interest rates while people with a higher annual income had lower interest rates on their loans.</br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132809645-8f812848-f69f-4a81-99c6-a3bebf0e6ab1.png)</br>
<br><b> Grade C has highest total loan amount </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132809669-e7c5b429-a2df-43b3-a0ac-de1bdc049abd.png)</br>
<br><b> Majority of Bad Loans exist from A,B,C and D. Although B and C grade have similar number of Good loans Issued but C grade has more Bad Loans than Grade B </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132809692-6895a4e9-71d3-4432-b338-ea9859969826.png)</br>
<br><b> Most of the loan takers have Home Ownership of Rent or Mortgage. Very Few own a House which request for loan</br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132809720-ac171013-7738-44fc-b2a8-0a1429eb8476.png)</br>
<br><b> 25 % percentile of loan amount issued is 7500 , 50% percentile is 12500 and 75 % percentile is 20K. There are few outliers i.e. Q3 +1.5(Q3-Q1) which gives maximum point in the dataset. But there are few data points which are lying above that </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132809808-3f91bba8-4932-439a-9fb9-979b1fd1656e.png)</br>
<br><b> Loan taken majority of the times are 36 months.7% of the total loans for term 36 months are bad 9.5% of the total loans for term 60 months are bad. So, term of 60 months have high probability of being bad loan </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132809900-e961e96a-35ba-4e9c-b29c-09f657f58b54.png)</br>
<br><b> Majority of Employee are 10+ years who have taken loan </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132809933-e5ffbe54-c00e-49ea-9c5a-b24895ca6c69.png)</br>
<br><b> For Rented Home Ownership good Loan median is 11K while for Bad Loan median it is 12K. For Owned House good loan median is 12K while bad one is 14K. For Mortgage good loan median is 17K while Bad loan median is 18K. So Bad loan median is high than Good loan Amount. People who have Mortgage tend to take loans with higher amount.</br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132809991-4ce6bc19-5871-4de6-9031-fdee9e85e879.png)</br>
<br><b> 6 % of loans taken for credit card are bad. 8.2% of loans taken for debt_consolidation are bad.  7% of loans taken for home improvement are bad. Majority of the loans are taken for debt consolidation </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132810064-7d6d1682-3609-49e0-bf80-bb29480256a6.png)</br>
<br><b> Hawai, Nevada, Alabama and Oklahoma high most Percentage of Bad Loans and reason can be Debt to Income ratio is also very high for these states </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132810114-38a52676-561a-40e0-8a30-c93d6dbf45f7.png)</br>
<br><b> Maine, District of Columbia and Vermont have maximum percentage of good Loans </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132810147-9f6e2367-13e8-4d33-8a81-e3a5ce32a925.png)</br>
<br><b> Generally Installments made for car, Vacation and Eductional are low. Installments made for Credit Card, Small Business, Debt Consolidation, Home Improvement and House are high </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132810179-dc0affe5-9f66-42a1-8602-7dda2f297417.png)</br>
<br><b> Interest rate for Bad Loans are higher than Good loans making it difficult to repay and resulting into Not Repaying </br></b>

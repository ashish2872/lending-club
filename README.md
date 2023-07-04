# lending-club

On the given dataset of the Lending Club Case Study, we have conducted our Exploratory Data Analysis and performed the steps as follows: 
1. Understanding the data - Our first step was to understand what kind of data has been provided to us. 

2. Cleaning the data  - Next we started with removing the NaN values from the dataset and dropped the columns with only 1 unique value in it, we also extracted the month and year from the date columns, removed the ‘%’ sign from interest rate and revolving utilisation colu
mns, converted string number to floating point numbers.

3. Conducting Univariate and Segmented Univariate Analysis- In this particular step we conducted analysis on each and every column we had after removing the columns. We were able to identify a few columns which were important for conducting the analysis or can also said ‘Driver Variables’. We identified those variables and they are as follows : Purpose of the loan, Loan amount, funded amount, funded amount promised by investors, Interest Rates, Term of the loan, Revolving Utilisation of the credit accounts and the Annual Income of the applicant. 

4. Conducting Bivariate Analysis - We conducted the bi-variate analysis on the identified driver variables and found that the ‘funded amount for the loan’ and ‘funded amount promised by investors’ were highly correlated to ‘loan amount’ and the variables ‘revolving utilisation of the credit accounts’ was also positively correlated to the ‘interest rates’ which means the higher the revolving utilisation higher the interest rate.

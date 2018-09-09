# Bankruptcy-prediction
The workbook aims to predict bankruptcy for U.S. Service Companies 1,2,3 years before bankruptcy using machine learning model namely Supported Vector Machine, Decision Tree, K-nearest Neighbor, Random Forest

## Data Source:
* The list of companies went bankrupt was compiled from UCLA-Lopucki Bankruptcy Research Database.
* Then the non-bankrupt companies were chosen based on the same Standard Industrial Classification code (SICs), approximately asset sizes and operating years.
* Then the financial data such as total assets, total liabilities, total equity,... were attracted from Mergent online database.

## Variables:
There are 7 variables used to predict bankruptcy. All the variable are believed to yeild high accuracy rate because there were well researched by many researchers such as Altman (1983), Beaver (1966).
The variables are: X1 = working capital/total assets; X2 = retained earnings/total asssets; X3 = EBIT/total assets; X4 = total equity(book)/total assets; X5 = net income/total assets; X6 = total liabilities/total assets; X7 = cash flow from operation/total liabilities

## Accuracy rate results
### T-1 (1 year before bankruptcy)
* Supported Vetor Machine: 73%
* Decision Tree: 69%
* Random Forest: 88%
* K-nearest neighbor: 77%

### T-2 (2 years before bankruptcy)
* Supported Vetor Machine: 88%
* Decision Tree: 100%
* Random Forest: 92%
* K-nearest neighbor: 81%

### T-3 (3 years before bankruptcy)
* Supported Vetor Machine: 65%
* Decision Tree: 54%
* Random Forest: 65%
* K-nearest neighbor: 50%

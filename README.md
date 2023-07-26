# Collection-Analysis
## 1. Introduction
### Introduction to the dataset
This dataset includes 1 table containing debt collection information of partners by month in 2020 and 2021.
### Data dictionary
![image](https://github.com/gathub-lab/Collection-Analysis/assets/116141004/ff98b8b0-d329-48a4-bb46-ca22c50d11ec)

### Request
Know the debt collection situation in general and each partner's as well as their strengths: Amount of debt collected, success rate of debt collection by month, by year, by product

## 2. Design Thinking Method
**Apply 5 steps of Design Thinking**
### Step 1 - Empathize
![image](https://github.com/gathub-lab/Collection-Analysis/assets/116141004/26b9574a-78c1-404e-b79c-e5ac57ef2159)
### Step 2 - Define
![image](https://github.com/gathub-lab/Collection-Analysis/assets/116141004/18b5ddd0-8197-4e8f-a74d-909881cf1b6c)

### Step 3 - Ideate
![image](https://github.com/gathub-lab/Collection-Analysis/assets/116141004/1e7934c4-9a1f-4142-943a-bf95151c4831)

### Step 4 - Prototype
![image](https://github.com/gathub-lab/Collection-Analysis/assets/116141004/8ba623d4-c131-484e-bca2-52c249994061)

### Step 5 - Review
![image](https://github.com/gathub-lab/Collection-Analysis/assets/116141004/fb3ca4f1-f7f2-47f1-84fe-42382c39f4ae)

## 4. Insight
Overview:
- 44% of debts in group 1080+; 27% belongs to 720 - 1080 debt group and 22% is bad debt
- SP credit card has the highest payout ratio (0.17%) and overdraft (0.10%)
- Secured Loan product has the lowest payment ratio (0.02%) and has the third highest outstanding balance, worth 41T. NDC company ranks TOP 1 in terms of debt recovery for this product, debt recovery rate = 0.03%. In December 2020, this product has the best debt recovery, %payment = 0.06%. In October 2020, NDC company collected many debt payments for this product worth more than 950 million, in December 2020, FBI company obtained many debt payments for this product worth more than 1.1 billion
- Unsecured Loan product has the highest outstanding balance among products (accounting for nearly 50%, worth 136T), the average debt recovery rate is 0.07%, well recovered by GLX, HMK, and ASA
- Debt recovery rates in 2021 of GLX, HNA, DK and AMG companies tend to increase compared to 2020
- FBI company has a fairly low average debt recovery rate = 0.03%, the main product is HHB. In December 2020, the FBI ranked first in bad debt collection, worth more than 1.2 billion

TOP 1 Partner: NDC Company
- 1st in balance 45T billion
- Average debt recovery rate: 0.09%
- From October 2020 (0.15%, up 0.06% compared to September 2020), NDC has had a breakthrough in the ratio of payment to total outstanding loans.
- As a result, from March to May 2021, NDC company ranked first in terms of the amount recovered, nearly 5.5 billion (March 2021).
- Products that this company can collect well are Other (0.32%) and Credit card (0.26%)
- Able to recover bad debts, continuously ranked in TOP in bad debt recovery in October 2020 (nearly 1.3 billion), April 2020 (> 640 million) and 3/2021 (> 370 million)

TOP 2 Partner: ASA Company
- Average debt recovery rate: 0.11%
- ASA has an unstable debt collection rate compared to the same period last year:
+ January and 2: The debt collection rate of 2021 is much lower than 2020, specifically January 2020 = 0.2%, January 2021 = 0.14%; February 2020 = 0.28%, February 2021 = 0.06%
+ March, April, and May: The debt recovery rate of 2021 is higher than that of 2020, specifically, the rate of 2021/2020 of the months of March, April, and May is 0.17%/0.15%, respectively; 0.12%/0.08% ; 0.11%/0.06%
+ The strength of this company is the Overdraft product, with a payment/debt ratio of 0.26%

TOP 3 Partner: GLX Company
- Average debt recovery rate: 0.11%
- GLX has a sharp decrease in debt recovery rate in 2021 compared to 2020
- Strength SP is Overdraft and HHB

## 5. Recommendations
- Allocation of debt portfolio according to the strengths of each company:
+ NDC: Other, Credit Card, Secured Loan
+ ASA: Overdraft, Unsecure Loan
+ GLX: Overdraft, HHB, Unsecured Loan
+ FBI: HHB, Secured Loan
- Implement ranking policy: allocate better portfolio to partners with good recovery rate

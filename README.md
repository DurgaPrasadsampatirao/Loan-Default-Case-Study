# Loan-Default-Case-Study
Managing loan defaults is a critical challenge for lending institutions, impacting stability and profitability. This project explores loan default analysis, examining factors like loan type, purpose, credit score, interest rates, and property values. By understanding these dynamics, we aim to develop effective risk mitigation strategies.


# Data description
 ● IDIdfor each row
 ● yearyear when the loan was taken
 ● loan_limit if the loan limit is fixed or variable cf-confirm/fixed, ncf- not confirm/not fixed
 ● Gendergender of the applicant, can be male female, not specified, joint (in case of applling as a couple for home loan)
 ● loan_type type of loan (masked data ) type-1, type-2, type-3
 ● loan_purpose purpose of the loan (masked data ) p1,p2,p3,p4
 ● business_or_commercial if the loan is for sommercial establishment or personal establishment
 ● loan_amount amount of the loan
 ● rate_of_interest rate of interest for the loan
 ● Upfront_charges down payment done by the applicant
 ● property_value value of the property being constructed for which the loan is taken
 ● occupancy_type for the establishment
 ● incomeincome of the applicant
 ● credit_type 'EXP' 'EQUI' 'CRIF' 'CIB'
 ● Credit_Score credit score of applicant
 ● co-applicant_credit_type credit type for co-applicant
 ● ageageofapplicant
 ● LTVlifetime value of the applicant
 ● Region region of the applicant
 ● Status defaulter(1) or normal(0)

# Recommendations for Each Column

## 1. Loan Limit
**Observation**: Borrowers with “ncf” (non-conforming) loans have a default rate of 33.21%, compared to 24.03% for “cf” (conforming) loans.  
**Recommendation**:  
- Limit the issuance of "ncf" loans or apply stricter underwriting standards for these high-risk loans.  
- Introduce additional eligibility checks for non-conforming loan applicants.  

## 2. Loan Type
**Observation**: Type 2 loans show the highest default rate (34.54%), followed by Type 3 (25.06%) and Type 1 (22.77%).  
**Recommendation**:  
- Conduct enhanced risk assessments for Type 2 loans and consider increasing minimum eligibility criteria.  
- Prioritize offering Type 1 loans, which have the lowest default risk, to maintain a safer portfolio.  

## 3. Loan Purpose
**Observation**: Loans with purposes categorized as “p3” and “p4” have the highest defaults.  
**Recommendation**:  
- Introduce stricter screening for borrowers applying under "p3" and "p4."  
- Provide specialized financial counseling for higher-risk purposes to reduce default tendencies.  

## 4. Business or Commercial Nature
**Observation**: Non-business loans ("nob/c") have a higher default rate compared to business loans.  
**Recommendation**:  
- Focus on promoting secured business loans and enhancing monitoring of non-business loans.  
- Offer lower interest rates or flexible repayment plans for business loans to attract safer borrowers.  

## 5. Loan Amount
**Observation**: Smaller loan amounts are associated with higher default rates.  
**Recommendation**:  
- Set a minimum loan amount threshold to avoid issuing loans with higher risks of default.  
- Perform more comprehensive risk evaluations for small loans to ensure creditworthiness.  

## 6. Rate of Interest
**Observation**: Interest rates above 4% are linked to higher default rates.  
**Recommendation**:  
- Consider offering competitive interest rates to borrowers with strong financial profiles.  
- Use interest rate thresholds to segregate and monitor high-risk borrowers proactively.  

## 7. Upfront Charges
**Observation**: Higher upfront charges are associated with lower default rates.  
**Recommendation**:  
- Increase upfront charges slightly for high-risk borrowers to mitigate default risks.  
- Offer upfront charge discounts for safer borrower profiles to enhance customer loyalty.  

## 8. Property Value
**Observation**: Borrowers with higher property values are less likely to default.  
**Recommendation**:  
- Incentivize secured loans backed by high-value properties to reduce risks.  
- Tighten criteria for loans issued without property collateral.  

## 9. Loan-to-Value (LTV) Ratio
**Observation**: Borrowers with LTV ratios >100% have the highest default rates (64.8%), while those with <50% have the lowest (15.1%).  
**Recommendation**:  
- Introduce strict caps for LTV ratios, especially for high-risk categories above 80%.  
- Promote loans with lower LTV ratios by offering better terms for borrowers with more equity.  

## 10. Debt-to-Income (DTI) Ratio
**Observation**: Higher DTI ratios are correlated with defaults, especially in extreme cases.  
**Recommendation**:  
- Set an upper limit for acceptable DTI ratios to ensure borrowers have manageable debt loads.  
- Implement regular monitoring of borrower DTIs during the loan tenure for early risk detection.  

## 11. Credit Score
**Observation**: Credit score alone does not strongly predict defaults.  
**Recommendation**:  
- Combine credit score with other indicators (e.g., income, loan purpose) to create a comprehensive risk profile.  
- Target financial education initiatives at lower-credit-score borrowers to improve repayment behavior.  

## 12. Region
**Observation**: The North-East region has the highest default rate (30.4%).  
**Recommendation**:  
- Design region-specific risk mitigation strategies, such as additional borrower support in high-risk areas.  
- Partner with local financial advisors to better understand regional repayment behaviors.  

## 13. Age
**Observation**: Borrowers under 25 and over 74 show the highest default rates.  
**Recommendation**:  
- Offer financial literacy programs tailored for younger borrowers.  
- Provide flexible repayment plans or reduced EMI options for older borrowers to alleviate financial pressure.  

## 14. Gender
**Observation**: Joint accounts have the lowest default rate (19.16%), while "Sex Not Available" has the highest (28.59%).  
**Recommendation**:  
- Encourage joint account loans, which exhibit better repayment reliability.  
- Monitor loans for "Sex Not Available" profiles closely, as this category indicates higher risk.  

## 15. Collateral
**Observation**: Loans without collateral have higher default rates.  
**Recommendation**:  
- Promote secured loans by offering better interest rates and terms for loans backed by collateral.  
- Implement stricter approval criteria for unsecured loans.  

## 16. Occupancy Type
**Observation**: Individual residence (ir) loans show the highest default rates (29.99%), while primary residence (pr) loans exhibit the lowest (24.3%).  
**Recommendation**:  
- Focus lending on primary residences to minimize risks.  
- Introduce targeted risk assessment measures for individual residence loans.  

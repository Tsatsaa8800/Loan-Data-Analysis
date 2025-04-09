# Bank Loan Dashboard
## Executive Summary

This dashboard provides a clear overview of a bank’s loan portfolio, highlighting trends in applications, funding, repayments, and defaults. While overall growth is strong—with rising application volume and repayment inflows—default rates are also notable, with 13.8% of loans in default.

Deeper analysis shows that defaults are most common among lower-grade borrowers (E–G), renters, and those earning between $30K–$60K. Traditional indicators like long employment history are not reliable predictors of repayment. Instead, combinations of factors—such as loan purpose, housing status, and income—more accurately signal risk.

These insights support the need for multi-factor risk scoring, tighter approval criteria for high-risk segments, and closer monitoring during seasonal lending spikes.


## Summary Page – Portfolio KPIs

Loan funding and receipts are steadily increasing, indicating continued portfolio growth and strong borrower engagement. At the same time, there is a gradual rise in both interest rates and debt-to-income (DTI) ratios, which may be early signs of financial strain among borrowers. Additionally, with 13.8% of loans currently in default, the portfolio shows moderate risk exposure that warrants ongoing monitoring.

🔗 **Please download the interactive dashboard [here]().**

![Screenshot 2025-04-07 125223](https://github.com/user-attachments/assets/d899ee88-8e03-47f7-a4ce-5a1e7573904a)




---

## Overview Page – Borrower Behavior & Trends

This page reveals key macro-level patterns across borrower segments, helping to explain where default risk is most concentrated. Default rates increase significantly from Grade C onward, with Grade A loans showing a default rate of just 5.7%, compared to 31.3% in Grade G. This confirms that credit grades remain the most reliable predictor of loan performance.

Housing status is also a strong indicator—renters account for around 50% of all defaults, far more than homeowners or mortgage holders. Income levels further narrow the picture: most defaults are clustered among borrowers earning between $30K and $60K annually, a group that may appear stable on paper but is more financially vulnerable in practice. Notably, long employment history does not guarantee repayment reliability; even those with over 10 years of tenure show up in default records.

Seasonal patterns also emerge, with loan applications peaking in Q4, suggesting that year-end financial pressure may influence borrowing behavior and risk.

---

## Details Page – Loan-by-Loan Record View

The Details Page highlights several recurring patterns at the individual loan level. High-interest loans with disproportionately low repayment amounts appear frequently, suggesting a strong link between high pricing and borrower delinquency. Even among loans with identical funding amounts, installment values vary widely, driven by differences in interest rates or loan terms—indicating how repayment burden can differ significantly across borrowers.

Filtering the data also reveals that renters and individuals borrowing for credit card repayment purposes tend to show more frequent repayment issues, reinforcing earlier insights from the borrower segmentation analysis.

---

## Root Cause Analysis – Understanding Default Behavior

This tree diagram reveals how combinations of borrower traits contribute to loan defaults, uncovering patterns that are not always visible in isolation. Defaults are most frequently tied to loans taken for debt consolidation or credit card repayment—both indicators of pre-existing financial stress. These defaults are especially common among renters and borrowers earning less than $60K annually.

Interestingly, many of these borrowers have stable employment histories, which suggests that behavioral or financial management factors outweigh traditional indicators like job tenure. Seasonal effects also play a role, with loans issued in Q4 demonstrating a higher failure rate, likely due to year-end financial strain.

Overall, the analysis reinforces that no single variable explains default risk; instead, it’s the combination of purpose, income, housing status, and timing that paints a clearer risk profile.

---

## Overall Recommendations

- Implement stricter approval criteria for borrowers in lower credit grades (E to G), particularly those with additional high-risk indicators such as high DTI or renter status.
- Enhance credit assessment models by incorporating multi-variable scoring techniques, rather than relying solely on traditional factors like income or employment tenure.
- Introduce early warning systems for loans with high interest rates and disproportionately low repayment progress, using thresholds based on repayment-to-funding ratios.
- Monitor seasonal lending activity—especially in Q4—and consider adjusting underwriting criteria during high-risk periods to account for increased financial pressure on borrowers.
- Use the findings from the Root Cause Analysis to train and refine machine learning models that can flag high-risk borrower profiles prior to loan approval.
- Reassess the weight assigned to employment length during credit evaluation, as data shows it is not a reliable standalone predictor of repayment behavior.
- Consider segment-specific lending strategies for mid-income borrowers ($30K–$60K), such as smaller loan sizes, financial coaching, or structured repayment plans.
- Apply targeted risk controls to loans issued for high-risk purposes like debt consolidation and credit card refinancing, which frequently appear in default clusters.
- Integrate visual risk indicators (e.g., conditional formatting, risk flags) into the loan-level dashboard to support faster decision-making and operational reviews.
- Regularly update and validate scoring models using new borrower data and observed default behavior to ensure risk models remain aligned with real-world outcomes.

---

## 🛠️ Tech Stack

- **Frontend**: Power BI (or Dash, Tableau, React)
- **Data Source**: CSV or SQL-backed datasets
- **Hosting**: Internal server or cloud-hosted dashboard



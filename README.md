# Mental Health Survey Data Analysis (Excel)
 
🔍 Objective:
To explore how various workplace and personal factors influence the likelihood of seeking treatment for mental health issues, using data from a mental health in tech survey.

🧹 Data Cleaning & Preparation:
Cleaned and formatted raw data to ensure consistency across fields.

Standardized values (e.g., unified gender entries, normalized country/state codes).

Converted inappropriate date-type values (e.g., "25-Jun") back to correct categorical formats (e.g., "6-25" for company size).

Handled missing or ambiguous entries by:

Converting "NA" and "Not applicable" to NULL/blank

Excluding outliers in the Age column and binning remaining values into age brackets.

Created meaningful bins for:

Age groups (e.g., 18–24, 25–34, etc.)

Company size ranges (1–5, 6–25, etc.)

📊 Analysis with Pivot Tables:
Built multiple pivot tables to explore how treatment-seeking behavior varies across key dimensions:

Factor	Insight Explored
Gender: Compared treatment rates between male and female.
Age Group:	Identified patterns in help-seeking across different age brackets.
Remote Work:	Analyzed if remote workers are more likely to seek treatment.
Self-Employment:	Explored differences in behavior among freelancers and employees.
Anonymity at Work:	Assessed how workplace anonymity impacts treatment behavior.
Benefits & Support:	Looked at whether company-provided benefits correlate with higher treatment-seeking.

📈 Key Calculations:
Calculated % of respondents who sought treatment across various subgroups.

Used “Show Values As → % of Row Total” to express proportional comparisons.

Segmented by multiple factors (e.g., Gender + Age).

# A/B Testing – Conversion Rate Analysis

## Project Overview
This project simulates an A/B testing scenario to evaluate the effectiveness of a website change on user conversion rates. Using a synthetic dataset, the analysis identifies whether a statistically significant difference exists between the control and treatment groups. This type of work mirrors real-world product optimization and marketing strategies used by companies like American Express to drive customer engagement and growth.
---
## Business Problem
Companies often make changes to their websites, apps, or customer experiences. But how can they know if these changes actually improve key metrics—like conversions?
This project answers:
- **Did the treatment group outperform the control group?**
- **Was the improvement statistically significant?**
- **Should the business adopt the new version sitewide?**
---
## Data Summary
- **Source**: Synthetic dataset with ~6,000 observations
- **Features**:
  - `user_id`: Unique visitor
  - `group`: Control or Treatment
  - `converted`: Binary outcome (0 = No, 1 = Yes)
---
## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Distribution of users across groups
   - Baseline conversion rates
2. **Hypothesis Testing**
   - Null Hypothesis: No difference in conversion rates
   - Alternative Hypothesis: Treatment group has a higher conversion rate
   - Statistical Test: Two-proportion z-test
3. **Confidence Intervals**
   - 95% CI for conversion rate difference
4. **Decision & Recommendations**
   - Business rationale based on statistical findings
---
## Key Insights
- **Conversion Rate – Control**: ~11.8%  
- **Conversion Rate – Treatment**: ~13.3%  
- **Lift**: +1.5 percentage points
- **P-value**: 0.027 (Statistically significant at 5%)

**Recommendation**: Roll out the new version—it leads to a statistically significant and practical improvement in conversions.
---
## Tools & Technologies
- Python (Pandas, NumPy, SciPy, Matplotlib)
- Jupyter Notebook
- Statistical Testing (z-test, CI)
- Git/GitHub for version control
---
## Skills Demonstrated
- Business-focused experimentation
- Hypothesis testing and statistical inference
- Data cleaning and aggregation
- Communicating results with visual and written clarity
- Decision-making support with confidence bounds
---
## Live Code & Notebook
You can view the notebook [here](https://github.com/MujtabaMuhammad/ab-testing-conversion-analysis/blob/main/ab_test_analysis.ipynb).
---
## Contact
Feel free to connect or reach out if you'd like to collaborate or ask questions!
[LinkedIn](https://www.linkedin.com/in/mujtaba-muhammad) | [GitHub](https://github.com/MujtabaMuhammad)

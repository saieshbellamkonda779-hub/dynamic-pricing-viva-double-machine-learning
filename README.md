# dynamic-pricing-viva-double-machine-learning
Data Preparation – Member 1


Objective


Prepare and validate the team's selected dataset for the Dynamic Pricing via Double Machine Learning project.


Responsibilities




Document the selected dataset, source, and variables.


Check data types, missing values, and duplicate records.


Investigate unusual price and sales values.


Assess whether the available variables support causal price-effect analysis.


Document data-quality issues, limitations, and findings for the project team.




Dataset




File: wcer (1).csv


Rows: 4,751,202


Columns: STORE, UPC, WEEK, MOVE, PRICE


Purpose: Analyze store-product sales and prices over time.




Current Status


The team-selected dataset has been identified for the project. Data preparation includes checking data quality, understanding the available variables, and documenting limitations relevant to the planned Double Machine Learning analysis.


Data Limitations


The available columns do not explicitly identify discounts, promotions, or other potential confounding factors. These limitations should be considered before interpreting estimated price effects as causal.


Next Steps




Verify data-quality checks against the final dataset.


Document confirmed validation results.


# Dynamic Pricing via Double Machine Learning

Project: Dynamic Pricing
Role: Member 1 — Data Preparation and Causal Analysis
Date: 2026-10-22

1. Objective
Analyze whether observed product price affects sales movement while accounting for store, product, and time-related factors using Double Machine Learning (DML).

2. Dataset Overview
File: wcer (1).csv
Rows: 4,751,202
Columns: 5

Column Description:
- STORE: Store identifier
- UPC: Product identifier
- WEEK: Time-period identifier
- PRICE: Observed product price
- MOVE: Recorded sales movement; exact interpretation to be confirmed

3. Completed Work
- Inspected the dataset schema.
- Checked for missing values; none were found.
- Checked for exact duplicate rows; none were found.
- Reviewed price and sales movement distributions through EDA.
- Documented provisional causal assumptions.

4. Pending Validation
- Confirm the treatment definition (PRICE) and outcome definition (MOVE) with the team.
- Check price overlap and positivity across comparable store-product-week groups.
- Review the causal graph and potential confounding factors.
- Assess whether the available variables adequately support causal identification.

5. Limitations and Risks
Unobserved demand, promotions, and other omitted factors may confound the relationship between price and sales movement. The available dataset contains five listed variables; additional confounders may not be available. Positivity and overlap have not yet been verified. No causal effect is claimed at this stage.

6. Next Steps
- Validate the treatment and outcome definitions with the team.
- Assess overlap in price assignments across comparable groups.
- Review the causal graph with the team.
- Update the assumptions and limitations based on findings.

Current status:
Initial data checks, EDA, and documentation completed; causal validation remains in progress.
Coordinate with the team on the treatment variable, outcome variable, and available control variables for the DML pipeline.




# Sensitivity Analysis of Key Assumptions – With-Profit Endowment Assurance

Sensitivity analysis of a With-Profit Endowment Assurance product using Microsoft Excel to evaluate the impact of changes in key pricing and valuation assumptions on product profitability.

The objective is to identify key profitability drivers, understand how changes in individual assumptions influence the financial performance of the product, and assess the potential risks associated with different pricing and valuation scenarios.

## Technologies Used

- **Microsoft Excel:** Financial modelling, calculations, sensitivity analysis and data visualisation.

### Key Concepts

- Actuarial Valuation
- Premium and Claim Cost Analysis
- Present Value of Future Liabilities
- Profitability Analysis
- Break-even Analysis
- Sensitivity Analysis
- With-Profit Endowment Assurance

## Base Scenario – Model Inputs and Assumptions

The following assumptions were used to establish the base scenario for the With-Profit Endowment Assurance valuation model.

| Parameter | Base Assumption |
|---|---|
| Mortality Table | AM92 (Actuarial Booklet) |
| Age at Entry | 42 years |
| Policy Term | 20 years |
| Annual Premium | ₹26,000 |
| Simple Bonus | 3% of Premium |
| Sum Assured | ₹500,000 |
| Initial Expenses | ₹850 |
| Renewal Expenses | ₹100 |
| Initial Commission | 40% of Premium |
| Renewal Commission | 5% of Premium |
| Death Claim Expenses | ₹500 |
| Maturity Claim Expenses | ₹300 |
| Expense Inflation | 1.25% |
| Interest / Risk Discount Rate | 5% |

These assumptions form the reference point for the sensitivity analysis. Individual assumptions were varied while keeping the remaining assumptions constant to evaluate their impact on product profitability.

## Features of the Project

- Analysis of three key assumptions affecting product profitability:
  - Premium
  - Sum Assured
  - Interest Rate
- Evaluation of profitability under different assumption scenarios.
- Identification of break-even points for each assumption.
- Visualisation of changes in profitability using charts.
- Assessment of the relationship between individual assumptions and product profitability.

## Project Process

1. **Base Model:** Establish a With-Profit Endowment Assurance valuation model using the specified base assumptions.
2. **Sensitivity Analysis – Premium:** Vary premium levels while keeping other assumptions constant to evaluate their impact on profitability.
3. **Sensitivity Analysis – Sum Assured:** Vary the sum assured to assess changes in expected benefit liabilities and product profitability.
4. **Sensitivity Analysis – Interest Rate:** Change the interest rate assumptions to examine their impact on the present value of future benefit obligations.
5. **Profitability Assessment:** Calculate the resulting profit or loss under each scenario.
6. **Visualisation and Interpretation:** Use charts to compare results, identify break-even points and interpret the impact of each assumption.

## Key Findings

### 1. Premium Sensitivity

- Profitability increases as the premium increases.
- At a premium of ₹22,000, the policy generates a loss of ₹46,321.87.
- Losses gradually reduce as premiums increase from ₹22,000 to ₹25,000.
- The break-even point lies between ₹25,000 and ₹26,000, where profit changes from a loss of ₹10,709.23 to a profit of ₹1,161.65.
- Profit reaches ₹60,516.04 at a premium of ₹31,000.
- Premium and profitability demonstrate a positive and approximately linear relationship across the range analysed.

### 2. Sum Assured Sensitivity

- Profitability decreases as the sum assured increases.
- At a sum assured of ₹300,000, the policy generates a profit of ₹123,230.44.
- Profit declines consistently as the sum assured increases from ₹300,000 to ₹750,000.
- At the base sum assured of ₹500,000, profit is approximately ₹1,161.65.
- Beyond ₹500,000, the policy becomes unprofitable, with losses increasing as the sum assured rises.
- At a sum assured of ₹750,000, the model records a loss of ₹151,424.34.
- Sum assured and profitability demonstrate a strongly negative relationship.

### 3. Interest Rate Sensitivity

- Profitability increases as the interest rate increases.
- At an interest rate of 2%, the policy records a loss of ₹145,384.20.
- Losses reduce as the interest rate increases.
- The model reaches the break-even point around the base interest rate assumption of 5%, where profit is approximately ₹1,161.65.
- Profit reaches ₹80,247.96 at an interest rate of 8.75%.
- Interest rate and profitability demonstrate a positive relationship across the range analysed.

### Overall Findings

The sensitivity analysis indicates that profitability is highly dependent on the assumptions used in the valuation model.

- Premium and interest rate assumptions have a positive relationship with profitability.
- Sum assured has a negative relationship with profitability.
- Changes in sum assured and interest rate produce particularly large variations in profit.
- The analysis identifies break-even points for all three assumptions, highlighting the importance of appropriate pricing and valuation assumptions.

## What I Learned

- Understanding the financial structure of a With-Profit Endowment Assurance product.
- Analysing the impact of pricing and valuation assumptions on profitability.
- Understanding the relationship between premiums, sum assured and expected benefit liabilities.
- Applying sensitivity analysis to financial and actuarial models.
- Identifying break-even points and interpreting profitability trends.
- Understanding the importance of interest rate assumptions in the valuation of long-term insurance liabilities.
- Assessing how changes in key assumptions can affect the financial sustainability of an insurance product.

## Next Steps

- Extend the analysis by varying multiple assumptions simultaneously.
- Conduct scenario analysis under different economic conditions.
- Explore the impact of mortality and expense assumptions on profitability.
- Develop a more comprehensive profitability model incorporating additional actuarial assumptions.

## How to Run the Project

1. Download or clone this repository.
2. Open the Excel workbook included in the repository.
3. Review the base assumptions and valuation calculations.
4. Modify the selected assumptions to explore different scenarios.
5. Observe the resulting changes in profitability.

**Reference:** The base assumptions used in the valuation model were derived from the Institute of Actuaries of India (IAI) CM1B – Actuarial Mathematics Practice Examination Paper, September 2021.

**Additional Assumption:** Death benefits were assumed to be payable at the end of the year of death.

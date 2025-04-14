# Homework-8
Homework 8 for SDS 315

# Homework 3: Regression, Disease Growth Modeling, and Price Elasticity

This homework assignment analyzes three datasets to answer questions using linear regression, bootstrapping, and log-log models. The problems focus on kidney health, COVID-19 death growth, and price elasticity of demand.

## Files Included

- **creatinine.csv**  
- **covid.csv**  
- **milk.csv**  
- **Homework3.Rmd**  

### Problem 1: Regression Warm-Up

- **Objective:**  
  Use linear regression on the `creatinine.csv` data to:
  - Predict creatinine clearance for a 55-year-old.
  - Determine the change in clearance per one-year increase in age.
  - Compare whose creatinine clearance is healthier (relative to age): a 40-year-old with a rate of 135 mL/min or a 60-year-old with a rate of 112 mL/min.

### Problem 2: Modeling Disease Growth

- **Objective:**  
  Model the exponential growth of COVID-19 deaths using `covid.csv` data for Italy and Spain. Specifically, estimate:
  - The daily growth rate.
  - The doubling time of deaths.

### Problem 3: Price Elasticity of Demand

- **Objective:**  
  Estimate the price elasticity of demand for milk using the `milk.csv` dataset.

## How to Run the Analysis

1. **Preparation:**  
   Place the CSV files (`creatinine.csv`, `covid.csv`, and `milk.csv`) in the directory specified in the code (e.g., `~/Documents/SDS315/`).  
   If necessary, update the file paths in `Homework3.Rmd` to match your local setup.

2. **Execution:**  
   Open the `Homework3.Rmd` file in RStudio and click the *Knit* button to generate the final report in your preferred format (HTML or PDF).

3. **Results:**  
   The knitted document includes:
   - Regression predictions and interpretations for Problem 1.
   - Estimated growth rates, doubling times, and corresponding bootstrapped confidence intervals (presented using **kable**) for Problem 2.
   - Estimated price elasticity and its bootstrapped 95% confidence interval (also formatted with **kable**) for Problem 3.

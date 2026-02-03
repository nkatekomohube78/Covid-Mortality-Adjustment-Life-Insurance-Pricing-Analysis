# Covid-Mortality-Adjustment-Life-Insurance-Pricing-Analysis
Actuarial pricing analysis of Covid-adjusted mortality and its impact on life insurance premiums using Excel.

## Overview
This project evaluates the impact of **Covid-19 mortality loadings** on the pricing and competitiveness of **whole life insurance policies**.  
Using actuarial pricing techniques, the analysis compares current Covid-loaded mortality assumptions with alternative post-Covid scenarios, including vaccination-adjusted mortality.

The objective is to assess whether existing premiums remain competitive and to support informed pricing decisions.



## Business Context
Following elevated claims during the Covid-19 pandemic, mortality rates were increased using age-based Covid loadings.  
As conditions normalize, insurers must reassess:
- Whether Covid loadings should be removed
- Whether mortality assumptions should depend on vaccination status
- The resulting impact on premiums and profitability


## Product & Assumptions
- **Policy type:** Whole life insurance
- **Age at entry:** 35
- **Terminal age:** 120
- **Sum assured:** R1,000,000 (with sensitivity testing up to R20,000,000)
- **Interest rates:** Term structure provided in the template
- **Expenses:** Initial and renewal expenses with inflation
- **Mortality:** Base mortality rates with age-dependent Covid loadings


## Scenarios Analysed

### Current Basis
- Mortality rates include full Covid loadings

### Scenario 1: Pre-Covid Mortality
- All Covid loadings removed
- Assumes Covid risk has fully dissipated

### Scenario 2: Vaccination-Adjusted Mortality
- Pre-Covid mortality applies only to fully vaccinated policyholders
- Post-Covid mortality applies to partially or unvaccinated lives
- Vaccination probabilities adjusted for insured population behaviour


## Methodology

### 1) Vaccination Probability Modelling
- Estimated probability of being fully vaccinated (initial + 2 boosters)
- Adjusted population statistics to reflect insured lives

### 2) Mortality Rate Adjustment
- Derived revised mortality rates for each scenario
- Applied age-dependent Covid loadings where applicable

### 3) Survival & Life Expectancy
- Calculated curtate life expectancy at age 35
- Compared outcomes under Covid and pre-Covid mortality

### 4) Premium Calculation
- Calculated annual premiums (paid in advance)
- Included expenses, inflation, and discounting
- Compared premiums across all scenarios

### 5) Sensitivity Analysis
- Premium comparison across multiple sum assured levels
- Visual comparison using clear graphical outputs


## Results
- Covid loadings materially increase life insurance premiums
- Removing loadings significantly improves price competitiveness
- Vaccination-adjusted mortality provides a balanced alternative
- Higher sums assured amplify pricing differences
- Life expectancy increases meaningfully under pre-Covid assumptions


## Recommendation
Based on premium competitiveness and risk differentiation, a **partial removal of Covid loadings** through vaccination-adjusted mortality provides a more sustainable pricing approach than a full removal.


## Skills Demonstrated
- Actuarial life insurance pricing
- Mortality modelling and adjustments
- Scenario and sensitivity analysis
- Interpretation of demographic statistics
- Professional Excel model design
- Clear actuarial communication


## Tools
- Microsoft Excel 


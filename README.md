# Ratio Estimator Analysis for 2022 ACS Data

## Project Overview

This project uses the 2022 American Community Survey (ACS) data obtained from [IPUMS USA](https://usa.ipums.org/usa/) to estimate the total number of respondents in each state based on the number of respondents with doctoral degrees. The analysis employs the **ratio estimator** approach, using California as the reference state, to estimate the total number of respondents for other states.

### Key Components:
- **Data:** We focus on respondents whose highest educational attainment is a doctoral degree (using the `EDUCD` variable).
- **Method:** The ratio estimator approach is used to estimate the total number of respondents in each state, leveraging California's known respondent totals.
- **Comparison:** The estimated total respondents are compared to the actual number of respondents in each state.
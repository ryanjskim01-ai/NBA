# NBA Player Value Analysis

**Identifying market inefficiencies in NBA player salaries using statistical modeling**

## Project Overview

This project analyzes NBA player performance data to identify players whose salaries don't align with their on-court value. Using linear regression modeling in R, I created a "value score" metric that combines key performance statistics and compared it against actual salaries to find the most overpaid and underpaid players in the league.

## Key Findings

**Most Overpaid Players:**
- Players performing significantly below their salary expectations
- Identified through negative salary difference (actual > expected)

**Most Underpaid Players:**
- High-value performers earning less than statistical model predicts
- Identified through positive salary difference (expected > actual)

## 🛠️ Technologies Used

- **R** - Statistical analysis and modeling
- **tidyverse** - Data manipulation
- **ggplot2** - Data visualization
- **ggrepel** - Label positioning
- **plotly** - Interactive visualizations
- **Excel** - Data cleaning and preparation

## Methodology

1. **Data Collection:** Compiled player statistics and salary data
2. **Feature Engineering:** Created composite "value score" from performance metrics
3. **Statistical Modeling:** Built linear regression model (salary ~ value_score)
4. **Residual Analysis:** Calculated salary difference (actual - predicted)
5. **Visualization:** Created scatter plots showing overpaid/underpaid players

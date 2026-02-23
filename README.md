# Movie Data Analysis

## Author
Uziel Saldivar
B.S. Information Science — University of Maryland
Focus: IT Infrastructure & Data Analytics

## Overview
This project analyzes the relationship between movie budget, popularity, and IMDb audience ratings using datasets 
from TMDB and IMDb (sourced from Kaggle).

## Tools Used
- Python (Pandas, Matplotlib)
- Google Colab
  
## Skills Demonstrated
- Data cleaning & preprocessing
- Dataset merging
- Correlation analysis
- Log transformation for skew correction
- Quantile-based grouping
- Time-series trend analysis
- Data visualization
- Analytical interpretation of findings
  
## Key Findings
- Higher budgets strongly increase popularity (visibility).
- Higher budgets have almost no correlation with IMDb ratings (r ≈ -0.04).
- Older films tend to have higher median ratings compared to recent decades.

## Methods and Approach
- Merged TMDB and IMDb datasets (~3,300 cleaned records after filtering)
- Removed missing values and duplicates
- Applied log₁₀ transformation to budget data to correct skew
- Conducted correlation analysis
- Created:
  - Scatter plots (Budget vs IMDb rating)
  - Bar charts (Popularity by budget group)
  - Line graphs (Ratings over decades)

## Tools Used
- Python
- Pandas
- Matplotlib
- Google Colab

## Data Sources (All Downloaded from Kaggle)
- TMDB Movies Dataset (2024)
- IMDb Dataset (2024 Updated)

## Future Improvements
- Genre-based comparisons
- Marketing spend data
- Revenue vs budget comparisons
- Audience demographic segmentation


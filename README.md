# Hospital Readmissions Analysis

## Objective
Analyze CMS Hospital Readmissions Reduction Program (HRRP) data to identify
patterns in excess 30-day readmissions across U.S. hospitals and clinical
conditions.

## Data Source
Centers for Medicare & Medicaid Services (CMS) – Hospital Readmissions Reduction
Program (HRRP) dataset, containing hospital-level readmission metrics for
multiple conditions.

## Key Questions
- Which clinical conditions show the greatest variability in excess
  readmission ratios?
- Are hospitals generally meeting CMS readmission benchmarks?
- Which conditions may warrant targeted quality improvement efforts?

## Methods
- Loaded and cleaned CMS HRRP data using Python and pandas
- Standardized column names and converted numeric fields
- Filtered hospitals with valid discharge and readmission data
- Conducted exploratory data analysis (EDA) by clinical condition
- Visualized distributions using boxplots to assess variability and outliers

## Key Findings
- Median excess readmission ratios cluster near CMS benchmarks (≈1.0) across
  most conditions
- Hip and knee replacement procedures show substantially greater variability
  in hospital performance compared to other conditions
- Certain conditions demonstrate tighter distributions, suggesting more
  standardized care pathways

## Visualizations
- Boxplot of excess readmission ratios by clinical condition

## Tools Used
- Python (pandas, matplotlib)
- Jupyter Notebook
- VS Code

## Next Steps
- Rank hospitals by excess readmission ratio to identify consistently
  high-performing and low-performing facilities
- Analyze geographic variation in readmission performance by state
- Examine the relationship between hospital volume and readmission outcomes
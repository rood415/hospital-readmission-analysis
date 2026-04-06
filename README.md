# Hospital Readmissions Analysis

CMS penalizes hospitals financially for excess 30-day readmissions. 
This project analyzes national HRRP data to identify which clinical 
conditions and hospitals are struggling most and where targeted 
quality improvement efforts would have the greatest impact.

## Objective
Analyze CMS Hospital Readmissions Reduction Program (HRRP) data to 
identify patterns in excess 30 day readmissions across U.S. hospitals 
and clinical conditions.

## Data Source
Centers for Medicare & Medicaid Services (CMS) – Hospital Readmissions 
Reduction Program (HRRP) dataset, containing hospital-level readmission 
metrics for multiple conditions.

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
- Median excess readmission ratios cluster near CMS benchmarks (≈1.0) 
  across most conditions, suggesting most hospitals are broadly compliant
- Hip and knee replacement procedures show substantially greater 
  variability than other conditions indicating inconsistent care 
  quality and a high value target for intervention programs
- Conditions with tighter distributions suggest more standardized care 
  pathways exist and could serve as models for higher variability areas

## Visualizations
- Boxplot of excess readmission ratios by clinical condition

## Tools Used
- Python (pandas, matplotlib)
- Jupyter Notebook
- VS Code

## Next Steps
- Rank hospitals by excess readmission ratio to identify consistently 
  high-performing and low performing facilities
- Analyze geographic variation in readmission performance by state
- Examine the relationship between hospital volume and readmission outcomes

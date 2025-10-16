# U.S. Healthcare Access and Socioeconomic Analysis (2022-2024)
A comprehensive data analysis examining the relationship between healthcare provider availability and socioeconomic factors across all U.S. counties.

## Overview
This project analyzes healthcare access disparities across the United States by examining the correlation between healthcare provider availability and key socioeconomic indicators including poverty rates, median income, and population density. The analysis identifies healthcare deserts and provides evidence-based recommendations for policy intervention.

## Key Findings

### Correlation Analysis
- Poverty Rate: Strong negative correlation with healthcare access
- Median Income: Moderate positive correlation with provider availability
- Population Density: Weak to moderate positive correlation
- Access Score: Very strong positive relationship with provider availability

### Healthcare Landscape

- A substantial proportion of U.S. counties experience healthcare provider shortages
- Healthcare deserts are concentrated in specific geographic regions
- Counties with high poverty and low population face compounded disadvantages
- Economic viability significantly impacts provider distribution

### Critical Insights
The analysis reveals a compound effect where counties with both high poverty rates and low population density experience the most severe healthcare provider shortages, creating areas of critical need that require targeted intervention.

## Data Sources

Health Resources and Services Administration (HRSA) - Health Professional Shortage Areas
Center for Disease Control - Healthcare access measures
County Health Rankings & Roadmaps - Poverty rates, median income, rural-urban codes

## Methodology

1. Data Collection: Aggregated county-level data from multiple federal sources (2022-2024)
2. Data Cleaning: Standardized metrics and addressed missing values
3. Correlation Analysis: Pearson correlation coefficients calculated for key variables
4. Geographic Analysis: Mapped healthcare deserts and shortage areas
5. Statistical Testing: Validated relationships and identified significant predictors
6. Visualization: Created comprehensive charts and geographic heat maps

## Technologies Used

Python
Pandas - Data manipulation and analysis
NumPy - Numerical computations
Matplotlib/Seaborn - Data visualization
Jupyter Notebook - Interactive analysis environment

## Installation

### Clone the repository
git clone https://github.com/matt-lawl/healthcare-access-analysis.git
cd healthcare-access-analysis

### Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### Install dependencies
pip install -r requirements.txt

## Strategic Recommendations

Based on the analysis findings:

- Primary Focus: Target identified healthcare desert counties with immediate intervention programs
- Economic Incentives: Develop financial models to improve economic viability of rural healthcare practice
- Poverty-Focused Strategy: Prioritize counties with high poverty rates as strong predictors of provider shortage
- Compound Disadvantage: Design intensive intervention programs for counties facing multiple barriers
- Alternative Care Models: Implement telehealth and mobile clinic solutions in most disadvantaged areas

### Policy Implications

The strong negative correlation between poverty and healthcare access suggests that economic factors are primary drivers of healthcare disparities. Policymakers should consider:

- Loan forgiveness programs for providers serving high-poverty areas
- Enhanced reimbursement rates for rural and underserved regions
- Infrastructure investment to support alternative care delivery models
- Comprehensive approaches addressing both healthcare access and economic development

### Future Work

- Longitudinal analysis tracking changes over time
- Machine learning models to predict future shortage areas
- Cost-benefit analysis of intervention strategies
- Integration of health outcome data
- Analysis of specific healthcare specialties

### Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Contact

Matthew Lawlor - mattlawlor00@gmail.com
Project Link: https://github.com/matt-lawl/healthcare-access-analysis

### Acknowledgments

Data provided by County Health Rankings & Roadmaps, HRSA, and CDC
Inspired by ongoing research in healthcare equity and rural health
Thanks to all contributors to open-source data science tools

For questions, issues, or collaboration opportunities, please open an issue or contact the project maintainer.

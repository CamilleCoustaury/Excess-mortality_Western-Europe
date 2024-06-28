# Patterns and drivers of Excess mortality during the COVID-19 pandemic in 13 Western European countries

# Summary
In this paper, we examine patterns in age and sex-standardised cumulative excess mortality in 13 Western European countries during the first thirty months of the COVID-19 pandemic. In a timeline analysis, we identified notable differences in seeding events, particularly in early 2020. Lower excess mortality was associated with implementing stringent non-pharmaceutical interventions (NPIs) when hospital admissions were still low in 2020, and rapid roll-out of vaccines in the elderly in early 2021. Countries which implemented NPIs while hospital admissions were low tended to experience lower GDP losses in 2020. Structural factors, such as high trust in the national government and low ratio of population at risk of poverty were also associated with lower excess mortality. Further analyses are required at a more granular level to better understand how these factors impacted excess mortality and help guide pandemic preparedness plans.

# System requirements
The analysis were implemented on Jupyter Notebook version 6.5.4 using Python version 3.11.5

# FIle description
This Git repository contains: 
- *Excess_mortality-final_analysis.ipynb* which contains code for replicating the excess mortality curves.
- *Figures_NPI_paper.ipynb* which contains code for replicating the excess mortality factor analysis.
- a *Data* file containing all the data needed to replicate the results
More specifically, the *Data* file contains :
- *monthly_deaths_pop_ireland.xlsx* and *stmf.xlsx*: the two data files compiling mortality data
- *raw_data_scatter_plots_cc_post_standardisation.xlsx* the data file containing all data used in the excess mortality factor analysis.

# Instruction for use
After downloading the repository, user must change before running the code: 
- the "path_user" variable in *Excess_mortality - final analysis.ipynb* cell 2, to the "Data" file path
- the "data_path" variable in *Figures_NPI_paper.ipynb* cell 2, to the *raw_data_scatter_plots_cc_post_standardisation.xlsx* in the "Data" file path
The total run time for a normal desktop computer can take up to 8 minutes. 

# modoc-expenses
Analysis of expenditures data from the Missouri Department of Corrections

All files used in this analysis was downloaded from the Missouri Accountability Portal: https://mapyourtaxes.mo.gov/MAP/Portal/Default.aspx

Data had to be downloaded by each individual fiscal year, and combined into a master-file in R. I analyzed expenditures of the Department of Corrections, with special focus on vendors paid for medical and dental services. 

The analysis includes two versions of the same dataset, downloaded from different pages of the Missouri Accountability Portal. The bulk of findings were made with the file labled corr_expenses. 

Some cleaning was done with this file outside of R in OpenRefine, to ensure vendor names were spellec consistently. After cleaning, I used dplyr and ggplot to show trends in which vendors received the greatest total payments each fiscal year, and how department payments to specific vendors of interest changed over time.

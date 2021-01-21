# COVID-19_Deaths_USA
Deaths reported from COVID-19, pneumonia, and influenza for age goups in the USA

This notebook sets out to determine whether there is a statistically significant difference in COVID-19 deaths reported by age group.

The data for this project comes from the national Center for Health Statistics (NCHS) throu the Center for Disease Contol (CDC)
and can be found here: https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-by-Sex-Age-and-S/9bhg-hcku 

The data reveals that there are significant differnce in COVID-19 deaths by age group, especially between the youngest and eldest groups.
The data also reveals that the reported deaths for COVID-19 also follow a trend similar to that of pneumonia and influenza.

Tools used:

 - Language: Python Version 3.8.3
 - Libraries:
   - Pandas and Numbpy are used to handle data frames and some computation
   - scipy is also used for some computation
   - stats is used to handle Kruskal-Walis testing and multipletest
   - seaborn is used to handle most of the visuals
   
Future Plans:

- Analyze other diseases for comparison
- Do the same kind of analysis of COVID-19 with comorbidities
- Revisit this with data post-vaccine for compaison 

  


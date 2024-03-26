# segregation

Project Title: Housing and ethnic Segregation Analysis in major Iranian Cities

Description:

This project analyzes housing segregation patterns in three major cities of Iran. It merges survey data on housing and population for three major iranian cities (Tehran, Isfahan, Mashhad) to calculate Shannon's and Theil's entropy for three categories:

Single-family vs. Multi-family housing type
Rental vs. Owned housing type
Native vs. Immigrant dwellers

Using decomposed entropy of information, in the final step it was calculated how much the entropy of neighborhoods are due to the entropies of bigger scales such as districts and cities but not neighborhoods themselves. 

Data:

The project utilizes geolocated survey data on housing and population from the three main cities of Iran (2016). The data includes information on housing type (single-family/multi-family), ownership type (rental/owned), and dwelling status (native/immigrant).
the survey was executed at census block level which is agggregated at neighborhood level. with the hierarchical structure as neighborhoods nested within districts and districts are nestesd within cities 
Methodology:

Data Cleaning and Preparation: The data was cleaned and prepared for analysis, potentially including handling missing values and inconsistencies.
Theil's Entropy Calculation: Theil's entropy be calculated for each category, following the method outlined in the article "Uneven geographies: Exploring the sensitivity of spatial indices of residential segregation" by Barros and Feitosa (2018).
Shannon's Entropy Calculation: Shannon's entropy will be calculated for each category to measure the level of diversity/segregation in housing distribution. following the method described by Sarkar et al, (2024).
decomposed entropy of information: this feature enable us to calculate to what extent the value of segregation of neighborhoods are due to larger scales such as cities and districts, but not the structure of neighborhoods themselves (Owen, 2019).

Outputs:

The project will generate reports (in .ipynb ) that detail the following:
Descriptive statistics of the housing and population data.
Calculated Shannon's and Theil's entropy values for each category in each city.
Interpretation of the results, considering the entropy values and potential segregation patterns.

Software:
Python (pandas, numpy)

References:

Sarkar, S., Gurran, N., Shrivastava, R., & Chapple, K. (2024). Spatial segregation and neighbourhood change (No. jm95p). Center for Open Science.

Owens, A. (2019). Building inequality: Housing segregation and income segregation. Sociological Science, 6, 497.

Barros, F. C., & Feitosa, F. C. (2018). Uneven geographies: Exploring the sensitivity of spatial indices of residential segregation. Social Science Research, 90, 366-380.

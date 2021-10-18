# eds213_group8

## Research Question
Potential research question: How do population demographics impact lead exposure in Philadelphia communities?

Potential dataset found on DataONE: https://search.dataone.org/view/https%3A%2F%2Fpasta.lternet.edu%2Fpackage%2Fmetadata%2Feml%2Fedi%2F998%2F1


## Data Management Plan
1. We are collecting all data from the Lead Risk Factors for West and North Philadelphia: 2007-2020 from the Environmental Data Initiative stored on DataOne. We will collect all data describing lead risk factors, includeing: lead-in-soil, land recycled sites, demolitions, housing code violations, age of housing, smelters, and elevated blood lead levels of children. This includes data initially collected between 2007 - 2020. We will also be collecting demographic data, including: age, race, socioeconomic status, and renter occupation measures. This data is from the 2010 U.S. Census. 

2. It took our whole group, working together, approximately four hours to find the data and create a system to download the data that leaves each user responsible to manage the data on their local computer. We are using the `metajam` package which uses the DataOne API to access data. In the group8.Rmd, we included a code chunk that is not automatically evaluated, which each user can run to download the data. When manually run, this script will create a "data" folder within the .Rproj and download all data and metadata into said folder. We also added the "data" folder to the .gitignore in order to store the data locally, rather than on GitHub. This data is already Tidy as it was previously used for analysis, so will not take much additional time to clean.

3. We imagine this project will be a good resource throughout the duration of our Master of Environmental Data Science (MEDS) program. Therefore, we would like to preserve this data at least through December 2022 to be referred to for future projects and MEDS students. We will be preserving the data and our analysis code on The Knowledge Network for Biocomplexity (KNB).

4. There no legal constraints. It is recommended that users of this data reach out to the creators of the package in order to prevent duplicate research.

## Ontogeny

*The DataONE repository for the data contains definitions for features of the dataset. Below is an example.* 

**% Renter Occupied:** "The percent of housings units that are rented and occupied by a renter over the total number of housing units per census tract" This is the definition from DataONE; we would update this definition by including data source information. For example, this data is calculated from 2019 housing surveys from the American Community Survey's 2019 statistics. 



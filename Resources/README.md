## List of Resources

### NOTE: resource files have relocated to Amazon S3 bucket locations:
The resource files for this project have been moved from github to Amazon S3 storage services. The section below on **Sources:** contain URLs for new locations.

### COVID-19 Case Surveillance Public Use Data with Geography
- Downloaded the raw csv dataset from the CDC website:
https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data-with-Ge/n8mc-b4w4/data
- Multiple attempts to upload the raw datafile to GitHub (including using Git LFS), but the file size was too large

### CA County Demographic Data 20210804:
Created a dataset by data entry in Excel that compiled California county demographic data from various web sources. 

**Sources:**

- CDC COVID Tracker Data/COVID-19 Integrated County View
https://covid.cdc.gov/covid-data-tracker/#county-view
- County Health Rankings & Roadmaps
https://www.countyhealthrankings.org/app/california/2021/overview
- Statewide COVID-19 Cases Deaths Tests
https://data.chhs.ca.gov/dataset/f333528b-4d38-4814-bebb-12db1f10f535/resource/046cdd2b-31e5-4d34-9ed3-b48cdbc4be7a/download/covid19cases_test.csv
- County FIPS Codes
https://www.nrcs.usda.gov/wps/portal/nrcs/detail/national/home/?cid=nrcs143_013697

The resource files for this project have been moved from github to Amazon S3 storage services.
The following are the location URLs for the resource files in this project:

Clean/ca_data_df.csv
https://mygits3bucket.s3.us-west-1.amazonaws.com/Clean/ca_data_df.csv

Clean/ca_county_demographic_data-20210804.csv
https://mygits3bucket.s3.us-west-1.amazonaws.com/Clean/ca_county_demographic_data-20210804.csv

Clean/ca_county_demographic_data-20210804.xlsx
https://mygits3bucket.s3.us-west-1.amazonaws.com/Clean/ca_county_demographic_data-20210804.xlsx

Raw/Statewide_COVID-19_Cases_Deaths_Tests.csv
https://mygits3bucket.s3.us-west-1.amazonaws.com/Raw/Statewide_COVID-19_Cases_Deaths_Tests.csv


**Calculations:**
- Cumulative Deaths /Cases (calculated by EK): Using Excel, divided values in column E (Cumulative Deaths (2020-02-01 - 2021-31-07)) by values in column D (Cumulative Cases (2020-02-01 - 2021-31-07)).
- Cases per capita (calculated by EK): Using Excel, divided values in column C (Cumulative Cases (2020-02-01 - 2021-31-07)) by values in column H (Total Population).
- Deaths per capita (calculated by EK): Divided values in column D (Cumulative Deaths (2020-02-01 - 2021-31-07)) by values in column H (Total Population).



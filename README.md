This will be an ongoing process to create a single dataset for research related to crime. The single data is called "master\_crime". The datasets currently included here are:

1.  ucr\_offenses\_clearances - [UCR Offenses Known and Clearances by Arrest 1960-2015](http://www.icpsr.umich.edu/icpsrweb/NACJD/series/57)

    This dataset contains:
    -   Yearly counts for crimes committed (aggregated from monthly count)
    -   Yearly counts for crimes cleared (aggregated from monthly count)

2.  ucr\_police\_employee\_leoka - [UCR Police Employee (LEOKA) 1975-2015](http://www.icpsr.umich.edu/icpsrweb/NACJD/series/57)

    This dataset contains:
    -   The number of male/female officers and civilian employees
    -   Number of male/female officers per 1,000 population
    -   Number of total officers per 1,000 population
    -   Number of total civilian employees per 1,000 population

3.  ucr\_supplementary\_homicide\_report - \[UCR Supplementary Homicide Reports 1975-2014\] (<http://www.icpsr.umich.edu/icpsrweb/NACJD/series/57>)

    This dataset contains:
    -   Details on homicide victims, offenders, and circumstances
    -   Age, race, and gender of homicide victims
    -   Age, race, and gender of homicide offenders
    -   Relationship between victim and offender
    -   "Spouse" includes married and nonmarried partners as well as those in homosexual relationships.
    -   "Immediate family" does not include spouses
    -   Circumstances of the homicide
    -   Weapon used
    -   Number of murders
    -   This is different than total homicides. Total homicides includes all instances reported in this dataset. Total murders excludes negligent use of a firearm (e.g. hunting accident), shootings by very young children or felons who are killed by police officers or citizens.

4.  police\_agency\_identifier\_crosswalk - [Law Enforcement Agency Identifiers Crosswalk Series](http://www.icpsr.umich.edu/icpsrweb/NACJD/series/366)

    This dataset contains:
    -   The name of the agency, its county and census name, address and longitude/latitude.
    -   FIPS codes, census codes, csllea codes, and lemas codes to connect to various datasets
    -   Federal judicial district
    -   Number of households in the area
    -   Size of the area in square miles

5.  master\_column\_dictionary - Explains which dataset each of the columns in master\_crime is from.

If you have any questions, find any bugs, or have any data to offer, my email is <jacobkap@sas.upenn.edu>.

For file types other than R (.rda), please use the Dropbox link to download the files. The cleaned files are in the "clean\_files" folder. The raw data I used (from ICPSR) to create the datasets are also on Dropbox. The code used to create the cleaned files are in the "R\_code" folder. [Dropbox link](https://www.dropbox.com/sh/9jy8ds057h7m00d/AACC082n_hahaKooNnxuJBs7a?dl=0)

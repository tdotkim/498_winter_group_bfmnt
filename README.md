# 498_winter_group_bfmnt

*./example_code*: This holds examples for the using python or curl to get the data

*./example_code/download_with_python/big_import.ipynb*: does all the data pulls

*./etl*: how to join the datasets

uncomment out the sex offenders lines if you need to refresh it. still need to work on a incremental refresh option for speed.

*./geojsons*: This holds the geojsons for the different ways Chicago segments the city

Environmental Data - https://data.cityofchicago.org/Environment-Sustainable-Development/CDPH-Environmental-Complaints/fypr-ksnz/data_preview

Crimes Data - https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data

Sex offenders data - https://data.cityofchicago.org/Public-Safety/Sex-Offenders/vc9r-bqvy/data_preview *NOTE: SINCE ADDRESSES ARE ANONYMIZED, THE X ANONYMIZED VALUES ARE REPLACED WITH 0 SO 11XXX S STATE ST BECOMES 11000 S STATE ST TO APPROXIMATE THE LOCATION

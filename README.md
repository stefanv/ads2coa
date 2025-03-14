# AIRA INSTITUTE NSF COA Generator

This script generates the NSF COA from the author affiliations csv file.

## Installation:

```bash
pip install git+https://github.com/AIRA-Institute/ads2coa.git#egg=ads2coa
```

## Steps:

 - Get the author affiliations csv file from ADS and save
   it locally as `authorAffiliations.csv`.
   
 - Get the unadulterated NSF COA template from the NSF website:
https://www.nsf.gov/bfa/dias/policy/coa/coa_template.xlsx

 - Run this script (see `--help` for arguments):
    
```bash
ads2coa
```

 - Edit the generated file and save it as lastname_coa.xlsx 

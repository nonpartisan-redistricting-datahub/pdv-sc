# vest-sc-2016

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-south-carolina-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: VEST SC 2016 file
   - Date accessed: 8/18/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/NH5S2I/Y3OFQZ&version=66.0
   - File: `sc_2016.zip`
- File: VEST documentation file, 2016
   - Date accessed: 7/22/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4931775&version=63.0
   - File: `documentation.txt`
- File: Election results from South Carolina State Election Commission
    - Date accessed: 7/26/2021
    - Link: https://www.enr-scvotes.org/SC/64658/184701/en/select-county.html
    - Note: There’s an individual file for every county, in an .xls format. These will need to be downloaded separately, and opened in an excel-like program to extract the sheets with required races (Presidential, Senate) manually
- File: US FIPS Codes
    - File: `US_FIPS_Codes.csv`

## File processing:

`vest-sc-2016-validation.ipynb` is the script that is the basis of the validation report

# pdv-sc

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-south-carolina-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed.

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report.

## Raw from source

### Accessible files:

- File: SC VEST 2020 File
   - Date accessed: 11/26/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4789402&version=27.0
   - File: `sc_2020.zip`
- File: VEST Documentation File, 2020
   - Date accessed: 11/26/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=5431956&version=27.0
   - File: `documentation.txt`
- File: SC Precinct-Level Election Results, 2020
  - Date accessed: 11/29/2021
  - Link: https://www.enr-scvotes.org/SC/106502/Web02-state.264691/#/
  - Note: Selected 'SELECT COUNTY' tab, clicked on a county, select 'See Precincts Reporting', and downloaded 'Detail XLS'
- File: 2020 Redistricting Data Program Final Release (SC Partnership Shapefile)
  - Date accessed: 11/22/2021
  - Link: https://www.census.gov/geo/partnerships/pvs/partnership19v2/st45_sc.html

## File processing:

`vest-sc-2020-validation.ipynb` is the script that is the basis of the validation report

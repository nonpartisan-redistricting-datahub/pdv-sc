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

### Inaccessible files:
- File: SC Precinct Shapefiles
  - Note: Emailed Mapping Section of the South Carolina Revenue and Fiscal Affairs Office at analyticsmapping@rfa.sc.gov to request shapefiles on 12/02/21.

## File processing:

`vest-sc-2020-validation.ipynb` is the script that is the basis of the validation report

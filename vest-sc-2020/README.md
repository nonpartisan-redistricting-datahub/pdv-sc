# pdv-nm

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-new-mexico-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed.

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report.

## Raw from source

### Accessible files:

- File: NM VEST 2018 File
   - Date accessed: 08/17/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/UBKYRU/CW9QXO&version=45.0
   - File: `nm_2018.zip`
- File: VEST Documentation File, 2018
   - Date accessed: 8/3/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=5007790&version=45.0
   - File: `documentation.txt`
- File: NM Precinct-Level Election Results, 2018
  - Date accessed: 8/3/2021
  - Link: https://electionresults.sos.state.nm.us/default.aspx?eid=2698
  - Note: Selected 'EXPORT' and downloaded 'Precinct' data for each election
- File: NM Precinct Shapefiles
  - Date accessed: 09/17/2021
  - Link: https://www.nmlegis.gov/Redistricting/
- File: 2020 Redistricting Data Program Final Release (NM Partnership Shapefile)
  - Date accessed: 8/3/2021
  - Link: https://www.census.gov/geo/partnerships/pvs/partnership19v2/st35_nm.html
  - Note: Downloaded up to 5 at a time

## File processing:

`vest-nm-2018-validation.ipynb` is the script that is the basis of the validation report

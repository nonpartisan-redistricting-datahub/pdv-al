# vest-al-2017

[In progress] Our final validation report for this dataset is available [here]().

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## Raw from source

### Accessible files:

- File: VEST AL 2017 file
   - Date accessed: 6/8/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4751071&datasetVersionId=247478
   - File: `al_2017.zip`
- File: VEST documentation file, 2017
   - Date accessed: 6/8/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=4751070&version=5.1
   - File: `documentation.txt`
- File: Election Results, SOS 2017
   - Date accessed: 6/8/2021
   - Link: https://www.sos.alabama.gov/alabama-votes/voter/election-data
   - File: `2017-Special-General-PrecinctLevel.zip` (available upon request)
   - Note: selected '2017 Special General Election Results - Precinct Level', file contains a separate xls file for every county
- File: TIGER/Line VTD File, 2020 
   - Date accessed: 6/3/2021
   - Link: https://www2.census.gov/geo/tiger/TIGER2020PL/STATE/01_ALABAMA/01/
   - File: `tl_2020_01_vtd20.zip` (available upon request)
   - Note: VEST refers to their precinct shapefile source as 'the U.S. Census Bureau's 2020 Redistricting Data Program final release'. We believe this is the 2020 TIGER/Line VTD file. 
- File: Baldwin County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://baldwincountyal.gov/government/probate-office/elections/district-maps-voting-precincts
   - Note: they have a GIS department but only PDF map available on the website at that link. 
- File: Calhoun County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://www.calhouncounty.org/forms/Commission_Districts_Voting.pdf
   - Note: only finding a PDF map on their website. 
- File: Limestone County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://www.votelimestone.com/related-links/limestone-county-beat-map-with-polling-locations/
   - Note: only finding a PDF map on their website. 
- File: Madison County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://www.madisoncountyvotes.com/voter-resources/polling-locations/
   - Note: their interactive precinct map only shows the polling locations, but not precinct boundaries. 
- File: Mobile County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://www.mobilecountyal.gov/government/departments/administration/gis-mapping/election-maps/
   - Note: only finding a PDF map on their website. You can request GIS maps by mail request form. 
- File: Morgan County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://www.morgancountyelections.com/election-information/precinct-maps/
   - Note: there is an interactive arcgis precinct map, but there is no download option. Emailed Kate Terry, the Chief Clerk at kterry@morgancounty-al.gov. 
- File: St. Clair County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://stclair.maps.arcgis.com/apps/webappviewer/index.html?id=63f82a53398c49d38bf0e036e163e08a
   - Note: there is an interactive argis precinct map, but there is no download option. Emailed gissupport@stclairco.com
- File: Shelby County Shapefile
   - Date accessed: 6/4/2021
   - Link: https://maps.shelbyal.com/html5/
   - Note: there is an interactive arcgis precinct map, but there is no download option. Called the county IT Services (205-670-6981), and told to call back and ask for Victoria at 1pm (6/4/2021). 
- File: Talladega County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://www.talladegacountyal.org/departments/voter_registration/county_district_maps.php
   - Note: only finding a PDF map from 2013. Unlikely that they have a shapefile because the map looks like a scan of a physical copy. 
   
### Inaccessible files:

- File: County Canvass Report, 2017
   - Date accessed: 6/8/2021
   - Link: https://www.sos.alabama.gov/alabama-votes/voter/election-data
   - Note: it is not clear what file VEST is referring to that they used for county canvass reports. There is not a county level file for download on the SOS website, and there is nothing on the county website. 
- File: Blount County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://blountcountyal.gov/departments-services/elections-and-voting
   - Note: not finding any precinct maps on their website. 
- File: Cullman County Shapefile
   - Date accessed: 6/3/2021
   - Note: not finding a precinct map on their county website, there is a jpg map in the Cullman Times from 2014 at this link: https://www.cullmantimes.com/cullman-county-voting-precincts-map/image_0269f200-6231-11e4-9024-af8efe886238.html
- File: DeKalb County Shapefile
   - Date accessed: 6/3/2021
   - Note: not finding a precinct map on their website. 
- File: Franklin County Shapefile
   - Date accessed: 6/3/2021
   - Note: not finding any precinct maps on their website. 
- File: Jefferson County Shapefile
   - Date accessed: 6/3/2021
   - Link: https://jeffcoprobatecourt.com/elections/voting-precinct-changes/
   - Note: not finding a precinct map on their website, but they do list precinct changes over time. 
- File: Lee County Shapefile
   - Date accessed: 6/3/2021
   - Note: not finding a precinct map on their website. 
- File: Marengo County Shapefile
   - Date accessed: 6/3/2021
   - Note: not finding a precinct map on their website. 
- File: Marshall County Shapefile
   - Date accessed: 6/3/2021
   - Note: only finding the list of polling locations, but no precinct map on their website. 
- File: Tuscaloosa County Shapefile
   - Date accessed: 6/3/2021
   - Note: they have a list of polling locations, but not finding a precinct map on their website. 

## File processing:

`vest-al-2017-validation.ipynb` is the script that is the basis of the validation report
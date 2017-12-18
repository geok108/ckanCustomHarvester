# ckanCustomHarvester

customHarvester.py is a harvester for the CKAN data management system which was developed for the Cypriot open data portal http://www.data.gov.cy/ in 2016. This custom harvester was implemented as a part of a senior project.

Extensions like ckanext-geoview, ckanext-spatial and ckanext-harvest were integrated since the purpose of the system was to "harvest" datasets from the national portal. Each dataset's metadata should be converted to an ISO19139 xml file in order to be imported to the CKAN instance. Also, the national portal provided a CSV file with datasets' metadata which the harvester used in order to insert each dataset to the CKAN system.

The video below demonstrates the CKAN instance that was developed.
https://www.youtube.com/watch?v=EtvVwfUlZPg

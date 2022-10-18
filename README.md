# Enrich layers in ArcGIS Online (AGOL)

This Google Clould Platform (GCP) Cloud Function is designed to retrieve data from AGOL, enrich that data, and write it back to the original service. This script uses open source libraries and can be deployed to any platform which can run Python, eliminating the need for ArcPY to manipulate AGOL feature services. This script uses GeoPandas for the spatial operations and PyProj for reprojecting the data. 
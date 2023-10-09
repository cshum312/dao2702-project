# dao2702-project
Determine the most profitable sector to build a condominium development in Singapore

Description of Python Code for Data Cleaning:

1. Region and Geocoding: Takes data for addresses or location names (with postal code), and sorts it by region (using postal code) and coordinates by Nominatim from Geopy module.

2. Reverse Geocoding: Takes data without addresses to generate addresses to apply the "Region and Geocoding" code using the coordinates of the locations.

3. Distance Calculation Collective: Uses coordinates generated from sector data to calculate distances, with Geod in the pyproj module, from each sector to amenities and hdb.

Datasets extracted from data.gov.sg

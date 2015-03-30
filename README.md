# HubHacks2
Files for analyzing and creating network visulaizations of Boston City Data

These series of python files are used in connection with open data from the city of Boston to create JSON files.

The JSON files are used to create network visualizations of connections.

The following is a general method, but the specific use of the files depends on the structure of the data source:
1. Use the Stops_to_wards_classifier to output a csv file with the stop classified as a ward, neighborhood or town.
2. The csv files are then used to create an adjanceny matrix
3. The adjacency matrix is used in the _JSON_constructors to parse the files into a format easily read by the D3 library.

# MovieDataAnalysis
Using Python to collect, clean, analyze Movie Data collected from an API.
The IPYNB notebook contains the python code which is used to extract the data from an API, then pre-process it and analyze it.
Process:
1)From movies.csv, we get the movie's IMDB id, which is used to call the API http://www.omdbapi.com and get the data for each movie.

2)This data is stored in CollectedData.csv

3)This data is pre-processed, removing duplicates, handling missing/null values, deleting unwanted attributes/columns from the csv, etc and it is stored in CleanedData.csv

4)This cleaned data is then used to derive further analysis.

Project heavily uses Python Data Analysis Library.

# 12_No_SQL_Mongo_DB_Project

This project involved 2 parts related to UK Food establishments database where we needed to load, transform and then do some analysis and dataframe creation to answer pertinent questions. 

Part 1 (NOSQL_setup_starter.ipynb) involves using MongoDB/Pymongo in order to load a json file (establishments.json-  located in the resources folder) of food establishemnts into a database, and add an additional establishemnt to the database (using data from the database in order to add the appropirate business type to the establishment). After that, unncessary documents are removed based on region (Dover), and finally several columns are converted to approriate datatypes for analysis in the next part of the project.  

Part 2 (NOSQL_analysis_starter.ipynb) involves using Pymongo to conduct analysis on the database updated in part 1. Several questions are answered in order to view establishments given various criteria.  For each query, data is displayed using pretty print(pprint) and then saved as a Pandas DataFrame for future use

### Repo Strucuture/Notes
* Users can create the same database and walk through the database updating/set up and data analysis using the json file in the resources folder along with the 2 jupyter notebooks for setup and analysis. Code used to import the json data through a local terminal is provided at the top of the setup_starter jupyter notebook. 

### Code Source
No additional sources utilized for this project beyond in class assignments. 

### References
UK Food Standards Agency (https://www.food.gov.uk/). (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0(https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).

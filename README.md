# Kanika's ETL Project Report
## The focus of this project was centered around 2020 Covid Data and it's general information. This is the first time I am using this topic for my projects and it is very relatable to the current times.
### The two sources for this ETL project was a CSV file and a JSON file.


Extract: your original data sources and how the data was formatted (CSV, JSON, pgAdmin 4, etc).

- The CSV file and the JSON file was downloaded from two different website sources. 
- The CSV File focused more on the international states and covid deaths.
- The JSON file focused more on US states and more indepth covid information.

Transform: what data cleaning or transformation was required.

- The main data cleaning was to figure out how to merge the two tables, which I was going to do on Date
- When changing the date to datetime, the formats of the two dates came out compleltly different even though I was using the right code
- It took a while to figure out how to merge the two tables with the correct date format.

Load: the final database, tables/collections, and why this was chosen.

- The data was loaded into Postgres as the final database. 
- I found it best to create the engine connection from jupyter notebook to Postgres and have the available tables there.

# sql-projects

As a first responder, I was interested in analyzing a data set of fire incidents in Pittsburgh. I wanted to investigate the location, type, and frequency of fire calls, and see if there were any correlations with time of day, month, location, and fire type. After a quick google search I found this data set, “fire incidents that have been dispatched in Pittsburgh,” on the western pa data center site.
I began by cleaning and uploading the data to Bigquery by individual year, focusing on the most recent five years and filling in null values using addresses and area codes. I used common table expressions and subqueries with UNION ALL/DISTINC to combine the tables and eventually Percentages, COUNT and SUM with a table I created later.
After running queries on the data, I update created a dashboard on Tableau to visualize my results. I also looked into the specific areas of Wilkinsburg and Carrick and researched building types and populations.

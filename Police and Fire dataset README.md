For this project, I wanted to create a dataset with police incidents in the city of Pittsburgh and the previous data set I used for fire incidents.
Looking at both data sets there were some unique keys and primary keys I could use to join the data. The primary keys would be neighborhood and police zone. The secondary keys would be the year and date.
Before I could upload it to big query this required me to clean the data in excel. This was initially easy, as there were no duplicates and the blanks were things I wouldn’t be able to fill in so they would be cut if I decided to do a visual of the results. After cleaning I ran into some issues, the police dataset was a lot larger than the fire data set, so I had to go back and take a closer look since big query wouldn’t allow me to have the police zone as an integer in both sets. Back in excel, I found multiple rows that had words and abbreviations and changed them to a numerical values. Once I was able to join the tables I began queries on the data.
Some of the queries I did were just to get incident totals per year and then the entire dataset with joins. I also looked at the incidents by neighborhoods with joins. It's hard to find any correlations since the police incidents were significantly larger than the fire incidents.

Original datasets
fire: https://data.wprdc.org/datastore/dump/8d76ac6b-5ae8-4428-82a4-043130d17b02
police: https://data.wprdc.org/datastore/dump/044f2016-1dfd-4ab0-bc1e-065da05fca2e

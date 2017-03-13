*README*

Project Topic: Determining factors to reduce airplane bird strikes 

By: Shashank Naik

Code Files:
PigCode -- Contains the pig commands we executed to prepare and clean the several input data files. Besides cleaning and filtering data, we joined the Bird population data with the Routes file to get the geolocation content.

BirdYearCount.java -- A MapReduce Program to calculate the bird population variation for each the geo location spot co-ordinates per year inclusive of all bird species.

HiveCode -- Contains the Hive commands we executed to prepare data for MapReduce, perform cross product and massage the data for cross product. Also includes commands for execution on NYU's Dumbo cluster.

HiveCodeCompare -- Contains the Hive commands we executed compare our final result with a bird strike data.

UPDATES:
1) updated HiveCode file, included the cross product and data cleanup which was precursor for the analytics
2) Hive code was run on NYU's Dumbo HPC cluster, this code is updated in the HiveCode file.
3) updated the mapreduce logic to now calculate per year bird population location based statistics
4) Added HiveCodeCompare which contains commands for comparing the birdstrike data to the data we processed
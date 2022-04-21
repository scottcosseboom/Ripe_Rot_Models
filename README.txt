The .jrp files contains formulas/scripts for predicting ripe rot. Each script requires a jmp data table with two variables (columns) named "Temp" and "WD: 
"Temp" is temperature in degrees Celcius
"WD" is wetness duration in hours

If the .jrp file is opened, then all scripts can be run on a jmp data table with these two variables. 
This will create new variables in the data table (columns).
Some of these column labels match the labels in the manuscript.
The data in each column is the ripe rot risk probability from the environmental risk models.

The "Example_data_set.jmp" file contains example data in columns named "Temp" and "WD". The .jrp scripts can be ran on this data table as an example.
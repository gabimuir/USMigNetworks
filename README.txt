# US Population Movement Visualizations

## Project Description and Aims

Originally created for 'Structure and Dynamics of Complex Networks' course, Fall 2017. 
Updated July 2019 (with new pandas skills). 

### The dataset
The data for this project is collected from the American Community Survey (ACS), the 2011-2015 collection. This data can be accessed through https://www2.census.gov/programs-surveys/acs/data/pums/2015/5-Year/ (as of 7/18/19). In Fall of 2017, I took the dataset and cleaned it, but lost the original file. It looks as though the census bureau packages data differently than it did back then, so it may be more difficult to replicate my entire project. To clean the data, I used bash scripting (because I didn't know about how easy it is to use pandas!)

### Overview
The dataset is from the American Community Survey, which asks for people's current addresses and the address they had the previous year. Each location (state, county, or non-US country) is considered a 'node', and each individual's move is an 'edge' in a networks framework. It's interesting to compare the differences between different groups moving different places.
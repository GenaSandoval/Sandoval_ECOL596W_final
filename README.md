# Sandoval_ECOL596W_final

## Bat Species Diversity Analysis

#### An R script for multiple analyses that can be used to reveal trends of species diversity and numbers in select sampling sites.

### Requirements
-Updated version of R

-Github account to fork and clone the repo

### Installation
You will need to have the following packages installed:

library(readr)

library(ggplot2)

library(tidyverse)

library(dplyr)

library(leaflet)

library(vegan)

### Script
Script: https://github.com/GenaSandoval/Sandoval_ECOL596W_final.git/Sandoval_final_script.R

### Data set
Data: https://github.com/GenaSandoval/Sandoval_ECOL596W_final.git/datasets/raw_bat_collection_data_2024.csv

Note the following files will be found in the same directory:

terms_key.csv is a simple text file explaining the abbreviated terms found in the metadata file.

site_info.csv gives details on the type of habitat each site is and their disturbance level based on human activity and natural event occurrences.

### Outputs
Figures: https://github.com/GenaSandoval/Sandoval_ECOL596W_final.git/figures

### Main Research Question
How do environmental variables (e.g., habitat type, disturbance levels) influence bat species diversity and abundance across different roosting sites in Tucson, AZ?

### Experimental design
#### Study: 
Our study focus is on genomic adaptation in Myotis bats but our sampling efforts are focused on previously recorded bat roosting sites in Tucson, AZ, which vary in habitat type and disturbance levels. These sites were selected based on their accessibility, and their believed presence of specific bat species.

#### Data Collection: 
The data comes from fieldwork conducted at various roosting sites, with additional information provided in accompanying metadata files (e.g., site_info.csv, terms_key.csv). Bats were captured at each site through mist netting above a body of water. The main data set includes categories such as location, date, and species counts. Trait measurements is limited to our study species of Myotis mainly due to time restraints and efficiency of processing. We have also recorded associated environmental variables for each site and made note of the possible disturbance of human activity.

#### Variables:
Species Diversity: Number of species observed at each site (species richness).
Environmental Variables: Habitat type (e.g., urban, desert, riparian), disturbance level (e.g., human activity, natural events), and GPS coordinates (latitude and longitude) for each site.

#### Statistical Methods: 
Species diversity will be correlated with environmental variables through various methods, including:

Canonical Correspondence Analysis (CCA) to examine the relationship between species composition and environmental factors.
Principal Component Analysis (PCA) for dimensionality reduction.
Linear models to predict species count based on environmental variables.
Control Variables: Disturbance level and habitat type will be treated as independent variables to assess their influence on species diversity, while controlling for other factors such as location.

#### Experimental limitations
Disclaimer: This data set was not intentionally created for this type of project. The data comes from our field records of every bat we caught within the 2024 sampling season. These records are typically transformed into generalized counts of how many individuals of a species was caught in a specific jurisdiction for government agency data reports. Data in some columns are limited as we are only required to report a minimum of the location and species for each individual captured but we try to record the age, sex, reproductive status, and time for each individual as well. The number of sites is also limited as we are restricted to local roosts based on our permits. Overall, this data set is very limited but should still be sufficient enough to do simple analyses.


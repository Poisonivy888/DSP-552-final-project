README
Overview
This project analyzes stroke and related health data using R, focusing on filtering and visualizing specific categories from large datasets of stroke, and diabetes data in Malaysia and the UK. The workflow utilizes the tidyverse and dplyr packages for data manipulation and includes code for filtering datasets based on predefined category lists.

Requirements
R (version 4.0 or higher recommended)

R packages:

tidyverse

dplyr

googlesheets4

openintro

Data Sources
Data is loaded from Google Sheets using the googlesheets4 package. Have acesses to Google Sheets and have authenticated your R session to read them.

Install required packages:
install.packages(c("tidyverse", "dplyr", "googlesheets4", "openintro"))

Load the libraries at the top of your R script:

library(tidyverse)
library(dplyr)
library(googlesheets4)
library(openintro)
Read in your data using read_sheet() from googlesheets4.

Run the code.

Proceed with analysis or visualization as needed.


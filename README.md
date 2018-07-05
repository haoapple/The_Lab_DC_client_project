# The_Lab_DC_client_project
A team repo to client project with The Lab @ DC (GA-DSI)

# Table of Contents
### 01.Data.ipynb - Read in all outside details, data sets are large
### 02.EDA.ipynb - Basic Breakdown and view of the datasets
### 03.Feature Engineering.ipynb - Preparing data for modeling
### 04.Modeling.ipynb - Classification and regression modeling
### 05.Graphs.ipynb - Few random graphs to show a little bit more information
### 98.Housing_dataset.ipynb - Future data that we hope to break down
### Assets - Contains data once first notebook is run
### Archive - Old notebooks

# Settings
  1) Make sure you have `.gitignore` in your local repo by adding this line: `assets/csr/*`
  2) Make sure you install and track Git Large File Storage(read more: https://git-lfs.github.com)
    - `git lfs install`, `git lfs track "*.csv"`
    - this will create  `.gitattributes` in your local repository.

# Sources: datasets
  1) ShotSpotter Data, Metropolitan Police Department
    https://mpdc.dc.gov/publication/shotspotter-data-disclaimer-and-dictionary

    - ShotSpotter Data (2014-2017): https://mpdc.dc.gov/sites/default/files/dc/sites/mpdc/publication/attachments/ShotSpotter%20Data%2014-17%20180213_0.xlsx
    - ShotSpotter Data (Q1 2018): https://mpdc.dc.gov/sites/default/files/dc/sites/mpdc/publication/attachments/ShotSpotter%20Public%20Data%20Q1%202018.xlsx

    - fetched at 12:30 EST, June 18th, 2018

  2) City Service Requests Data, Open Data DC
    http://opendata.dc.gov/

    - 2014: http://opendata.dc.gov/datasets/city-service-requests-in-2014
    - 2015: http://opendata.dc.gov/datasets/city-service-requests-in-2015
    - 2016: http://opendata.dc.gov/datasets/city-service-requests-in-2016
    - 2017: http://opendata.dc.gov/datasets/city-service-requests-in-2017
    - fetched at 12:30 EST, June 18th, 2018

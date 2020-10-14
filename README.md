# Network-Analysis-of-Bike-Sharing-System-
This project identifies communities and interactions and if they exhibit relationships with the demographics of an area for Citi Bike in New York

## DataSet
The dataset used for this project is publically available and can be downloaded from the Citi Bike website: https://www.citibikenyc.com/system-data

## Setup
Detailed Instructions before executing each folder is provided below:

1_Exploratory Data Analysis
- Save the downloaded source data file into the 'Input File' folder
- Execute the notebook labelled as 'Master File - EDA + Network Structure.ipynb'
- The outputs are stored as .CSV files under the sub-folder 'Clean_data_files_Community' which will be used as input for '2_Community Detection'
- The outputs for folium plots are stored under the sub-folder 'Folium_Output'.

2_Community Detection
- Replace the path directory to match with your system's location for Basemap package installed before executing further
- First, execute the notebook labelled as 'Community detection.ipynb'
- Next, execute the notebook labelled as 'Centrality on Communities.ipynb'
- The community detection output files in html format can be found under the sub-folder 'Output files_for_Community'

3_Network Classification
- Save the downloaded source data file into the 'Input File' folder
- Execute the notebook labelled as 'Network Classification.ipynb'
- Misc_Files are used for intermediate code operations


## FAQ/Troubleshoot
Please contact oishee2202@gmail.com for more information

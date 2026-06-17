# site-mapper 

&copy; 2026 Simon Reynaert

This repository includes the code for generating maps and datasets of sites where target species occur in Flanders. 
The main workflow can be found in the **main_workflow.ipynb** file. The script first pulls in all occurrences from GBIF of a species of interest and overlays them with the target areas (here: natuur management kaart), only keeping the areas where species are present. The output contains both an interactive .html map as well as a .csv file with all areas and occurrences of interest.

This repository is a work in progress.

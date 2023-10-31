# highlands-parkside-analysis
An analysis of work orders at the Highlands @ Mayfield and Parkside @ Mayfield neighborhoods.

# Background
These two neighborhoods have water and wastewater service provided by the City of Georgetown. However, while we provide the service for wastewater we do not own the infrastructure, it is owned by the Highlands Special Utility District.  

This repo contains a notebook for analyzing our work order volume and associated cost in these neighborhoods to determine if we our billing is adequate.  This was in response to ticket # WAT-51 for Chelsea.  

# Notebooks
The highlands_parkside_workorders.ipynb notebook contains the complete pipeline for analyzing these two neighborhoods, from extracting the data from the EAM system to the final visualizations.

The joining_gis_stuff.ipynb notebook is a simple workflow for extracting service data from the GIS database and the totality of the R5Objects table from the EAM db for use in the final analysis.

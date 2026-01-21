# WQP-downloader

Script to pull down, clean, and manipulate WQP data in various ways:
* Part 1: Finding site information (i.e., MonitoringLocationIdentifiers, coordinates, etc.) based on Project IDs.
* Part 2: Finding data based on list of MonitoringLocationIdentifiers.
* Part 3: Finding data based on NPS unit codes (i.e., park boundaries).
* Part 4: Finding data based on IMD network (i.e., boundaries of all parks within a network).
* Part 5: Correcting data coordinates for mapping, creating shapefile of all points for easy import into ArcGIS Pro.
* Part 6: Determining which NPS unit code/IMD network a location is in/closest to. 
* Part 7: Finding site data based on organization ID.

Required: 
* WQP Code > WQP_loop_code.Rmd: WQP R code
* WQP Code > data_input: all associated files needed, including park/network/wild and scenic river boundaries, sample data, list of IMD project IDs (last updated Feb 2025 from Dean Tucker).

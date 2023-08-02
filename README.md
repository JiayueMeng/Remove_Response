**remove_response:** Automatically attach and remove responses for data, and save the modified files to your output folder. Abnormal file collection and troubleshooting process included. 
**create_inventory:** Automatically create an inventory for a station for a specific time range. Only need to input Network, Station, and Time.
**down_sample:** Downsample all data in folders.

# Remove_Response

## Data Download
### Pacific OBS Networks
**Python files and bash scripts to download data for different networks parallelly with name format "Station_Network":** /scratch/tolugboj_lab/Prj4c_OJP/2_Data/OJ/fetch_NOISE-master/script_for_download_parallelly  
**Downloaded raw data:** /scratch/tolugboj_lab/Prj4c_OJP/2_Data/OJ/fetch_NOISE-master/script_for_download_parallelly/output  

### Island Networks
**Python files and bash scripts to download data for different networks parallelly with name format "Station_Network":** /scratch/tolugboj_lab/Prj4c_OJP/2_Data/OJ/fetch_NOISE-master/island_networks  
**Downloaded raw data:** /scratch/tolugboj_lab/Prj4c_OJP/2_Data/OJ/fetch_NOISE-master/island_networks/output_BHZ12  

**All data removed response:** /scratch/tolugboj_lab/Prj4c_OJP/2_Data/OJ/fetch_NOISE-master/removed_response_output  
**All data removed response and downsampled:** /scratch/tolugboj_lab/Prj4c_OJP/2_Data/OJ/fetch_NOISE-master/removed_response_output/all_stations_downsample  

**OBS station lists in Pacific Ocean:** /scratch/tolugboj_lab/Prj4c_OJP/2_Data/OJ/fetch_NOISE-master/OBS_pacific_stations

## Modified MATnoise
**MATnoise files after debugging:** /scratch/tolugboj_lab/Prj4c_OJP/2_Data/OJ/MATnoise-master  
**PSD plot (a4) with classified means (connections between island and island, ocean and island, and inside networks):** /scratch/tolugboj_lab/Prj4c_OJP/2_Data/OJ/MATnoise-master/a4_plot_ccfPSD_classified.m  

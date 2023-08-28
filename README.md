[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8205655.svg)](https://doi.org/10.5281/zenodo.8205655) 

# GES DISC Tutorials

A place to find tutorials on how to use GES DISC tools, services, and data.

Most tutorials in this repository take the form of python notebooks. Jupyter is a very popular version of python notebooks, and is used extensively by the GES DISC team.

| Notebook  | Summary | Services and Tools |
| ------------- |-------------|:-------------:|
|[How to Access GES DISC Data Using Python](notebooks/How_to_Access_GES_DISC_Data_Using_Python.ipynb) | There are multiple ways to work with GES DISC data resources using Python. For example, the data can accessed using techniques that rely on a native Python code. Still, there are several third-party libraries that can further simplify the access. In the sections below, we describe four techniques that make use of Requests, Pydap, Xarray, and netCDF4-python libraries. | |
|[How to Generate Earthdata Prerequisite Files](notebooks/How_to_Generate_Earthdata_Prerequisite_Files.ipynb) | This notebook demonstrates how to generate three Earthdata prerequisite files (.netrc, .urs_cookies, .dodsrc) needed to access the GES DISC archives manually, or through Python.| |
|[How to Access MERRA2 Using OPeNDAP with Python3 and Calculate Weekly from Hourly Data ](notebooks/How_to_Access_MERRA2_Using_OPeNDAP_with_Python3_Calculate_Weekly_from_Hourly.ipynb) | This notebook is based on Python3 and demonstrates how to remotely access the Modern-Era Retrospective analysis for Research and Applications, Version 2 (MERRA-2) hourly files via OPeNDAP and analyze data such as resample hourly files into daily, weekly, and monthly files and calculate their corresponding statistics, e.g., mean, sum, maximum, and minimum. | |
|[How to Read IMERG Data Using Python ](notebooks/How_to_Read_IMERG_Data_Using_Python.ipynb)| This notebook shows how to read data from the Global Precipitation Measurement (GPM) mission's IMERG dataset using Python. |  |
|[How to Read and Plot NetCDF MERRA-2 Data in Python ](notebooks/How_to_Read_and_Plot_NetCDF_MERRA-2_data_in_Python.ipynb)| This How-To shows how to read and plot NetCDF4 data from the Modern-Era Retrospective analysis for Research and Applications version 2 (MERRA-2) using Python. |  |
|[How to Use the Web Services API for Dataset Searching ](notebooks/How_to_Use_the_Web_Services_API_for_Dataset_Searching.ipynb) | This example code demonstrates how to use the API to search GES DISC data collections.  | |
|[How to Use the Web Services API for Subsetting ](notebooks/How_To_Use_the_Web_Services_API_for_Subsetting.ipynb) | This example code demonstrates how to use the API to subset GES DISC data collections.  | |
|[How to Use the Web Services API for Subsetting MERRA-2 Data](notebooks/How_to_Use_the_Web_Services_API_for_Subsetting_MERRA-2_Data.ipynb) | The example code provided below demonstrates three examples on how to use the API to submit an asynchronous request to the GES DISC Subsetting Service in order to obtain subsets of the Modern-Era Retropsective analysis for Research and Applications, Version 2 (MERRA-2). | |
|[How to Use the Web Services API to Validate Point Measurements ](notebooks/How_to_Use_the_Web_Services_API_to_Validate_Point_Measurements.ipynb) | This notebook demonstrates how to use the GES DISC API to retrieve Level 2 subsets of satellite data for the purpose of validation or comparison to ground-based measurements using Python.  | |
|[How to Access the Hydrology Data Rods Time Series API Using Python](notebooks/How_to_Access_the_Hydrology_Data_Rods_API_Using_Python) | This notebook describes accessing the Hydrology Data Rods Time Series API using Python.| |
|[How to find the max precipitation value of a Region of Interest (ROI) using an ArcGIS image service](notebooks/How_to_Find_the_Max_Precipitation_Value_of_a_ROI_Using_an_ArcGIS_Image_Service.ipynb) | This notebook demonstrates how to calculate and view the maximum precipitation rate value from the GPM IMERGHHE ArcGIS Image Service. | |
|[How to Find and Plot Level 2 Data from Multiple Granules on a Map using Python](notebooks/How_to_Find_and_Plot_Level2_Data_from_Multiple_Granules_on_a_Map_Using_Python.ipynb) | This notebook demonstrates how to aggregate and plot Level 2 granules on a map using Python. | |
|[How to Remotely Access MERRA-2 with Python3 and Calculate Monthly Average Surface PM2.5 for World Countries](notebooks/How_to_MERRA2_PM25_Monthly.ipynb) | This notebook demonstrates how to access MERRA-2 from the THREDDS Data Server, before calculating monthly average surface PM2.5 values for various world countries. | |
|[How to Calculate and Plot Wind Speed using MERRA-2 Wind Component Data using Python](notebooks/How_to_calculate_and_plot_wind_speed_using_MERRA-2_wind_component_data.ipynb) | This tutorial demonstrates how to calculate and plot hourly wind speed using the northward and eastward wind component variables with MERRA-2 data using Python. | |
|[How to Plot Horizontal and Vertical Slices of Swath Data with Python Using GPM_2ADPR](notebooks/How_To_Plot_Horizontal_and_Vertical_Slices_of_Swath_Data_with_Python_Using_GPM_2ADPR.ipynb) | This notebook demonstrates how to use Python for plotting horizontal spatial maps and vertical cross sections (also known as curtain plots) of the Level 2 product [GPM_2ADPR](https://disc.gsfc.nasa.gov/datasets/GPM_2ADPR_07/summary?keywords=GPM_2ADPR_07). | |
|[How to Calculate Greenhouse Gas Growth Rates using Python](notebooks/How_To_Calculate_Greenhouse_Gas_Growth_Rates.ipynb) | This notebook demonstrates how to calculate the growth rate, also known as rate of change, for greenhouse gases using Giovanni and Python. | |

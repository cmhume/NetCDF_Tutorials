# NetCDF_Tutorials
This is a collection of tutorials on how to use python3 and jupyter notebook to analyze NetCDF files.

## Requirements

To view NetCDF files in Jupyter Notebook the following libraries were installed to the environment:


* Cartopy - https://scitools.org.uk/cartopy/docs/latest/installing.html
* Geos - https://libgeos.org/
* PROJ - https://proj.org/
* PyProj - https://github.com/pyproj4/pyproj/
* Shapely - https://shapely.readthedocs.io/en/stable/project.html#installing-shapely
* PyShp - https://pypi.org/project/pyshp/


## What is a NetCDF file?


NetCDF - Network Common Data Form (NetCDF) was developed by UniData for recording and sharing multidimensional scientific data.


File endings = .nc, .nc4


## GES DISC Tutorial - How to read and plot NetCDF MERRA-2 data in Python


Tutorial Link:

https://disc.gsfc.nasa.gov/information/howto?title=How%20to%20read%20and%20plot%20NetCDF%20MERRA-2%20data%20in%20Python

Jupyter Notebook [Link](https://github.com/cmhume/NetCDF_Tutorials/blob/b5338d65ba590eab4489eefd4667228a399fe58f/nc_tutorials.ipynb)

Data Source:

Global Modeling and Assimilation Office (GMAO) (2015), MERRA-2 tavgM_2d_slv_Nx: 2d,Monthly mean,Time-Averaged,Single-Level,Assimilation,Single-Level Diagnostics V5.12.4, Greenbelt, MD, USA, Goddard Earth Sciences Data and Information Services Center (GES DISC), Accessed: 12/6/2021, 10.5067/AP1B0BA5PD2K

File Name: 

MERRA2_300.tavgM_2d_slv_Nx.201001.nc4


### Download Data

1.  Register for an Earthdata account here: https://urs.earthdata.nasa.gov/home
2.  Search for ‘M2TMNXSLV_5.12.4’ dataset and click on link
3.  Download file named 'MERRA2_300.tavgM_2d_slv_Nx.201001.nc4'


### Install Cartopy and NCD4 libraries in the coding environment


### Import dependencies


### Open and read file


### Plot Contour Maps with matplotlib and Cartopy

![Screenshot (478)](https://user-images.githubusercontent.com/78699521/145663381-bd9818aa-b8b6-4501-927b-e9364af045fc.png)


![Screenshot (479)](https://user-images.githubusercontent.com/78699521/145663383-e1a75477-7255-4cc9-a089-09bc08652a86.png)

### Close file


## Notebook Tutorial



### Further Resources

https://www.unidata.ucar.edu/software/netcdf/docs/index.html#what_is_netcdf

https://www.unidata.ucar.edu/software/netcdf/?_ga=2.149285044.306078577.1639075559-2065963898.1639075559


https://www.nodc.noaa.gov/data/formats/netcdf/v2.0/

https://www.unidata.ucar.edu/software/netcdf/examples/files.html

https://nsidc.org/support/faq/what-netcdf

https://pro.arcgis.com/en/pro-app/latest/help/data/multidimensional/essential-netcdf-vocabulary.htm


https://psl.noaa.gov/data/gridded/whatsnetCDF.html







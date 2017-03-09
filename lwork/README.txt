README.txt

The files contained in this directory may be used to plot Open-File 97-289 "Digital 
Compilation of Landslide Overview Map of the Conterminous United States".

This directory contains the following files:

These files are in ARC/INFO export format and Geographic projection

slidedd.e00       landslide polygons
hydrodd.e00       U.S. hydrography derived from Digital Chart of the World
coastdd.e00       U.S. coastline derived from 1:100,00 USGS Digital Line Graphs
countydd.e00      U.S. counties derived from 1:100,00 USGS Digital line Graphs

These files are in ARC/INFO export format.  The shadeset and lineset need to be
installed by the user to plot the map.

slide.lut.e00     lookup table 
inkcolor.lin.e00  lineset
inkcolor.shd.e00  shadeset

The aml, landslide.aml, takes the ARC/INFO export files, coastdd.e00, hydrodd.e00, 
slidedd.e00, countydd.e00 and converts them to ARC/INFO coverages, projects
them into Albers Equal Area and plots "Digital Compilation of Landslide
Overview Map of the Conterminous United States".

Note:

These are very large data sets approximately 120 megabytes in .e00 files. The output
.gra file is over 16 megabytes.


Abstract:

This dataset consists of polygons enclosing areas of landslide incidence and
susceptibility for the conterminous United States.

Purpose:
     
The purpose of this dataset is to give the user a general indication of areas
that may be susceptible to landsliding. It is not suitable for local planning
or site selection.
     
Procedures Used:

The dataset was digitized manually from the original mylar manuscripts.
Except for minor changes in some polygons that enclose areas along canyon rims
mesa tops, no updates or corrections to the original were made. 1 : 1,000,000
Digital Chart of the World was used to close the polygons at the coastlines and
international boundaries.
 
Use Constraints:

The use of these data should be limited to the digitized scale 1 : 3,750,000.
 
Data Set Credit:

The original map was compiled by the above authors. Credit should also be given
to the Graphics Lab, Geologic Hazards Team, Geologic Division, Golden, Colorado.
This work was supported in part by an appointment to the U.S. Geological Survey
Earth Sciences Program administered by Oak Ridge Associated Universities.
 
Update:

10/27/97 shadeset and lineset export files updated, minor fix in landslide.aml. 


Contact: 

Jonathan Godt
U.S. Geological Survey
National Landslide Information Center
(303) 273-8626 
jgodt@usgs.gov
http://geohazards.cr.usgs.gov/landslide.html


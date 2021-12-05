# MS4 Regulated Areas 2019-2020

<img
    src="https://www.cascobayestuary.org/wp-content/uploads/2014/04/logo_sm.jpg"
    style="position:absolute;top:10px;right:50px;" />


GIS data showing MS4 regulated Areas in the Casco Bay Region

# Introduction
This archive includes geospatial data and a simple map showing the location
of MS4 regulated areas in the Casco Bay region, in Maine.

Curiously, areas regulated under the U.S. Clean Water Act's "Municipal 
Separate Storm Sewer System" program (known as the "MS4" program) are not 
based on municipal boundaries or even on local land use, but on whether the 
areas are designated by the U.S. Census as part of an "urbanized area". These
maps show how those designated areas have been interpreted by Maine DEP 
to identify areas in the MS4 program.

Boundaries of the MS4 areas will change once results fo the 2020 census have 
been incorporated into Maine's regulatory processes. 

# Statement of Purpose
CBEP is committed to the ideal of open science.  Our State of the Bay data
archives ensure the science underlying the 2020 State of the Bay report is
documented and reproducible by others. The purpose of these archives is to
release  data and data analysis code whenever possible to allow others to
review, critique, learn from, and build upon CBEP science.

# Archive Structure
CBEP 2020/2021 State of the Bay data analysis summaries contain a selection of 
data,  data analysis code, and visualization code as used to produce 
results shared via our most recent State of Casco Bay report. Usually, these
archives are organized into two or three folders, including the following:

- `Data`  folder.  Contains data in simplified or derived form as used in our
data  analysis.  Associated metadata is contained in related Markdown documents,
usually `DATA_SOURCES.md` and `DATA_NOTES.md`.

- Analysis.  Contains one or more R Notebooks proceeding through the principal
data analysis steps that underpin SoCB reporting. To simplify the archives,
much preliminary analysis, and many analysis "dead ends" have been omitted. 

- Graphics.  Contains R Notebooks stepping through development of graphics, and
also copies of resulting graphics, usually in \*.png and \*.pdf formats.  These
graphics may differ from graphics as they appear in final State of the Bay
graphical layouts. Again, most draft versions of graphics have been omitted for 
clarity.

# Summary of Data Sources
All data included here are derived from public data released by Maine's 
Department of Environmental Protection:

GIS data delineating current MS4 areas is available from Maine DEP
[website](https://www.maine.gov/dep/gis/datamaps/). 

The specific data here is titled "Municipal Separated Storm Sewer Systems 
Regulated Areas (5/27/2014)"
A link was provided on the DEP website for downloading a zipped shapefile at
the following address in 2021:
(https://www.maine.gov/dep/gis/datamaps/lawb_municipal_separate_stormwater_sewer_systems/municipal_separate_stormwater_sewer_systems_regulated_area_shapes.zip)

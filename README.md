## Courses for improve hydrologyst skills


<div>

This personal repository is a compiled of courses and relevant information that I consider that will improve to *Hydrologists skills*. The main topics are: 
- GIS with R and python.
- Geostatistics.
- Database manage.

Based on [CRAN Task View: Hydrological Data and Modeling](https://github.com/ropensci/Hydrology).
See also [Riccardo Rigon’s excellent list](https://abouthydrology.blogspot.com/2012/08/r-resources-for-hydrologists.html) of hydrology-related R tools and resources. Some Python related resources can be found [here](https://abouthydrology.blogspot.com/2016/11/python-resources-for-hydrologists.html) and [here](https://github.com/raoulcollenteur/Python-Hydrology-Tools)

If you have any comments or suggestions for additions or improvements for this Task View, go to GitHub and [submit an issue](https://github.com/caemillan/Courses/issues) , or make some changes and [submit a pull request](https://github.com/caemillan/Courses/pulls) . If you can’t contribute on GitHub, [send Carlos Millan an email](mailto:cmillanarancibia@gmail.com) .  If you have another consideration be free to comment it.

 ## Courses to begin with Python as GIS
 
 - [Geo-Python](https://geo-python-site.readthedocs.io/en/latest/): The Geo-Python course teaches you the basic concepts of programming and scientific data analysis using the Python programming language in a format that is easy to learn and understand (no previous programming experience required). Each lesson is a tutorial with specific topic(s) where the aim is to gain skills and understanding how to solve common data-related tasks using Python. Geo-Python is organized by the [Department of Geosciences and Geography](https://www.helsinki.fi/en/faculty-science/faculty/geosciences-and-geography) at the University of Helsinki.
 
 - [Introduction to Earth Data Science](https://www.earthdatascience.org/courses/intro-to-earth-data-science/):Introduction to Earth Data Science is an online textbook for anyone new to open reproducible science and the Python programming language. There are no prerequisites for this material, and no prior programming knowledge is assumed.
This textbook is designed for the Earth Analytics Bootcamp for the Earth Data Analytics Professional Certificate taught by instructors at CU Boulder.
 
 ## Specialized courses with Python
 - [Use Data for Earth and Environmental Science in Open Source Python](https://www.earthdatascience.org/courses/use-data-open-source-python/): Use Data for Earth and Environmental Science in Open Source Python is an intermediate and multidisciplinary online textbook that addresses major questions in Earth science and teaches students to use the analytical tools necessary to undertake exploration of heterogeneous “big” scientific data.
This textbook assumes that readers have reviewed the Introduction to Earth Data Science textbook or are familiar with the Python programming language, Jupyter Notebook, and git/GitHub.
This textbook is designed for the Earth Analytics Python course for the Earth Data Analytics Professional Certificate taught by instructors at CU Boulder.
 
 - [GeoPython-AutoGIS](https://automating-gis-processes.github.io/site/): Automating GIS-processes -course teaches you how to do different GIS-related tasks in Python programming language. Each lesson is a tutorial with specific topic(s) where the aim is to learn how to solve common GIS-related problems and tasks using Python tools. We are using only publicly available data which can be used and downloaded by anyone anywhere. We also provide a computing environment which allows you to instantly start programming and trying out the materials yourself, directly in your browser (no installations needed).
 
 
 ## Mapping your work
 
  - [Geospatial Techniques in R](https://stefanjuenger.github.io/gesis-workshop-geospatial-techniques-R/): When social scientists aim to use geospatial data, they must rely on specialized tools, called Geographic Information Systems (GIS). However, the world of GIS is complicated, since often only foreign software solutions provide a comprehensive collection of available geospatial techniques. Fortunately, nowadays, social scientists can also use the statistical software R as a proper GIS. Thus, this course will teach how to exploit R and apply its geospatial techniques in a social science context. We will learn about the most common data formats, their quirks, and their application. Most importantly, the course will present data sources, how to get the data and wrangle them for further analysis. Central are geospatial operations, such as cropping, aggregating or linking data. Finally, what is of interest for many researchers is creating maps, which is also straightforward in R.
 

 ## Data Retrieval

**Hydrological data sources (surface water/groundwater quantity and quality)**

  - [AWAPer](http://cran.rstudio.com/web/packages/AWAPer/index.html): AWAPer allows efficient extraction of daily catchment average precipitation, Tmin, Tmax, vapour pressure, solar radiation and then estimation of areal potential evaporation (Morton’s) for anywhere in Australia. Spatial measures are also derived (eg spatial daily variance). For technical details see Peterson et al. (2019).
 
**Meteorological data (precipitation, radiation, temperature, etc - including both measurements and reanalysis)**

  - [climate](http://cran.rstudio.com/web/packages/climate/index.html): Automatize downloading of meteorological and hydrological data from publicly available repositories: OGIMET, University of Wyoming - atmospheric vertical profiling data, and Polish Institute of Meterology and Water Management - National Research Institute. T

  - [clifro](http://cran.rstudio.com/web/packages/clifro/index.html): A web portal to the New Zealand National Climate Database of around 6,500 climate stations. See <https://cliflo.niwa.co.nz/> for more information.

 
## Data Analysis

**Data tidying (gap-filling, data organization, QA/QC, etc)**

  - [<span class="GitHub">driftR</span>](https://github.com/shaughnessyar/driftR/): A tidy implementation of equations that correct for instrumental drift in continuous water quality monitoring data using one or two standard reference values. The equations implemented are from [Hasenmueller (2011)](http://doi.org/10.7936/K7N014KS) .

**Meteorology (functions for working with meteorological and climate data)**

  - [Evapotranspiration](http://cran.rstudio.com/web/packages/Evapotranspiration/index.html): Functions to calculate potential evapotranspiration (PET) and actual evapotranspiration (AET) from 21 different formulations including Penman, Penman-Monteith FAO 56, Priestley-Taylor and Morton models.

  - [humidity](http://cran.rstudio.com/web/packages/humidity/index.html): Functions for calculating saturation vapor pressure (hPa), partial water vapor pressure (Pa), relative humidity (%), absolute humidity (kg/m^3), specific humidity (kg/kg), and mixing ratio (kg/kg) from temperature (K) and dew point (K). Conversion functions between humidity measures are also provided.

**Other**

  - [berryFunctions](http://cran.rstudio.com/web/packages/berryFunctions/index.html): Draw horizontal histograms, color scattered points by 3rd dimension, enhance date- and log-axis plots, zoom in X11 graphics, trace errors and warnings, use the unit hydrograph in a linear storage cascade, convert lists to data.frames and arrays, fit multiple functions.

 **Spatial data processing**

The CRAN [Spatial](Spatial.html) Task View gives an overview of packages to be used in R to read, visualise, and analyse spatial data. See also the ROpenSci [MapTools Listing](https://github.com/ropensci/maptools) .

  - [<span class="GitHub">lumpR</span>](https://github.com/tpilz/lumpR/): Functions for a semi-automated approach of the delineation and description of landscape units and partition into terrain components. It can be used for the pre-processing of semi-distributed large-scale hydrological and erosion models using catena-representation (WASA-SED, CATFLOW). GitHub only package.

## Modeling

**Process-based modeling (scripts for preparing inputs/outputs and running process-based models)**

See also the [RHydro project](https://r-forge.r-project.org/R/?group_id=411) on R-forge and the [Astagneau et al. (2021) HESS](https://doi.org/10.5194/hess-25-3937-2021/) paper discussing R packages for Hydrology modelling.

  - [airGR](http://cran.rstudio.com/web/packages/airGR/index.html): Hydrological modelling tools developed at INRAE-Antony (HYCAR Research Unit, France). The package includes several conceptual rainfall-runoff models (GR4H, GR5H, GR4J, GR5J, GR6J, GR2M, GR1A) that can be applied either on a lumped or semi-distributed way. A snow accumulation and melt model (CemaNeige) and the associated functions for their calibration and evaluation.

 **Statistical modeling (hydrology-related statistical models)**

The [Environmetrics](Environmetrics.html): Task View gives an overview of packages used in the analysis of environmental data, encompassing hydrological data, including many statistical approaches used in the ecological sciences. Additionally, packages that help model datasets with extreme values are discussed in the [ExtremeValue](ExtremeValue.html) Task View.

  - [rtop](http://cran.rstudio.com/web/packages/rtop/index.html): Interpolation of Data with Variable Spatial Support Geostatistical interpolation of data with irregular spatial support such as runoff related data or data from administrative units.

</div>
 

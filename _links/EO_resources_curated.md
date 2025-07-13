# Earth Observation (#EO) resources: a curated list
[![Update](https://img.shields.io/github/last-commit/bzgeo/bzgeo?label=last%20updated&style=flat-square)](https://github.com/BzGEO/BzGEO/edit/main/links/EO_resources_curated.md)

*compiled by Emil A. Cherrington, Ph.D.*

## OVERVIEW: Key questions
* *WHERE can I find satellite data?*
* *WHAT is hyperspectral data all about?*
* *WHERE can I find software for processing satellite data?*
* *HOW can I process huge EO datasets in the cloud?* 
* *WHAT does geospatial artificial intelligence (geo AI) entail?*

## Portals and platforms for EO data
* U.S. National Aeronautics & Space Administration (NASA)
  * [NASA EOSDIS WorldView](https://worldview.earthdata.nasa.gov/) -> *visualization*
  * [NASA Giovanni](https://giovanni.gsfc.nasa.gov/giovanni/) -> *time series analysis*
  * [NASA EarthData Search](https://search.earthdata.nasa.gov/search) -> *data extraction / download*
  * [NASA  OB.DAAC L3 / L4 browser](https://oceandata.sci.gsfc.nasa.gov/l3/) -> *data extraction / download*
  * [NASA ASF DAAC](https://search.asf.alaska.edu/#/) -> *data extraction / download*
  * [NASA AppEEARS](https://appeears.earthdatacloud.nasa.gov/) -> *data extraction / download*
* U.S. Geological Survey (USGS)
  * [USGS Earth Explorer](https://earthexplorer.usgs.gov/) -> *data extraction / download*
  * [USGS ESPA](https://espa.cr.usgs.gov/) -> *data extraction / download*
  * [USGS Glovis](https://glovis.usgs.gov/app) -> *visualization*
* European Commission's Copernicus Programme + European Space Agency (ESA)
  * [Copernicus Browser](https://browser.dataspace.copernicus.eu/) -> *data extraction / download*
  * [Copernicus Land Monitoring Service](https://land.copernicus.eu/en) -> *data extraction / download*
* Commercial
  * [Maxar Discover](https://discover.maxar.com/) -> *visualization*
  * [Planet Explorer](https://www.planet.com/explorer/) -> *data extraction / download*
    * View cool visualizations of Planet data: [Planet Stories](https://www.planet.com/stories/)
    * Apply for access to Planet data: [Planet Education & Research Program application](https://www.planet.com/industries/education-and-research/#apply-now)
    * Apply for access to Planet data: [NASA Commercial Satellite Data (CSDA) program](https://csdap.earthdata.nasa.gov/signup/)
    * Planet Dove + SuperDove band [specifications](https://docs.planet.com/data/imagery/planetscope/)
      * Dove Classic + Dove-R: VNIR (blue, green, red, NIR)
      * Super Dove (coastal blue, blue, green I, green, yellow, red, red edge, NIR)

## Hyperspectral data resources
* Missions
  * NASA spaceborne (i.e., satellite) missions
    * EO-1 [Hyperion](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-earth-observing-one-eo-1-hyperion), 2001-2017
      * [Hyperion data in GEE](https://developers.google.com/earth-engine/datasets/catalog/EO1_HYPERION)
    * International Space Station [Earth Surface Mineral Dust Source Investigation (EMIT)](https://earth.jpl.nasa.gov/emit/), 2022-present
      * [EMIT data in GEE](https://developers.google.com/earth-engine/datasets/catalog/NASA_EMIT_L2A_RFL)
    * [Plankton, Aerosol, Cloud, ocean Ecosystem (PACE)](https://pace.oceansciences.org/), 2024-present
    * [Surface Biology & Geology (SBG)](https://sbg.jpl.nasa.gov/), *proposed*
  * NASA airborne missions
    * [Airborne Visible InfraRed Imaging Spectrometer (AVIRIS)](https://aviris.jpl.nasa.gov/)
      * [AVIRIS-NG data over NEON sites, in GEE](https://developers.google.com/earth-engine/datasets/catalog/projects_neon-prod-earthengine_assets_HSI_REFL_002)
  * EOportal.org [hyperspectral mission list](https://www.eoportal.org/other-space-activities/hyperspectral-imaging)
* **GitHub code repositories** (*not exhaustive*)
  * Brian Bue et al.'s [Hyperspectral Image Interactive Holistic Analysis Toolkit, HiiHAT (2011)](https://github.com/dsmbgu8/HiiHAT)
  * GatorSense's Hyperspectral Image Analysis Toolkit
    * [Matlab implementation (2018)](https://github.com/GatorSense/hsi_toolkit)
    * [Python implementation (2019)](https://github.com/GatorSense/hsi_toolkit_py)
  * Charles Camp Jr.'s [CRIKit2: Hyperspectral imaging toolkit (2022)](https://github.com/CCampJr/CRIkit2)
  * SpringsZ's [Hyperspectral Image Computer Vision Classification Image Preprocessing Toolkit (2023)](https://github.com/springsZ/Hyperspectral-Image-Computer-Vision-Classification-Image-Preprocessing-Toolkit)
  * NASA
    * [SBG-VSWIR (2025)](https://github.com/sbg-vswir) (*multiple individual repositories*)
    * [ISOFIT 3x (2025)](https://github.com/isofit/isofit)
    * [VITALS (2025)](https://github.com/nasa/VITALS)
  * Giacomo Nodjoumi's [HyperSpectral Toolkit (2024)](https://github.com/Hyradus/HyperSpectralToolkit)
  * Wujietao's [Hyperspectral Detection Tools (2024)](https://github.com/wujietao233/Hyperspectral_Detection_Tools)
  * SongYZ's [Hyperspectral Imagery (HSI) Preprocessing Toolkit (2025)](https://github.com/songyz2019/hsi-preprocessing-toolkit)
  * Skye Caplan's [PACE tutorials (2025)](https://github.com/skyecaplan/pace_tutorials)
  * Emil Cherrington
    * [PACE OCI toolkit (2025)](https://github.com/BzGEO/pace_oci_toolkit)
      * [GEE code repo](https://bit.ly/gee_repo_pace_oci)
    * [Hyperspectral toolkit (2025)](https://github.com/BzGEO/hyperspectral_toolkit)
      * [GEE code repo](https://bit.ly/gee_repo_hyperspectral)

## Spotlight: Hyperspectral data from NASA's PACE
* [PACE mission page](https://pace.oceansciences.org/)
  * [Ocean Color Instrument (OCI)](https://pace.oceansciences.org/oci.htm)
* Data access
  * View data in [NASA EOSDIS WorldView](https://go.nasa.gov/4kNDA1z) -> *example for 8 July 2025*
  * Download data via the [NASA  OB.DAAC L3 / L4 browser](https://oceandata.sci.gsfc.nasa.gov/l3/)
  * Download data via the [NASA EarthData Search](https://search.earthdata.nasa.gov/search?fi=OCI&as[platforms][0]=Space-based%20Platforms%3AEarth%20Observation%20Satellites%3A%3APACE&as[instrument][0]=OCI&fpb0=Space-based%20Platforms&fpc0=Earth%20Observation%20Satellites&fps0=PACE)
* PACE data products
  * [PACE data products list](https://pace.oceansciences.org/data_table.htm)
    * [Data description: Surface reflectance](https://oceancolor.gsfc.nasa.gov/data/10.5067/PACE/OCI/L2/SFREFL/3.0)
    * [Data description: Land Vegetation Indices (LandVI)](https://oceancolor.gsfc.nasa.gov/data/10.5067/PACE/OCI/L2/LANDVI/3.0)
  * [PACE: Terrestrial products overview slides (Dec. 2024)](https://pace.oceansciences.org/docs/03-c-Huemmrich_PACE_Terrestrial.pdf)
* PACE Applications
  * [PACE: Applications workshop (Dec. 2024)](https://pace.oceansciences.org/event_archive/2024-PACE-Applications-Workshop.htm)
* PACE events [page](https://pace.oceansciences.org/events.htm)
* [PACE Land data Users' Group (PLUG)](https://pace.oceansciences.org/events_more.htm?id=74)
  * 1st PLUG meeting (15.04.2025): [recording](https://www.youtube.com/watch?v=7U1FBZyB-dk)
  * 2nd PLUG meeting (01.07.2025): [recording](https://www.youtube.com/watch?v=hOu8rPd_x6I)
* PACE Early Adopters / Applications Partners
  * [PACE: Early Adopters projects](https://pace.oceansciences.org/app_adopters.htm)
    * PACE: Early Adopters [UAH project](https://pace.oceansciences.org/people_ea.htm?id=127)
    * PACE: Early Adopters projects [application form](https://forms.gle/ZxUeqDJDZu47SEzD8)
* Calendars for products
  * [8-day calendar](https://bit.ly/pace_oci_8d_cal)
  * [Julian day calendar (non-leap year)](https://satcorps.larc.nasa.gov/safari/JulianDayChart.html)
* Spectral bands from various multispectral and hyperspectral platforms
  * [Hyperspectral: PACE OCI (SFREFL, v3)](https://bit.ly/pace_oci_sr_v3_bands)
  * [Hyperspectral: ISS EMIT](https://bit.ly/iss_emit_bands)
  * [Multispectral: Landsat TM / ETM+ / OLI / OLI2](https://bit.ly/landsat_bands)
  * [Multispectral: Sentinel-2 MSI](https://bit.ly/s2_bands)

## Desktop software programs
* GUI-based
  * Clark University's TerrSet [installers](https://github.com/ClarkCGA/terrset/releases)
  * ESA's SNAP [installers](https://step.esa.int/main/download/snap-download/)
  * NASA's SeaDAS [installers](https://seadas.gsfc.nasa.gov/downloads/) -> *based on SNAP*
  * Quantum GIS (QGIS) [installers](https://qgis.org/download/)
* Programming-based
  * Anaconda [installers](https://www.anaconda.com/download)
  * R installers
    * [Linux](https://cran.r-project.org/bin/linux/)
    * [MacOS](https://cran.r-project.org/bin/macosx/)
    * [Windows](https://cran.r-project.org/bin/windows/)
  * R Studio desktop [installers](https://posit.co/download/rstudio-desktop/)

## the Google Earth Engine (GEE) platform for EO cloud computing
* GEE [Code Editor](https://code.earthengine.google.com/)
  * [GEE registration link](https://earthengine.google.com/signup/)
  * [Instructions for GEE project registration](https://courses.spatialthoughts.com/gee-sign-up.html), via SpatialThoughts.com
* GEE [tasks](https://code.earthengine.google.com/tasks)
* Google Groups
  * [GEE Developers Google Group](https://groups.google.com/g/google-earth-engine-developers)
* Data catalogs
  * [GEE public catalog](https://developers.google.com/earth-engine/datasets)
  * [Awesome GEE community catalog](https://gee-community-catalog.org/)
* GEE tutorials, etc.
  * [Book: EE Fundamentals & Applications (EEFA), 2022](https://www.eefabook.org/)
    * [Videos](https://www.youtube.com/@eefabook3667/videos)
    * [EEFA book GEE code repository](https://earthengine.googlesource.com/projects/gee-edu/book)
  * [GEE Higher Education resources](https://developers.google.com/earth-engine/tutorials/edu)
  * [Tutorials from the community](https://developers.google.com/earth-engine/tutorials/community/explore)
* Other resources
  * [JavaScript color guide](http://www.javascripter.net/faq/colornam.htm)
  * [Git repositories on GEE](https://earthengine.googlesource.com/)
  * Google Developer Experts (GDEs)
    * [GDE directory](https://developers.google.com/community/experts/directory)
      * [GEE GDEs](https://developers.google.com/community/experts/directory?specialization=earth-engine)
    * [Advocu](https://app.advocu.com/activities) -> *for GDE reporting*
* GEE apps
   * [Google's curated apps](https://www.earthengine.app/)
   * [BzGEO's published apps](https://bzgeo.users.earthengine.app/)
   * [SERVIR-BZ's published apps](https://servirbz.users.earthengine.app/)
   * [BZ-SDG project's published apps](https://bz-sdg.earthengine.app/)
* *Geo For Good (G4G) conference* resources
  * Geo For Good 2024
    * [G4G 2024: Sao Paulo](https://earthoutreachonair.withgoogle.com/events/geoforgood24-saopaulo)
    * [G4G 2024: Dublin](https://earthoutreachonair.withgoogle.com/events/geoforgood24-dublin)
  * [Colab Notebook - Soy mapping](https://colab.research.google.com/drive/1Iip9Li7ZguMxKUjZ4mbcg_q1EDyAvUB2)
  * AI-related slides
    * [Vertex AI](https://docs.google.com/presentation/d/1eNJDIoJg-ADrxC09JIzl00frjyseEc917rItTDPalGI/edit#slide=id.g303d87bcffc_0_0)
    * [Embeddings, part 1](https://docs.google.com/presentation/d/1ZfBYUNV1w377rkxc3REm5_evyzMJF6szxXGBszKC7uw/edit#slide=id.g3012811fd68_0_1316)
    * [Embeddings, part 2](https://docs.google.com/presentation/d/1azsWfeDuC-ZF5L8LNuWAEe49UOsxC-pPvqyZvSvJThk/edit#slide=id.g303d69aca51_0_197)
 
## Select geospatial AI resources

* NASA-related
  * [SERVIR Geo AI Working Group page](https://sites.google.com/uah.edu/geo-ai-working-group/home)
  * Course - [NASA ARSET: Fundamentals of Machine Learning for Earth Science (2023)](https://appliedsciences.nasa.gov/get-involved/training/english/arset-fundamentals-machine-learning-earth-science)
    * [Associated GitHub page](https://github.com/NASAARSET/ARSET_ML_Fundamentals)

* Europe-related
  * [ML4Earth Slack channel](https://ml4earthworkspace.slack.com/team)
  * Course - [EO College: Introduction to Machine Learning in Earth Observation MOOC (2024)](https://eo-college.org/courses/introduction-to-machine-learning-for-earth-observation/)

* Esri
  * [Deep Learning GitHub page w/ installers](https://github.com/Esri/deep-learning-frameworks?tab=readme-ov-file)
  * [Deep learning models / packages](https://livingatlas.arcgis.com/en/browse/#d=1&type=tool&itemTypes=Deep+Learning+Package)
    * Prithvi [foundational models](https://livingatlas.arcgis.com/en/browse/?q=prithvi#d=1&type=tool&itemTypes=Deep+Learning+Package&q=prithvi) from NASA and IBM
      * Prithvi HLS: [Crop classification](https://www.arcgis.com/home/item.html?id=39e598cb9eed4f1eac28f8484c5f3679)
      * Prithvi HLS: [Burn scar mapping](https://www.arcgis.com/home/item.html?id=9af7af28dd91473bbc8ad40942e74563)
      * Prithvi HLS: [Flood mapping](https://www.arcgis.com/home/item.html?id=29dc90c33daf402caa9293c2088d1057)
      * Prithvi WxC: [Weather And Climate Forecasting](https://www.arcgis.com/home/item.html?id=e5969e62295e4c7881b38ea16b565a2d)
  * [MyEsri.com](https://my.esri.com/) -> *for downloading ArcGIS software*

* EAC-related
  * [Geospatial Machine Learning (geoML) master document](https://bit.ly/geoml)
  * [Deep learning experiment runs](https://bit.ly/geoml_mod_comp)
  * [Deep learning on-ramp presentation slides](https://docs.google.com/presentation/d/1e9h_LQrSyL5oriFHUMxsVyWulQ1ReO1S/edit#slide=id.p1)
    * [Deep learning on-ramp presentation recording](https://www.youtube.com/watch?v=H-iAVLtkV0c) (Oct. 2024 version)

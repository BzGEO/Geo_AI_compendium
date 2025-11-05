# Miscellaneous research questions related to #GeoML (#GeoAI)
[![Update](https://img.shields.io/github/last-commit/bzgeo/bzgeo?label=last%20updated&style=flat-square)](https://github.com/BzGEO/Geo_AI_compendium)

## Scenarios

**Scenario 1:** *You would like to run geospatial [AI](https://support.esri.com/en-us/gis-dictionary/ai) ([machine learning](https://support.esri.com/en-us/gis-dictionary/machine-learning))-related tasks on a desktop or mobile system and are looking to purchase a workstation. Does the computer's configuration ultimately matter? What type of memory ([RAM](https://en.wikipedia.org/wiki/Random-access_memory)), central processing unit ([CPU](https://en.wikipedia.org/wiki/Central_processing_unit)), and graphics processing unit ([GPU](https://en.wikipedia.org/wiki/Graphics_processing_unit)) resources should you consider, if at all?*

**Scenario 2:** *You are looking to do intensive image processing work on the mobile workstation you're looking to purchase. Should you necessarily choose a system with the highest RAM, fastest CPU, and fastest GPU available (e.g., 128 GB RAM, 3.00 GHz CPU, [Nvidia GeForce RTX 5090](https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/rtx-5090/))? Would you get similar results from a system with fewer resources (e.g., 32 GB RAM, 2.00 GHz CPU, [Nvidia GeForce RTX 5060](https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/rtx-5060-family/))?*

**Scenario 3:** *You just want to know if your basic desktop or laptop that does not have a dedicated GPU will be able to execute deep learning-based classifications or regressions in [ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview). Should you just skip trying to do desktop-based classification altogether and run your classifications or regressions in the cloud? If so, what approaches should you explore?*

## Hypothesis(es)
* *Deep learning-based classifications **should** execute (run) faster on more powerful computers than on less powerful computers.*

## Research questions
* Does the application of deep learning-based land cover classification result in higher accuracies than traditional machine learning methods like supervised classification?

* To what extent do [desktop] computing architectures influence run times for deep learning-based classifications?
* Does one need to have a top-of-the-line graphics processing unit (GPU) to run deep learning-based classifications (model training *and* model inferencing) quickly?
    * Is the speed with which one is able to perform deep learning-based classifications impacted by GPU specifications?
    * To what extent is the speed with which one is able to perform deep learning-based classifications impacted by GPU specifications?

* How appropriate are desktop computing architectures for implementing deep learning-based land cover classifications, especially in the context of the growing availability of cloud computing resources? 

## Computer systems


## Experiment tracker
See: https://bit.ly/geoml_mod_comp [**public**]

## Other
*Are there parallel past or ongoing benchmarking types of activities?*
* [GEOBench-VLM: Benchmarking Vision-Language Models for Geospatial Tasks](https://github.com/The-AI-Alliance/GEO-Bench-VLM)

# GeoAI Sourcebook:
## Geospatial 🗺️ artificial intelligence / machine learning (Geo AI / Geo ML) 👨‍💻 resources focused on land cover monitoring 🛰️🏞️

*compiled by Emil A. Cherrington, Ph.D.*

[![Update](https://img.shields.io/github/last-commit/bzgeo/geo_ai_refs?label=last%20updated&style=flat-square)](https://github.com/BzGEO/geo_ai_refs)

![](https://github.com/BzGEO/geo_ai_refs/blob/main/_graphics/word_cloud_v2023-05-05b.PNG)

## Overview

1. Objectives
2. Schematics
3. Resources: Machine learning (traditional)
4. Resources: Deep learning
5. Resources: Uncertainty / accuracy assessment
6. Resources: Other

## 1. Objectives

* Document the various Machine Learning approaches available across various [desktop + cloud] platforms (e.g. [ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview), [ENVI](https://www.nv5geospatialsoftware.com/Products/ENVI), [ERDAS Imagine](https://hexagon.com/products/erdas-imagine), [GEE](https://code.earthengine.google.com/), [QGIS](https://qgis.org/),[R](https://cran.r-project.org/), [SNAP](https://step.esa.int/main/download/snap-download/), [TerrSet](https://github.com/ClarkCGA/terrset))
  * Compile resources (including tutorials and sample scripts) regarding how to implement those approaches in the platforms listed ⬆️
  * Understand how to replicate ML workflows from one platform to another
* Understand the limitations of the various ML approaches 🤔
  * Push the limits of the various approaches
  * *For instance, what determines the taste of the cake? The quality of the ingredients used, or the technique of the baker?* 🤔

## 2. Schematics

* Overview of the distinctions between Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning (DL)

![](https://github.com/BzGEO/geo_ai_refs/blob/main/_graphics/venn_diagram_ai_small.png)

*source*: [Human Centered AI Lab (2017)](https://human-centered.ai/wordpress/wp-content/uploads/2017/11/Deep-Learning-subset-of-Machine-Learning-subset-of-Artificial-Intelligence.jpg)

* Overview of various tools for doing ML (“[SciKit-Learn algorithm cheat sheet](https://scikit-learn.org/stable/machine_learning_map.html)”):

![](https://github.com/BzGEO/geo_ai_refs/blob/main/_graphics/scikit_learn_cheatsheet.PNG)

*source*: [SciKitLearn](https://scikit-learn.org/stable/machine_learning_map.html)

## 3. Resources: Machine learning (classical / traditional)

*These are resources for commonly-used software applications.*

## 3.a. Overview of classical / traditional ML
*Let's start with an overview of Machine Learning.*

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/google_2022_ml_defn.PNG)
[source:](https://docs.google.com/presentation/d/1zha7dCuy7Rq43OFDQOXbwWbDP2fAv5aOpgdzhno7IhU/edit?slide=id.gff707151b9_21_75#slide=id.gff707151b9_21_75) Google (2022)

*By the way, how does classical / traditional ML differ from Deep Learning?* 🤔

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/google_2024_ml_vs_dl.PNG)
[source:](https://docs.google.com/presentation/d/1BUk4pvlpJb5Uwm4Uld8WqDun4MexaLygACcd1pRWCVc/edit?slide=id.g2f65abacf57_0_1#slide=id.g2f65abacf57_0_1) Google (2024)

## 3.b. Classification algorithms

## 3.b.1. Unsupervised classification algorithms

**K-means**

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/algo_unsupervised_k_means.PNG)

source: B. Howell (2006)


**ISODATA**

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/algo_unsupervised_isodata_1.PNG)

source: B. Howell (2006)


![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/algo_unsupervised_isodata_2.PNG)

source: J. Jensen (2005)


![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/algo_unsupervised_isodata_3.PNG)

source: J. Jensen (2005)


## 3.b.2. Supervised classification algorithms

**Minimum Distance**

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/algo_min_dist.PNG)

source: B. Howell (2006)


**Maximum Likelihood**

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/algo_mlc.PNG)

source: B. Howell (2006)


**Support Vector Machine**

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/algo_svm.PNG)

[source](https://scikit-learn.org/stable/modules/svm.html): SciKit-Learn


**Random Forest**

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/algo_rf.PNG)

source: RUS-Copernicus


**Other: Miscellaneous supervised ML classification output options in Earth Engine** ➡️ *some classifiers output class probability maps*

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/algo_gee_options.PNG)

[source](https://docs.google.com/presentation/d/1zha7dCuy7Rq43OFDQOXbwWbDP2fAv5aOpgdzhno7IhU/edit#slide=id.gff707151b9_21_352): Google (2022) | for viewing class probabilities, see [this](https://developers.google.com/earth-engine/apidocs/ee-classifier-setoutputmode)

## 3.c. Classical / traditional ML in commonly-used software applications

**ArcGIS**
* Classifying Images in **ArcGIS Desktop** 10.4 [tutorial](https://community.esri.com/t5/esri-technical-support-blog/classifying-images-in-arcgis-for-desktop-10-4)
* Train a 'Random Trees' classifier in **ArcGIS Desktop** [tutorial](https://desktop.arcgis.com/en/arcmap/latest/tools/spatial-analyst-toolbox/train-random-trees-classifier.htm)
* Overview of image classification in **ArcGIS Pro** [tutorial](https://pro.arcgis.com/en/pro-app/latest/help/analysis/image-analyst/overview-of-image-classification.htm)

**QGIS**
* Supervised classification using the Semi-automatic classification Plugin (SCP)’s various algorithms and Sentinel-2 data in QGIS [tutorial](https://dges.carleton.ca/CUOSGwiki/index.php/Supervised_classification_in_QGIS)

**ENVI**
* Classification (supervised + unsupervised ML) workflow [overview](https://www.nv5geospatialsoftware.com/docs/Classification.html)
* Classification [tutorial](https://www.nv5geospatialsoftware.com/docs/classificationtutorial.html)

**SNAP**
* Unsupervised classification of land cover using Sentinel-1 in SNAP [tutorial](https://dges.carleton.ca/CUOSGwiki/index.php/Unsupervised_Landcover_Classification_In_SNAP_Using_Sentinel_1_Imagery)
* Supervised classification (Random Forests) of forests using Sentinel-2 in SNAP [tutorial](https://dges.carleton.ca/CUOSGwiki/index.php/Random_Forest_Supervised_Classification_Using_Sentinel-2_Data)
* Land cover classification (unsupervised, supervised) using Sentinel-1 in SNAP [tutorial](http://step.esa.int/docs/tutorials/S1TBX%20Landcover%20classification%20with%20Sentinel-1%20GRD.pdf)

**Google Earth Engine (GEE)**
* Basic ML in GEE
  * [Slides](https://docs.google.com/presentation/d/1zha7dCuy7Rq43OFDQOXbwWbDP2fAv5aOpgdzhno7IhU) (2022) ➡️ *see [slide 69](https://www.google.com/url?q=https://docs.google.com/presentation/d/1zha7dCuy7Rq43OFDQOXbwWbDP2fAv5aOpgdzhno7IhU/edit%23slide%3Did.gff707151b9_21_490&sa=D&source=docs&ust=1753935599322924&usg=AOvVaw2eVgFXxv2aAIFeSD3xLMYe) for restrictions re: the size of the training samples and classifier*
    * [Video](https://www.youtube.com/watch?v=WvaBZbph_cU) (2022)
  * [Slides](https://docs.google.com/presentation/d/1aZA8Q7nI-lCWHh709U2xRr2tSaGL6WRbfWMZfDecuSw/edit?resourcekey=0-L4QfUh2AXGnMoLgmrnTHxw#slide=id.g248af0f0c61_0_0) - Geospatial ML intro (2023)
  * [Slides](https://docs.google.com/presentation/d/1jT2biH6DIlN133djneZcdXS7-CgR-dlWm2jBQ1KhM50) - EE classifiers (2023)
    * [Video](https://www.youtube.com/watch?v=arqbzovtQTo) (2023)
  * [Slides](https://docs.google.com/presentation/d/1BUk4pvlpJb5Uwm4Uld8WqDun4MexaLygACcd1pRWCVc/edit#slide=id.g23ba3cc7e10_1_0) (2024)
* Overview of [unsupervised ML](https://developers.google.com/earth-engine/guides/clustering)
* Overview of [supervised ML](https://developers.google.com/earth-engine/guides/classification)
* Example excercise for [supervised classification using GEE](https://dges.carleton.ca/CUOSGwiki/index.php/Supervised_Classifications_using_Google_Earth_Engine)
* Example supervised learning classifiers
  * [Minimum distance](https://developers.google.com/earth-engine/apidocs/ee-classifier-minimumdistance) ➡️ includes 4 approaches, including:
    * Euclidean Distance
    * Mahalanobis Distance
    * Manhattan Distance
    * Spectral Angle / Cosine
      * Example Minimum Distance [script](https://code.earthengine.google.com/711333e694ed218c9bee90b4e2a1e239) (*including a condition limiting the minimum distance to classes*)
  * [Support Vector Machine (SVM)](https://developers.google.com/earth-engine/apidocs/ee-classifier-libsvm)
  * [Classification & Regression Trees (CART)](https://developers.google.com/earth-engine/apidocs/ee-classifier-smilecart)
  * [Naives Bayes](https://developers.google.com/earth-engine/apidocs/ee-classifier-smilenaivebayes) ➡️ *includes what is otherwise referred to as Maximum Likelihood Classification (MLC)*
  * [Random Forest](https://developers.google.com/earth-engine/apidocs/ee-classifier-smilerandomforest)

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/gee_clusterers_2025-07.PNG)

![](https://github.com/BzGEO/Geo_AI_sourcebook/blob/main/_graphics/gee_classifiers_2025-07.PNG)

## 4. Resources: Deep Learning

🚨 *This section is still in progress.* 🚨

![](https://github.com/BzGEO/geo_ai_refs/blob/main/_graphics/cranberries_dl_small2.png)
source: modified from the Cranberries' "Everybody Else is Doing It, So Why Can't We?" album cover (1993)



![](https://github.com/BzGEO/geo_ai_refs/blob/main/_graphics/oversized_salad_dl2.png)



## 5. Resources: Uncertainty / accuracy assessment

* General accuracy assessment
  * ArcGIS Desktop: Accuracy Assessment for Image Classification [page](https://desktop.arcgis.com/en/arcmap/latest/manage-data/raster-and-images/accuracy-assessment-for-image-classification.htm)
  * ArcGIS Pro: Accuracy Assessment [page](https://pro.arcgis.com/en/pro-app/latest/help/analysis/image-analyst/accuracy-assessment.htm)
  * GEE: Export training samples [script](https://developers.google.com/earth-engine/apidocs/export-table-todrive)
  * QGIS: Accuracy assessment [plugin](https://plugins.qgis.org/plugins/accassess/)

* Accuracy assessment of land cover data applying statistical best practices
  * Area Estimation & Accuracy Assessment (AREA2) toolbox
    * GitHub page: https://github.com/bullocke/AREA2/blob/master/README.md
    * GEE repository: https://code.earthengine.google.com/?accept_repo=projects/AREA2/public

![](https://github.com/BzGEO/geo_ai_refs/blob/main/_graphics/graphic_ml_algorithm_accuracy_metwalli.png)

[*source*](https://towardsdatascience.com/how-to-choose-the-right-machine-learning-algorithm-for-your-application-1e36c32400b9): Sara A. Metwalli / Towards Data Science (2020)

* The issue of training, validation, and test data
  * Training, validation, and test data sets (Wikipedia): https://en.wikipedia.org/wiki/Training,_validation,_and_test_data_sets
  * Definitions (from J. Brownlee, 2020): https://machinelearningmastery.com/difference-test-validation-datasets/

![](https://github.com/BzGEO/geo_ai_refs/blob/main/_graphics/graphic_validation_brownlee.png)
[*source*](https://machinelearningmastery.com/difference-test-validation-datasets/): J. Brownlee (2020)

## 6. Resources: Other

**GEE**
* Earth Engine Fundamentals & Applications [book](https://www.eefabook.org/) (2022) 📔
  * [Videos](https://www.youtube.com/@eefabook3667/videos) 🎥
  * EEFA book GEE code [repository](https://code.earthengine.google.com/?accept_repo=projects/gee-edu/book) 💾
* Earth Engine higher education [tutorials](https://developers.google.com/earth-engine/tutorials/edu) 📝
* Earth Engine general [tutorials](https://developers.google.com/earth-engine/tutorials/community/explore) 📝
* Earth Engine Developers [Google Group](https://groups.google.com/g/google-earth-engine-developers/) 👨‍💻

**Miscellaneous**

* NASA Science Mission Directorate [Artificial Intelligence initiative](https://science.nasa.gov/open-science/smd-ai-initiative/)
* Oak Ridge National Lab [Trillion Pixel Challenge](https://geoai.ornl.gov/trillion-pixel/)
  * Sept. 2019 workshop [report](https://geoai.ornl.gov/trillion-pixel/wp-content/uploads/sites/2/2021/03/Trillion_Pixel_Challenge_Workshop_Report-for-public-release.pdf)
  * July 2023 workshop [press release](https://www.ornl.gov/news/trillion-pixel-challenge-looks-ahead-next-decade-geoai-innovation)
  * Sept. 2024 workshop [report](https://geoai.ornl.gov/trillion-pixel/wp-content/uploads/sites/2/2025/06/2024_GeoAI_Trillion_Pixel_Workshop_Report.pdf)

* Statistical Machine Intelligence and Learning Engine [(SMILE)](https://haifengl.github.io/classification.html)
  * Google: SMILE Naive Bayes [documentation](https://developers.google.com/earth-engine/apidocs/ee-classifier-smilenaivebayes)

* Other ['open source GIS tutorials'](https://dges.carleton.ca/CUOSGwiki/index.php/Main_Page) from Carleton University (Canada)
  
* How to open a Google Colab Notebook from Github in [Google Colab](https://colab.research.google.com/): "*Just change the domain from 'github.com' to 'githubtocolab.com' and the notebook will open in Colab.*" [source](https://stackoverflow.com/questions/62596466/how-can-i-run-notebooks-of-a-github-project-in-google-colab#:~:text=Open%20Github%20notebook%20whatever%20you,notebook%20will%20open%20in%20Colab)


* *Emil's private GeoAI [photo library](https://photos.app.goo.gl/oeWUE5RKnKGTmT1Q9)* 📸

**Neural networks + deep learning in general**
* Neural networks explainer [video](https://www.youtube.com/watch?v=X22ENbm4BfU) 🎥 from Esri ➡️ *great contrast* w/ Random Forest explainer [video](https://www.youtube.com/watch?v=HL0nz9uOtF8) 🎥

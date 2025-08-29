# Geospatial Artificial Intelligence (Geo AI) / Geospatial Machine Learning (Geo ML) Compendium:
## Resources 👨‍💻 focused on land cover monitoring 🏞️🛰️

🚨 *This compendium is a work in progress.* 🚨

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16735094.svg)](https://doi.org/10.5281/zenodo.16735094)
[![Update](https://img.shields.io/github/last-commit/bzgeo/Geo_AI_compendium?label=last%20updated&style=flat-square)](https://github.com/BzGEO/Geo_AI_compendium)
![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=bzgeo.Geo_AI_compendium)

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/word_cloud_v2023-05-05b.PNG)

## Overview

1. [Objectives](https://github.com/BzGEO/Geo_AI_compendium/#1-objectives)
2. [Schematics](https://github.com/BzGEO/Geo_AI_compendium/#2-schematics)
3. [Resources: Machine learning (classical)](https://github.com/BzGEO/Geo_AI_compendium/#3-resources-machine-learning-classical--traditional)
4. [Resources: Deep learning](https://github.com/BzGEO/Geo_AI_compendium/#4-resources-deep-learning-dl)
5. [Resources: Uncertainty assessment / accuracy assessment](https://github.com/BzGEO/Geo_AI_compendium/?tab=readme-ov-file#5-resources-uncertainty-assessment--accuracy-assessment)
6. [Resources: Other](https://github.com/BzGEO/Geo_AI_compendium/#6-resources-other)
7. [Software installers](https://github.com/BzGEO/Geo_AI_compendium/#7-software-installers)

## 1. Objectives

* Document the various Machine Learning approaches available across various [desktop + cloud] platforms (e.g. [ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview), [ENVI](https://www.nv5geospatialsoftware.com/Products/ENVI), [ERDAS Imagine](https://hexagon.com/products/erdas-imagine), [GEE](https://code.earthengine.google.com/), [QGIS](https://qgis.org/), [R](https://cran.r-project.org/), [SNAP](https://step.esa.int/main/download/snap-download/), [TerrSet](https://github.com/ClarkCGA/terrset))
  * Compile resources (including tutorials and sample scripts) regarding how to implement those approaches in the platforms listed ⬆️
  * Understand how to replicate ML workflows from one platform to another
* Understand the limitations of the various ML approaches 🤔
  * Push the limits of the various approaches
  * *For instance, what determines the taste of the cake? The quality of the ingredients used, or the technique of the baker?* 🤔

## 2. Schematics

* Overview of the distinctions between Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning (DL)

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/venn_diagram_ai_small.png)

*source*: [Human Centered AI Lab (2017)](https://human-centered.ai/wordpress/wp-content/uploads/2017/11/Deep-Learning-subset-of-Machine-Learning-subset-of-Artificial-Intelligence.jpg)

**Therefore ⬇️ we will focus on the broader ML and the DL aspects of geospatial artificial intelligence.** 🧐

* Overview of various tools for doing ML (“[SciKit-Learn algorithm cheat sheet](https://scikit-learn.org/stable/machine_learning_map.html)”):

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/scikit_learn_cheatsheet.PNG)

*source*: [SciKitLearn](https://scikit-learn.org/stable/machine_learning_map.html)

## 3. Resources: Machine learning (classical / traditional)

*These are resources for commonly-used software applications.*

## 3.a. Overview of classical / traditional ML
*Let's start with an overview of Machine Learning.*

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/google_2022_ml_defn.PNG)
*source*: [Google (2022)](https://docs.google.com/presentation/d/1zha7dCuy7Rq43OFDQOXbwWbDP2fAv5aOpgdzhno7IhU/edit?slide=id.gff707151b9_21_75#slide=id.gff707151b9_21_75)

*By the way, how does classical / traditional ML differ from Deep Learning?* 🤔

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/google_2024_ml_vs_dl.PNG)
*source*: [Google (2024)](https://docs.google.com/presentation/d/1BUk4pvlpJb5Uwm4Uld8WqDun4MexaLygACcd1pRWCVc/edit?slide=id.g2f65abacf57_0_1#slide=id.g2f65abacf57_0_1)

## 3.b. Classification algorithms

## 3.b.1. Unsupervised classification algorithms

**K-means**

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/algo_unsupervised_k_means.PNG)

*source*: B. Howell (2006)


**ISODATA**

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/algo_unsupervised_isodata_1.PNG)

*source*: B. Howell (2006)


![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/algo_unsupervised_isodata_2.PNG)

*source*: J. Jensen (2005)


![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/algo_unsupervised_isodata_3.PNG)

*source*: J. Jensen (2005)


## 3.b.2. Supervised classification algorithms

**Minimum Distance**

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/algo_min_dist.PNG)

*source*: B. Howell (2006)


**Maximum Likelihood**

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/algo_mlc.PNG)

*source*: B. Howell (2006)


**Support Vector Machine**

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/algo_svm.PNG)

*source*: [SciKit-Learn (2024)](https://scikit-learn.org/stable/modules/svm.html)


**Random Forest**

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/algo_rf.PNG)

*source*: [RUS-Copernicus (2017)](https://eo4society.esa.int/wp-content/uploads/2022/01/LAND01_CropMapping_Seville.pdf)


**Other: Miscellaneous supervised ML classification output options in Earth Engine** ➡️ *some classifiers output class probability maps*

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/algo_gee_options.PNG)

*source*: [Google (2022)](https://docs.google.com/presentation/d/1zha7dCuy7Rq43OFDQOXbwWbDP2fAv5aOpgdzhno7IhU/edit#slide=id.gff707151b9_21_352) | for viewing class probabilities, see [this](https://developers.google.com/earth-engine/apidocs/ee-classifier-setoutputmode)

## 3.c. Classical / traditional ML in commonly-used software applications

**ArcGIS**
* Classifying Images in **ArcGIS Desktop** 10.4 [tutorial](https://community.esri.com/t5/esri-technical-support-blog/classifying-images-in-arcgis-for-desktop-10-4)
* Train a 'Random Trees' classifier in **ArcGIS Desktop** [tutorial](https://desktop.arcgis.com/en/arcmap/latest/tools/spatial-analyst-toolbox/train-random-trees-classifier.htm)
  * Random Forest explainer [video](https://www.youtube.com/watch?v=HL0nz9uOtF8) 🎥
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
    * [Video](https://www.youtube.com/watch?v=WvaBZbph_cU) 🎥 (2022)
  * [Slides](https://docs.google.com/presentation/d/1aZA8Q7nI-lCWHh709U2xRr2tSaGL6WRbfWMZfDecuSw/edit?resourcekey=0-L4QfUh2AXGnMoLgmrnTHxw#slide=id.g248af0f0c61_0_0) - Geospatial ML intro (2023)
  * [Slides](https://docs.google.com/presentation/d/1jT2biH6DIlN133djneZcdXS7-CgR-dlWm2jBQ1KhM50) - EE classifiers (2023)
    * [Video](https://www.youtube.com/watch?v=arqbzovtQTo) 🎥 (2023)
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

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/gee_clusterers_2025-07.PNG)

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/gee_classifiers_2025-07.PNG)

## 4. Resources: Deep Learning (DL)

**"Everybody else is doing [*Deep Learning*], so why can't we?"**

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/cranberries_dl_small2.png)

*source*: modified from the Cranberries' "Everybody Else is Doing It, So Why Can't We?" album cover (1993)

**TensorFlow resources**

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/dl_01.PNG)

*source*: Google


## 4.a. General DL resources from organizations
*Resources from Development Seed*
* Development Seed (2021): Deep Learning overview resources developed for SERVIR Amazonia: GitHub [repo](https://github.com/developmentseed/servir-amazonia-ml)
* Development Seed (2021): Deep Learning overview resources developed for SERVIR Amazonia: Jupyter Book
  * 1: [Introduction to ML, Neural Networks (NN), and DL](http://devseed.com/servir-amazonia-ml/docs/Lesson1a_Intro_ML_NN_DL.html)
  * 2: [Introduction to TensorFlow & Keras](http://devseed.com/servir-amazonia-ml/docs/Lesson1b_Intro_TensorFlow_Keras.html)
  * 3: [Accessing Planet / NICFI mosaic data](http://devseed.com/servir-amazonia-ml/docs/Lesson2a_get_planet_NICFI.html)
  * 4: [Processing data for use in DL](http://devseed.com/servir-amazonia-ml/docs/Lesson2b_prep_data_ML_segmentation.html)
  * 5: [Semantic segmentation with DL](http://devseed.com/servir-amazonia-ml/docs/Lesson3_deeplearning_crop_segmentation.html)
  * 6: [Evaluating semantic segmentation models](http://devseed.com/servir-amazonia-ml/docs/Lesson4_evaluation.html)
  * 7: [Dealing with limited data for semantic segmentation](http://devseed.com/servir-amazonia-ml/docs/Lesson5_dealing_with_limited_data.html)


*Resources from SERVIR*
* SERVIR (2019): TensorFlow basics overview by Kel Markert
  * [Slides](https://docs.google.com/presentation/d/1dXJOrNrqSzksN_TrzKPby5mZqZm9_YXJJ-nCcqdkGFU/edit#slide=id.p) ➡️ complementary to Google’s 2022 DL slide deck
  * Colab [notebook](https://colab.research.google.com/drive/1dGj-j2V_xk8M5o_9i1tBxuE4ZFQEaoyZ)
* SERVIR Geo AI Working Group (formerly TensorFlow Working Group) [resources (2019-present)](https://sites.google.com/uah.edu/2020-tensorflow-technical-exch/home/resources)
* SERVIR Geo AI Working Group presentation [videos (~2022-present)](https://www.youtube.com/playlist?list=PLKlxghiZuIM59XVSjuye43qcHXRZLwQNN) 🎥
* Overview of how GEE connects to Google Cloud and AI (Sept. 2019): "Understanding the workflow between the Tensorflow library, Google Cloud Platform, Google Earth Engine, and Google Colab is a challenging undertaking..." (T. Mayer / SERVIR SCO)

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/dl_02.PNG)

*Resources from Spatial Thoughts*
* Building a Deep Neural Network
  * [Slides](https://docs.google.com/presentation/d/1hPVRnxp2Vp1VHXBtu36SH_UtEOjPz70KcDV-zGIin3U/edit#slide=id.ge30b5f6dd9_0_33) / [Video](https://youtu.be/34yNkLmEHAI?t=5957) 🎥
  * [Colab Notebook](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/tf_gee_dnn_model.ipynb) → *this can be run using local (i.e. desktop or laptop) resources, per these [instructions](https://research.google.com/colaboratory/local-runtimes.html)*

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/dl_03.PNG)

*source*: [U. Gandhi / Spatial Thoughts (2024)](https://youtu.be/34yNkLmEHAI?t=5197)

*Resources from Google*
* Google (2019): Overview of the connections between GEE, Google Cloud, and the AI Platform (now formally, "Vertex AI"):

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/dl_04.PNG)

*source*: [N. Clinton, C. Brown / Google (2019)](https://medium.com/google-earth/down-to-earth-with-ai-platform-7bc363abf4fa)

* Google (2022): Overview of implementing DL using GEE and TensorFlow
  * [Slides](https://docs.google.com/presentation/d/1HcbbEnC0wbGfp-d6qXbVkcBryP0acNlBKeMCsDCUXpw/edit#slide=id.g15d38b5130c_10_137)
  * [Video](https://www.youtube.com/watch?v=aiqAN1Zlhdk) 🎥
  * [Colab Notebook](https://colab.research.google.com/drive/1QuKj2U5ekiUMYTJC6qpEK3F1unOlCUej)

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/dl_05.PNG)

*source*: [Google (2022)](https://docs.google.com/presentation/d/1HcbbEnC0wbGfp-d6qXbVkcBryP0acNlBKeMCsDCUXpw/edit#slide=id.g15d38b5130c_10_137)

* Google (2023): 
  * [Slides](https://docs.google.com/presentation/d/1e5ppyNts-KJx1YIawP-04QxkAXelOrjzKJ0HPpwNILY)
  * Video 🎥 ([part 1](https://www.youtube.com/watch?v=_BjtxPSO1Ho), [part 2](https://www.youtube.com/watch?v=2iiC1p69-EY))
  * Colab notebooks
    * [Part 1](https://colab.research.google.com/drive/1jHgVUls9w0y4HmndV-mpvyZ6yrNuvrjk?usp=sharing): Tables
    * [Part 2.1](https://colab.research.google.com/drive/1NgEB1G17ahL8roNdaDP-UBMbjfyv8XJA?usp=sharing): Generating training data
    * [Part 2.1.1](https://colab.research.google.com/drive/1No82eyqGcsklsKh5H2LFtDGg92pBhHkz): Data flow (transfer)
    * [Part 2.2](https://colab.research.google.com/drive/1KdCNaqYFgAk9ohEF5hWIh7eRkHDPL2-m): Model training on Vertex AI
    * [Part 2.3](https://colab.research.google.com/drive/1v0o5MEDxSkUT-Eg0RXo2u7rj4oPdZ0Lg): Model prediction

* Google (2024): Deep Learning with Earth Engine & Vertex AI
  * [Slides](https://docs.google.com/presentation/d/1eNJDIoJg-ADrxC09JIzl00frjyseEc917rItTDPalGI)
    * [Embeddings (1)](https://docs.google.com/presentation/d/1ZfBYUNV1w377rkxc3REm5_evyzMJF6szxXGBszKC7uw/edit#slide=id.g3012811fd68_0_1316)
    * [Embeddings (2)](https://docs.google.com/presentation/d/1azsWfeDuC-ZF5L8LNuWAEe49UOsxC-pPvqyZvSvJThk/edit#slide=id.g303d69aca51_0_197)
  * Colab Notebook: [Soybean mapping](https://colab.research.google.com/drive/1Iip9Li7ZguMxKUjZ4mbcg_q1EDyAvUB2)
  * [Other Vertex AI examples](https://developers.google.com/earth-engine/guides/ml_examples#multi-class-prediction-with-a-dnn-hosted-on-vertex-ai)

* Google (2025)
  * Embeddings (Embedding Field Model)
    * GEE Data Catalog [entry](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_SATELLITE_EMBEDDING_V1_ANNUAL)
    * [Blog post](https://medium.com/google-earth/ai-powered-pixels-introducing-googles-satellite-embedding-dataset-31744c1f4650)
    * [White paper](https://storage.googleapis.com/deepmind-media/DeepMind.com/Blog/alphaearth-foundations-helps-map-our-planet-in-unprecedented-detail/alphaearth-foundations.pdf)
    * [Slides (with code links)](https://docs.google.com/presentation/d/1BwKuuKrC29hiGccuACaKUO6WACJ2bb7gqB31_zETdHI/edit?slide=id.g35452590b7b_2_1035#slide=id.g35452590b7b_2_1035) - *from the ESA Living Planet Symposium*
    * Tutorials
      * [Part 1](https://developers.google.com/earth-engine/tutorials/community/satellite-embedding-01-introduction): Intro
      * [Part 2](https://developers.google.com/earth-engine/tutorials/community/satellite-embedding-02-unsupervised-classification): Unsupervised classification
      * [Part 3](https://developers.google.com/earth-engine/tutorials/community/satellite-embedding-03-supervised-classification): Supervised classification
      * [Part 4](https://developers.google.com/earth-engine/tutorials/community/satellite-embedding-04-regression): Regression
      * [Part 5](https://developers.google.com/earth-engine/tutorials/community/satellite-embedding-05-similarity-search): Similarity search

*Resources from other sources*
* Deep learning for land cover classification example (2023) - from [@Ramiqcom](https://www.youtube.com/@ramiqcom)
  * [Video](https://www.youtube.com/watch?v=NFoZPyQqVRA) 🎥
  * [GEE script](https://code.earthengine.google.com/49ccc840cb05e39282cc9d4ca88d82e0)
  * [Colab notebook](https://colab.research.google.com/drive/1mtzWCo4mczLuSjYZiD7JLicNH2jhsljD)



## 4.b. Software-specific DL resources

*ArcGIS-related resources*

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/esri_dl_defns_2024.PNG)

*source*: [Esri (2021)](https://www.esri.com/arcgis-blog/products/arcgis-pro/imagery/deep-learning-with-arcgis-pro-tips-tricks-part-2/)

* "Demystifying Geo AI" [article](https://www.esri.com/about/newsroom/arcnews/demystifying-geoai/) 2023
* "Land Cover Mapping using Pretrained Deep Learning Models" [article](https://www.esri.com/arcgis-blog/products/arcgis/imagery/pretrained-land-cover-models/) 2023
* "GeoAI: Artificial Intelligence in GIS" [book](https://www.esri.com/en-us/esri-press/browse/geoai-artificial-intelligence-in-gis) 2025
* Deep learning in ArcGIS Pro 3.x
  * [Overview](https://www.esri.com/arcgis-blog/products/arcgis-pro/geoai/deep-learning-for-image-analyst-whats-new-in-arcgis-pro-3-2/): "Deep Learning for Image Analyst – What’s New in ArcGIS Pro 3.2" (2023)
  * [Overview](https://www.esri.com/arcgis-blog/products/arcgis-pro/geoai/whats-new-for-geoai-in-the-image-analyst-extension-of-arcgis-pro-3-3/): "What's new for GeoAI in the Image Analyst extension of ArcGIS Pro 3.3" (2024)
  * [Classifying pixels using DL with ArcGIS' Image Analyst](https://pro.arcgis.com/en/pro-app/latest/tool-reference/image-analyst/classify-pixels-using-deep-learning.htm)
  * [Classifying objects using DL with ArcGIS' Image Analyst](https://pro.arcgis.com/en/pro-app/latest/tool-reference/image-analyst/classify-objects-using-deep-learning.htm)
  * [Pixel classification](https://pro.arcgis.com/en/pro-app/latest/tool-reference/image-analyst/pixel-classification.htm) ➡️ "In this case of sparse training samples as below, you must set the ignore class parameter to 0. This will ignore the pixels that have not been classified for training."
  * [Selecting DL model type](https://support.esri.com/en-us/knowledge-base/problem-train-deep-learning-model-model-type-not-found--000025249) ➡️ "Classify pixels using deep learning" → "Classified tiles" option
  * [Deep learning toolset](https://pro.arcgis.com/en/pro-app/latest/tool-reference/image-analyst/an-overview-of-the-deep-learning-toolset-in-image-analyst.htm) ➡️ explanation of the main ArcGIS DL tools
  * [Deep learning model architectures](https://pro.arcgis.com/en/pro-app/latest/tool-reference/image-analyst/train-deep-learning-model.htm) ➡️ **really useful to review** 😉
  * [Training Deep Learning Model (Image Analyst)](https://pro.arcgis.com/en/pro-app/latest/tool-reference/image-analyst/train-deep-learning-model.htm)
  * [Deep learning model review](https://pro.arcgis.com/en/pro-app/latest/help/analysis/image-analyst/deep-learning-model-reviewer.htm)
  * [Pretrained Deep Learning Models](https://www.esri.com/en-us/arcgis/deep-learning-models)
    * "Introducing pretrained geospatial deep learning models" [article](https://www.esri.com/arcgis-blog/products/arcgis/imagery/introducing-ready-to-use-deep-learning-models/) (2020)
    * [Pixel classification models](https://livingatlas.arcgis.com/en/browse/?q=dlpk%20classification#d=2&q=dlpk+classification)
      * [Mangrove classification using Landsat-8](https://www.arcgis.com/home/item.html?id=741a56ae6a5340058b9704a8f68f1b9a)
      * [Land cover classification using Landsat-8](https://www.arcgis.com/home/item.html?id=e732ee81a9c14c238a14df554a8e3225)
      * [Land cover classification using Sentinel-2](https://www.arcgis.com/home/item.html?id=afd124844ba84da69c2c533d4af10a58)
      * [Land cover classification using aerial photography](https://www.arcgis.com/home/item.html?id=a10f46a8071a4318bcc085dae26d7ee4)
    * Prithvi-related [models](https://livingatlas.arcgis.com/en/browse/?q=prithvi#d=1&type=tool&itemTypes=Deep+Learning+Package&q=prithvi) (via IBM / NASA)
    * Segment Anything Model (SAM) [instructions](https://doc.arcgis.com/en/pretrained-models/latest/imagery/using-segment-anything-model-sam-.htm)
    * Deep Learning package for ArcGIS
      * Installation [notes](https://pro.arcgis.com/en/pro-app/latest/help/analysis/deep-learning/install-deep-learning-frameworks.htm)
      * [Installers](https://github.com/Esri/deep-learning-frameworks?tab=readme-ov-file)
    * [Non-Esri] [Quick Intro to Deep Learning Classifications in ArcGIS Pro](https://www.youtube.com/watch?v=jV-U1RI_qus) (2023)
* Deep learning via ArcGIS API for Python [page](https://developers.arcgis.com/python/samples/land-cover-classification-using-unet/) (2022)
* Esri Jupyter notebooks setup [instructions](https://guides.lib.purdue.edu/DataScience/ArcGISPro) (from Purdue U.)
* Example classification tutorial [video](https://www.youtube.com/watch?v=nFbxIek4Tiw) 🎥 (from GeoTown)
* Esri community [forum](https://community.esri.com/t5/custom/page/page-id/Communities)
  * [Questions](https://community.esri.com/t5/arcgis-pro-questions/suggestions-for-deep-learning-backbone-model-for/m-p/1538698) about deep learning patch sizes (14 Sept. 2024)
  * [Questions](https://community.esri.com/t5/arcgis-pro-questions/deep-learning-tools-not-working-in-arcgis-pro-3-4/m-p/1556677#M89931) about installation of v. 3.4 (7 Nov. 2024)
* Esri Australia GIS Directions [podcast episodes](https://esriaustralia.com.au/resources/podcasts/gis-directions/homepage) on Machine Learning


![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/arcgis_dl_tools_v_3_3.PNG)

*source*: screenshot from ArcGIS Pro v. 3.3


*QGIS-related resources*
* General list of [QGIS plugins](https://plugins.qgis.org/plugins/tags/deep-learning/) referencing DL
* QGIS Deepness: Deep Neural Remote Sensing [plugin](https://plugins.qgis.org/plugins/deepness/) (2024) 🆕
  * Documentation [page](https://qgis-plugin-deepness.readthedocs.io/en/latest/)
  * “[Model Zoo](https://qgis-plugin-deepness.readthedocs.io/en/latest/main/main_model_zoo.html)”
* QGIS Deep Learning Tools [plugin](https://plugins.qgis.org/plugins/DeepLearningTools/) (2021)
* QGIS Deep Learning Datasets Maker [plugin](https://plugins.qgis.org/plugins/deep-learning-datasets-maker/) (2022)


*ENVI-related resources*
* Overview of the ENVI Deep Learning Process [page](https://www.nv5geospatialsoftware.com/docs/OverviewENVIDeepLearning.html)
* ENVI Deep Learning Guide [Map](https://www.nv5geospatialsoftware.com/docs/guidemap.html)
* What's New in ENVI Deep Learning 3.0 [page](https://www.nv5geospatialsoftware.com/docs/deep_learning_WhatsNew.html)
* ENVI Deep Learning system requirements [page](https://www.nv5geospatialsoftware.com/docs/systemrequirements.html)
* Train Deep Learning Models Using the ENVI Modeler [page](https://www.nv5geospatialsoftware.com/docs/trainusingmodeler.html)

*R-related resources*
* NeuralNet package basic [documentation](https://cran.r-project.org/web/packages/neuralnet/index.html)
* Torch (PyTorch) package basic [documentation](https://cran.r-project.org/web/packages/torch/index.html)
  * ReddIt thread re: packaging of PyTorch / TensorFlow in R → *“Has anyone else noticed that there do not seem to be many packages in R that allow for Neural Networks and Deep Learning (with the exception of "nnet")? It seems that any time and R user would like to fit Neural Networks, they are "forced" to use the R version of "keras" (through "reticulate") - ultimately, the fitting of the Neural Network is done behind the scenes in Python.”*
* DataCamp [tutorial](https://www.datacamp.com/tutorial/neural-network-models-r) for building a neural network in R using NeuralNet, Keras, and TensorFlow packages
* Udemy course preview [video](https://youtu.be/xrBkTy_F-h8?t=226) 🎥 about neural networks in R (2019) → Udemy [course](https://www.udemy.com/course/how-to-use-ann-for-prediction-mapping-using-gis-data/)


![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/oversized_salad_dl2.png)

## 5. Resources: Uncertainty assessment / accuracy assessment

* General accuracy assessment
  * ArcGIS Desktop: Accuracy Assessment for Image Classification [page](https://desktop.arcgis.com/en/arcmap/latest/manage-data/raster-and-images/accuracy-assessment-for-image-classification.htm)
  * ArcGIS Pro: Accuracy Assessment [page](https://pro.arcgis.com/en/pro-app/latest/help/analysis/image-analyst/accuracy-assessment.htm)
  * GEE: Export training samples [script](https://developers.google.com/earth-engine/apidocs/export-table-todrive)
  * QGIS: Accuracy assessment [plugin](https://plugins.qgis.org/plugins/accassess/)

* Accuracy assessment of land cover data applying statistical best practices
  * Area Estimation & Accuracy Assessment (AREA2) toolbox
    * GitHub page: https://github.com/bullocke/AREA2/blob/master/README.md
    * GEE repository: https://code.earthengine.google.com/?accept_repo=projects/AREA2/public

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/graphic_ml_algorithm_accuracy_metwalli.png)

[*source*](https://towardsdatascience.com/how-to-choose-the-right-machine-learning-algorithm-for-your-application-1e36c32400b9): Sara A. Metwalli / Towards Data Science (2020)

* The issue of training, validation, and test data
  * Training, validation, and test data sets (Wikipedia): https://en.wikipedia.org/wiki/Training,_validation,_and_test_data_sets
  * Definitions (from J. Brownlee, 2020): https://machinelearningmastery.com/difference-test-validation-datasets/

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/graphic_validation_brownlee.png)
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
* U.S. General Services Administration (GSA) Artificial intelligence [community of practice](https://www.gsa.gov/technology/government-it-initiatives/artificial-intelligence/ai-community-of-practice)
* Oak Ridge National Lab [Trillion Pixel Challenge](https://geoai.ornl.gov/trillion-pixel/)
  * Sept. 2019 workshop [report](https://geoai.ornl.gov/trillion-pixel/wp-content/uploads/sites/2/2021/03/Trillion_Pixel_Challenge_Workshop_Report-for-public-release.pdf)
  * July 2023 workshop [press release](https://www.ornl.gov/news/trillion-pixel-challenge-looks-ahead-next-decade-geoai-innovation)
  * Sept. 2024 workshop [report](https://geoai.ornl.gov/trillion-pixel/wp-content/uploads/sites/2/2025/06/2024_GeoAI_Trillion_Pixel_Workshop_Report.pdf)

* Statistical Machine Intelligence and Learning Engine [(SMILE)](https://haifengl.github.io/classification.html)
  * Google: SMILE Naive Bayes [documentation](https://developers.google.com/earth-engine/apidocs/ee-classifier-smilenaivebayes)

* Other ['open source GIS tutorials'](https://dges.carleton.ca/CUOSGwiki/index.php/Main_Page) from Carleton University (Canada)
  
* How to open a Google Colab Notebook from Github in [Google Colab](https://colab.research.google.com/): "*Just change the domain from 'github.com' to 'githubtocolab.com' and the notebook will open in Colab.*" [source](https://stackoverflow.com/questions/62596466/how-can-i-run-notebooks-of-a-github-project-in-google-colab#:~:text=Open%20Github%20notebook%20whatever%20you,notebook%20will%20open%20in%20Colab)


**Neural networks + deep learning in general**
* Neural networks explainer [video](https://www.youtube.com/watch?v=X22ENbm4BfU) 🎥 from Esri ➡️ *great contrast* w/ Random Forest explainer [video](https://www.youtube.com/watch?v=HL0nz9uOtF8) 🎥

## 7. Software installers

* ArcGIS Pro 3.x deep learning package [installers](https://github.com/Esri/deep-learning-frameworks?tab=readme-ov-file#download) ➡️ *current to ArcGIS Pro 3.5* 👀
* QGIS
  * Main program [installer](https://qgis.org/download/)
  * Deep learning [plugins](https://plugins.qgis.org/search/?q=deep+learning)
* R
  * Main program
    * [Linux installers](https://cran.r-project.org/bin/linux/)
    * [macOS installers](https://cran.r-project.org/bin/macosx/)
    * [Windows installers](https://cran.r-project.org/bin/windows/base/)
  * R Studio *v.2025.05.1+513* [installer](https://download1.rstudio.org/electron/windows/RStudio-2025.05.1-513.exe)
* SNAP [installers](https://step.esa.int/main/download/snap-download/)
* TerrSet [installers](https://github.com/ClarkCGA/terrset/releases)


## Citation

If this documentation is used in publications, presentations, or other venues, please cite 📝 the following:

Cherrington, E. (2025). Geo AI Compendium (Version 1.0.0) [Document]. https://doi.org/10.5281/zenodo.16735094

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16735094.svg)](https://doi.org/10.5281/zenodo.16735094)


## Contact information

If you have any questions, feel free to contact Emil Cherrington by :envelope_with_arrow: email: **emil.cherrington [at] uah.edu**.

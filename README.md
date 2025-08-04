# GeoAI Compendium:
## Geospatial 🗺️ artificial intelligence / machine learning (Geo AI / Geo ML) 👨‍💻 resources focused on land cover monitoring 🛰️🏞️

*compiled by Emil A. Cherrington, Ph.D.*

[![Update](https://img.shields.io/github/last-commit/bzgeo/Geo_AI_compendium?label=last%20updated&style=flat-square)](https://github.com/BzGEO/Geo_AI_compendium)

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/word_cloud_v2023-05-05b.PNG)

## Overview

1. [Objectives](https://github.com/BzGEO/Geo_AI_compendium/#1-objectives)
2. [Schematics](https://github.com/BzGEO/Geo_AI_compendium/#2-schematics)
3. [Resources: Machine learning (classical)](https://github.com/BzGEO/Geo_AI_compendium/#3-resources-machine-learning-classical--traditional)
4. [Resources: Deep learning](https://github.com/BzGEO/Geo_AI_compendium/#4-resources-deep-learning)
5. [Resources: Uncertainty / accuracy assessment](https://github.com/BzGEO/Geo_AI_compendium/#5-resources-uncertainty--accuracy-assessment)
6. [Resources: Other](https://github.com/BzGEO/Geo_AI_compendium/tree/#6-resources-other)

## 1. Objectives

* Document the various Machine Learning approaches available across various [desktop + cloud] platforms (e.g. [ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview), [ENVI](https://www.nv5geospatialsoftware.com/Products/ENVI), [ERDAS Imagine](https://hexagon.com/products/erdas-imagine), [GEE](https://code.earthengine.google.com/), [QGIS](https://qgis.org/),[R](https://cran.r-project.org/), [SNAP](https://step.esa.int/main/download/snap-download/), [TerrSet](https://github.com/ClarkCGA/terrset))
  * Compile resources (including tutorials and sample scripts) regarding how to implement those approaches in the platforms listed ⬆️
  * Understand how to replicate ML workflows from one platform to another
* Understand the limitations of the various ML approaches 🤔
  * Push the limits of the various approaches
  * *For instance, what determines the taste of the cake? The quality of the ingredients used, or the technique of the baker?* 🤔

## 2. Schematics

* Overview of the distinctions between Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning (DL)

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/venn_diagram_ai_small.png)

*source*: [Human Centered AI Lab (2017)](https://human-centered.ai/wordpress/wp-content/uploads/2017/11/Deep-Learning-subset-of-Machine-Learning-subset-of-Artificial-Intelligence.jpg)

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

*source*: [SciKit-Learn](https://scikit-learn.org/stable/modules/svm.html)


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

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/gee_clusterers_2025-07.PNG)

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/gee_classifiers_2025-07.PNG)

## 4. Resources: Deep Learning (DL)

🚨 *This section is still in progress.* 🚨

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/cranberries_dl_small2.png)

*source*: modified from the Cranberries' "Everybody Else is Doing It, So Why Can't We?" album cover (1993)

**TensorFlow resources**

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/dl_01.PNG)

*source*: Google


## 4.a. General DL resources from organizations
*Resources from Development Seed*
* Development Seed (2021): Deep Learning overview resources developed for SERVIR Amazonia: GitHub [repo](https://github.com/developmentseed/servir-amazonia-ml]
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
* SERVIR Geo AI Working Group (formerly TensorFlow Working Group) [resources](https://sites.google.com/uah.edu/2020-tensorflow-technical-exch/home/resources)
* SERVIR Geo AI Working Group presentation [videos](https://www.youtube.com/playlist?list=PLKlxghiZuIM59XVSjuye43qcHXRZLwQNN)
* Overview of how GEE connects to Google Cloud and AI (Sept. 2019): “Understanding the workflow between the Tensorflow library, Google Cloud Platform, Google Earth Engine, and Google Colab is a challenging undertaking… (T. Mayer / SERVIR SCO)

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/dl_02.PNG)

*Resources from Spatial Thoughts*
* Building a Deep Neural Network
  * [Slides](https://docs.google.com/presentation/d/1hPVRnxp2Vp1VHXBtu36SH_UtEOjPz70KcDV-zGIin3U/edit#slide=id.ge30b5f6dd9_0_33) / [Video](https://youtu.be/34yNkLmEHAI?t=5957)
  * [Colab Notebook](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/tf_gee_dnn_model.ipynb) → *this can be run using local (i.e. desktop or laptop) resources, per these [instructions](https://research.google.com/colaboratory/local-runtimes.html)*

![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/dl_03.PNG)

*source*: [U. Gandhi / Spatial Thoughts (2024)](https://youtu.be/34yNkLmEHAI?t=5197)

*Resources from Google*


## 4.b. Software-specific DL resources

*ArcGIS-related resources*

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
* Udemy course preview [video](https://youtu.be/xrBkTy_F-h8?t=226) about neural networks in R (2019) → Udemy [course](https://www.udemy.com/course/how-to-use-ann-for-prediction-mapping-using-gis-data/)



![](https://github.com/BzGEO/Geo_AI_compendium/blob/main/_graphics/oversized_salad_dl2.png)



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

## Contact information

If you have any questions, feel free to contact Emil Cherrington by :envelope_with_arrow: email: **emil.cherrington [at] uah.edu**.

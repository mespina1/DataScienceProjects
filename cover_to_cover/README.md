# Cover to Cover A (not so) Novel Approach to Book Recommendations
**Description:** Cover to Cover is a Content Based Image Retrieval recommender system  of the Amazon book covers dataset utilizing similarity algorithms in Computer Vision.

## The project files

Cover_to_cover.ipynb contains the Similarity based Image Recommendation System

genre_classification.ipynb explores the relationship between genre and cover design features with Neural network modeling


**NOTE:** If Notebooks are not rendering please copy the url and go to https://nbviewer.jupyter.org/ to view the files

## Directories:

models/ contains all models used for the Project (including the pre-trained cocoresNet50 model for object Detection)

model_history/ contains results from ALL tests on data set

modeling_pipeline/ contains code for neural network pipeline and plotting function used in genre_classification, the notebook contains full documentation of pipeline for reference purposes. 

image_detections/ contains all code and modeling for object detection attempts referenced in cover_to_cover.ipynb

the Image-AI library for object detection can be downloaded at via pip at https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.2/imageai-2.0.2-py3-none-any.whl

data_crawler_scripts/ contains modified python and shell scripts for retrieving book cover images from https://github.com/uchidalab/book-dataset and use these scripts to bypass errors from missing/broken image urls



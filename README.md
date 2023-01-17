# AI-Snails-YOLOv4-object-detection


## Introduction
This is a project for AI Snails to detect objects using YOLOv4.

## Images - dataset

To help you get started, our images are available at [firefly-cpp/snail-dataset](https://github.com/firefly-cpp/snail-dataset)

I have also found a dataset of snail images on Kaggle: [Slug detect dataset on Kaggle](https://www.kaggle.com/datasets/tegwyntwmffat/slug-detect).

## IPYNB - Jupyter Notebook information

The Jupyter Notebook is available in this repository. It is meant to be runnder from Google Colab. You can also run it locally if you have the necessary dependencies installed and change the path to the files.

Absolute path: "./Colab Notebooks/yolo/yolov4", path to folder and files.
* yolov4-tiny.conv.29 (pre-weighted mmodel, downloaded automatically from code)
* obj.zip (ziped images uploaded to gDrive)
* slug_images_and_txt_files_01.tar.gz (additional images, FugSlucks, uploaded to gDrive)
* obj.names (name of category for object detection - snail, created automatically in code)
* obj.data (No. of classes, folder, ..., created automatically in code)
* /backup/ (folder where models are saved during training in case of suspension, best and last model ("./Colab Notebooks/yolo/yolov4/backup/"))
* yolov4-tiny-custom.cfg (config, copied from gDrive, included in repository)
* train.txt (images for training, created automatically in code)
* test.txt (images for test, created automatically in code)
* /testSlike/ ((test) images that have not been in training dataset)
* /testSlikeOznacene/ (tagged test images - output from our model - results from object detection) 

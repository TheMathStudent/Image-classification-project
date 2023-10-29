# Introduction

This is Team 20’s final project for Skoltech 2023 Foundations of Software Engineering course. 
This repository contains a neural network (https://huggingface.co/akahana/vit-base-cats-vs-dogs) which was trained on a large dataset of cat and dog images (https://huggingface.co/datasets/cats_vs_dogs). The code achieves the goal of classification of cat and dog images. 

# Image-classification-project

Create a `.env` inside the `services` directory file with the following content:
```
IMGS_ROOT=<PATH_TO_YOUR_IMAGES_DIRECTORY>
IMG_PATH=/root/images
```

For run a script inside the docker you should go to `services` directory
```
cd services
```
and run
```
sudo IMG=<IMAGE_NAME> docker compose up
```

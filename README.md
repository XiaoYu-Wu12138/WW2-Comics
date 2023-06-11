# Linking Entities Across Texts and Images in Comics
<img src="Method1.jpeg" width="800"> 

## Updates

* 6/2023: Updated Method2-MDETR model (in comics and standard settings) 

* 6/2023: Updated Entity Pairs Ranking and CLIP in naturalistic/standard settings where the images are retrieved from the test set in the [Flickr30k dataset](https://github.com/BryanPlummer/flickr30k_entities)

* 5/2023: Updated Method2-CLIP model (in comics) 

* 4/2023: Updated Method1-Entity Pairs Ranking (in comics) and three csv files from [Kaggle WW2 database](https://www.kaggle.com/datasets/ramjasmaurya/world-war-2-archive)

* 3/2023: Updated Exploratory Data Analysis 

## Introduction
This repository is dedicated for a Master Thesis Project.  

Comics, a medium with distinctive structures, present an opportunity for exploring the intersection of visual and language content. In this work, we delve into the field of **visual grounding** in comics, a visual semantic task that aims to connect entities in speech bubbles with those depicted within the image. 

Unlike previous research in visual grounding which primarily focuses on naturalistic images, our study puts the spotlight on comics and presents two novel approaches to address this task. 

1. **Method 1: Entity Pairs Ranking** ranks the image-text pairs retrieved from object detection and Optical Character Recognition (OCR) models. 
2. **Method 2: Visual Language Transformer** adopts a transformer-based model that learns to integrate image-text representations. 


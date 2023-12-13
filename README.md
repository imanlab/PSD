# Picking Scheduling Dataset

## Table of Contents

* [About the Project](https://github.com/imanlab/PSD/blob/main/README.md#about-the-project)
* [Contents](https://github.com/imanlab/PSD/blob/main/README.md#contents)
  *[Annotations](https://github.com/imanlab/PSD/blob/main/README.md#Annotations)
     *[Hardness of Picking](https://github.com/imanlab/PSD/blob/main/README.md#Hardness-of-picking)
     *[Degree of Ripeness](https://github.com/imanlab/PSD/blob/main/README.md#degree-of-ripeness)
* [Contacts](https://github.com/imanlab/PSD/blob/main/README.md#contacts)
  
   
  


## About the Project
This repository contains the dataset and the annotations that have been used for the straberry picking scheduling.

## Contents

The dataset is divided in two folders, **data_collection** and **riseholme**.  

In each of these folder the pictures are divided in **train**, **test** and **val** containg respectively 70%, 20% and 10% of the dataset. 

### Annotations
The annotations are contained in the **segmentations_v2** folder, which is present in both **data_collection** and **riseholme** folder. 
The annotations are saved in .csv, .json and coco format. 

#### Hardeness of Picking

The Hardness of Picking has been classified with 5 different levels from 0 to 4 as:

* 0: Uncluttered
* 1: to 10% of the strawberry is cluttered
* 2: 10% - 80% of the strawberry is cluttered
* 3: 80% - 100% of the strawberry is cluttered
* 4: Out of range (too far to pick)

#### Degree of Ripeness

The Degree of Ripeness has been classified with 5 different levels from 0 to 4 as:

* 0: Unripe
* 1: to 50% ripe
* 2: to 90% ripe
* 3: Ripe
* 4: Rotten
  
## Contacts

clara.bresciani@mail.polimi.it



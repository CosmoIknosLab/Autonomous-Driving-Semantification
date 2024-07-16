# Semantification of Autonomous Driving Datasets

In this repository, we have the **FAIR activities** for the sanctification of _three_ different datasets related to the Autonomous Driving domain. 
The objective is to semanticise datasets in the autonomous driving domain, assigning semantic labels to the instances, and in particular to the objects present in the instances, in order to standardise these labels according to standards defined by domain ontologies.
Semanticisation is carried out according to a protocol involving the following steps:
- You define and describe the selected dataset, extracting from it all the classes that you choose to semantify;
- All the labels corresponding to a class in the ontology are identified;
- We proceed, where possible, to map 1:1 the class of the dataset with a class of the ontology with similar meaning to the label. If a total match cannot be found, the decision is made to map the class to one with similar meaning within the ontology, or one that is semantically similar to the class assigned to the object;
- The semanticisation process ends when all classes have been mapped with at least one ontology label.

## Activities

- Dataset Selection: for the project we have chosen the following dataset, **KITTI**, **CityScapes** and **A2D2**;
- Dataset Semantification: the semantification process regarding the link of the class label to an ontological label. For the ontology we have chosen **TTCar Toyota Ontology**.

## Process Description

The semantification process requires the ontology to have a more excellent coverage of the classes of all datasets. To use the Toyota Ontology for the process, an ontology extension was made, adding the missing ontology classes to cover all the cases of the three selected datasets.

# Dataset Description

## 1.	KTTI Dataset

The KITTI dataset was co-founded by Karlsruhe Institute of Technology in Germany and Toyota American Institute of Technology. It is a computer vision algorithm evaluation dataset in autonomous driving scenarios. This dataset is used to evaluate the performance of computer vision technologies such as stereo, optical flow, visual odometry, 3D object detection and 3D tracking in vehicle environments.First released in 2012 by Geiger et al, the KITTI dataset was released with the intent of advancing autonomous driving research with a novel set of real-world computer vision benchmarks. One of the first ever autonomous driving datasets, KITTI boasts over 4000 academic citations and counting.

## 2.	CityScapes Dataset 

CityScapes is a public dataset jointly released by the Mercedes-Benz Autonomous Driving Laboratory, the Max Planck Institute, and Darmstadt University of Technology, focusing on the semantic understanding of urban street scenes. The dataset contains 50 different cities, various stereoscopic video sequences recorded in street scenes under different seasons and weather conditions. The Cityscapes dataset has two sets of evaluation criteria: fine and coarse. The former provides 5000 finely annotated images, the latter provides 5000 finely annotated images plus 20000 coarsely annotated images. CityScapes is a large-scale dataset focused on the semantic understanding of urban street scenes in 50 German cities. It features semantic, instance-wise, and dense pixel annotations for 30 classes grouped into 8 categories. The entire dataset includes 5,000 annotated images with fine annotations, and an additional 20,000 annotated images with coarse annotations.

## 3.	A2D2 Dataset

Audi’s large autonomous driving dataset A2D2. This dataset provides camera, LiDAR, and vehicle bus data, allowing developers and researchers to explore multimodal sensor fusion methods. The sensor suite includes six cameras and five LiDAR units for full 360-degree coverage. The data mainly comes from German streets, including RGB images, but also the corresponding 3D point cloud data. The recorded data is time-synchronized.The Audi Autonomous Driving Dataset (A2D2) features over 41,000 labeled with 38 features. Around 2.3 TB in total, A2D2 is split by annotation type (i.e. semantic segmentation, 3D bounding box). 

# Ontology Extension

The class added regarding the following labels: **Person**, that have **Pedestrian**, **Cyclist** and **Person Sitting** classes as childrens, **Van** as a Automobile children, and **Tram** as a Special Vehicle. The image report the updated version of the Toyota Ontology:
![image](https://github.com/user-attachments/assets/663897c0-01df-4c76-acb4-89812c477888)


















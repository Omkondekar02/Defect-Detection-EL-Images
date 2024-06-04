# Defect-Detection-EL-Images

Within this project, I implemented a Residual Neural Network in PyTorch and used it for classifying defects of solar cells. Solar cells can exhibit various types of degradation caused by inappropriate transportation, installation, or bad weather conditions such as wind or hail. The model implemented here focuses on the classification of 5 different types of defects described in more detail below. An Inception -v3 from PyTorch pre-trained on the ILSVRC2012 ImageNet database is used for this task. All layers were fine-tuned to adapt to the classification of solar-cell defects.
This repository provides a dataset of solar cell images extracted from high-resolution electroluminescence images of photovoltaic modules.

# DataSet
The training and prediction are performed on electroluminescence images of functional and defective solar cells. The original dataset can be found on this GitHub page but was labeled differently for this project.
The Photovoltaic Electroluminescence Anomaly Detection Data Set for Solar Cells ( PVEL-AD), which contains 36,543 images with 2500 unique data in 5 categories, was used
for the training model. This file contains negatives and negative images with 10 different categories including cracks (lines and stars), fingerprints, black veins, dislocations, thick lines, scratches, chips, corners, and product defects.

![image](https://github.com/Omkondekar02/Defect-Detection-EL-Images/assets/102482472/9970b552-9a3c-48c2-a8ad-a7870bdefefb)
![image](https://github.com/Omkondekar02/Defect-Detection-EL-Images/assets/102482472/597e3690-4dad-47ec-9c0f-dcca42ef18af)
![image](https://github.com/Omkondekar02/Defect-Detection-EL-Images/assets/102482472/2df9e615-b4d5-445f-aaf7-c7a56828a7db)
![image](https://github.com/Omkondekar02/Defect-Detection-EL-Images/assets/102482472/77e87974-3fd2-4d14-a9c5-c16b26cdf8cc)
![Uploading image.png…]()





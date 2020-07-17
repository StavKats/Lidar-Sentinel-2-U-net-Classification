# Lidar & Sentinel-2 (U-net Classification)

These files are part of my thesis on researching the impact that LiDAR data have on the accuracy on land cover image classification. The code provided in the repository contains functions that receive an image and create smaller tiles out of it. Also, there are function for reconstruncting the tiles back to the original size and finctions that create a confusion matrix and calculate its errors and accuracy.
I used Tensorflow for training the CNN which is based on the U-net architecture.

## Sentinel-2 & LiDAR

The first application of my thesis used satellite images from Sentinel-2 and ground truth provided from Corine Land Cover 2018.
The are of interest was the small island of Hydra in Greece, thus the polygons used for calculating the confusion matrix of the classification work only for the data I used to train the network.

## RGB & LiDAR

The second application of my thesis used images from the RGB camera that was onboard with the airborne LiDAR system. These images are of high resolution of around 50 cm. The ground truth data used in this application was generated with a supervised classification method (Maximum Likelihood).

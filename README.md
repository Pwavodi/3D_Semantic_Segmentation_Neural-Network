# 3D_Semantic_Segmentation_Neural-Network

Semantic Segmentation Models¶
TASK: Create Pipeline to perform semantic segmentation on point clouds of indoor spaces.

WORKFLOW TO SOLVE THE PROBLEM:

Loading the Pretrianed Dataset that was downloaded from the https://cvg-data.inf.ethz.ch/s3dis/
Data Preprocessing.
This pipeline will incorporate a pretrained segmentation Point Net to get predictions for an input set of points.
Then open3d library will be used to search the point cloud space.
Convert Individual Semantic to Meshes

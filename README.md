# 3D_Semantic_Segmentation_Neural-Network

Semantic Segmentation Models¶
TASK: Create Pipeline to perform semantic segmentation on point clouds of indoor spaces.

WORKFLOW TO SOLVE THE PROBLEM:

1. Loading the Pretrianed Dataset that was downloaded from the https://cvg-data.inf.ethz.ch/s3dis/   
2. Data Preprocessing.    
3. This pipeline will incorporate a pretrained segmentation Point Net to get predictions for an input set of points.    
4. Then open3d library will be used to search the point cloud space.      
5. Convert Individual Semantic to Meshes

# A vector-based method for drainage network analysis based on LiDAR data

Fangzheng Lyu, Zewei Xu, Xinlin Ma, Shaohua Wang, Zhiyu Li, Shaowen Wang, A vector-based method for drainage network analysis based on LiDAR data, Computers & Geosciences, Volume 156, 2021, 104892, ISSN 0098-3004,
https://www.sciencedirect.com/science/article/pii/S0098300421001849

Last Update Date: August 12th, 2021

Drainage network analysis is fundamental to understanding the characteristics of surface hydrology. Based on elevation data, drainage network analysis is often used to extract key hydrological features like drainage networks and streamlines. Limited by raster-based data models, conventional drainage network algorithms typically allow water to flow in 4 or 8 directions (surrounding grids) from a raster grid. To resolve this limitation, this paper describes a new vector-based method for drainage network analysis that allows water to flow in any direction around each location. The method is enabled by rapid advances in Light Detection and Ranging (LiDAR) remote sensing and high-performance computing. The drainage network analysis is conducted using a high-density point cloud instead of Digital Elevation Models (DEMs) at coarse resolutions. Our computational experiments show that the vector-based method can better capture water flows without limiting the number of directions due to imprecise DEMs. Our case study applies the method to Rowan County watershed, North Carolina in the US. After comparing the drainage networks and streamlines detected with corresponding reference data from US Geological Survey generated from the Geonet software, we find that the new method performs well in capturing the characteristics of water flows on landscape surfaces in order to form an accurate drainage network.

This notebook is a sample notebook for running a small size dataset (from the LiDAR dataset of Rowan Watershed) with the proposed method for drainage system analysis. The algorithm is implemented with an execuation sample dataset.

In order to execute this code, user can to download the data at: https://drive.google.com/file/d/1JOl1IylIZg72QdMM89xs10NLFk4rObml/view?usp=sharing


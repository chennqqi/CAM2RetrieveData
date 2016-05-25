# NetworkCameras

This repository contains the code and data for retrieving data (image and video) from network cameras. It has four parts:

* Discovery: discover network cameras. Many network cameras are shown on consolidated web sites (for example, in the web sites of departments of transportation. The programs in this repository analyze the sites to identify network cameras. The programs here also discover the metadata of the cameras (for example, locations and orientations)
* Retrieval: retrieve data from the cameras. After finding the cameras, the data need to be retrieved for further analysis. The programs here are responsible retrieving the data. 
* Database: interact with MySQL database

This was originally in the CAM2 repository

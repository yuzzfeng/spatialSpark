# Spatial Analysis on Spark

A short and simple introduction for Apache Spark in Python and some helpful python pacakges, such as pandas, geoPandas, folium. Main contents are referenced by the tutorials given by [Shoaib Burq](https://github.com/sabman/PySparkGeoAnalysis) during the GeoPython 2016.

- Basic Spark operations - RDD and DataFrame
  http://nbviewer.jupyter.org/github/yuzzfeng/spatialSpark/blob/master/Montagsrunde_basics.ipynb

- Spark Demo with point count per cell
  http://nbviewer.jupyter.org/github/yuzzfeng/spatialSpark/blob/master/PointInCellCounter.ipynb
  
- Spatial Join Analysis
  http://nbviewer.jupyter.org/github/yuzzfeng/spatialSpark/blob/master/Montagsrunde_SpatialSpark.ipynb

- Twitter Demo with folium
  https://cdn.rawgit.com/yuzzfeng/spatialSpark/807bbf7a/demo.html

    
- Reference:
1. https://spark.apache.org/docs/1.6.1/programming-guide.html
2. http://simin.me/projects/spatialspark/


- Run docker with certain port connected to outside

$ docker run -it -p 8888:8888 tensorflow/tensorflow:1.5.0-gpu


- Start and stop a container

$ docker start backstabbing_sammet

$ winpty docker exec -i -t backstabbing_sammet bash

$ docker stop backstabbing_sammet

- Get info of container

$ docker inspect mad_northcutt

- Download anaconda
$ curl -O https://repo.continuum.io/archive/Anaconda3-4.2.0-Linux-x86_64.sh

$ sha256sum Anaconda3-5.0.1-Linux-x86_64.sh

$ bash Anaconda3-5.0.1-Linux-x86_64.sh

$ export PATH=/root/anaconda3/bin:$PATH


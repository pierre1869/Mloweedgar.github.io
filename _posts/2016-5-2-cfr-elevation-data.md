---
layout: post
title: CfR Elevation Data
published: true
---

## Code for Resilience Elevation Data Integration


### CURRENT STATUS
* Developed a User Interface in Inasafe to facilitate production of flood maps from qgis.
* Integrating the python script which has the codes for producing flood maps in the inasafe repository and make it available in Inasafe plugin  from QGIS.
* Working on producing flood maps from raster files with size greater than 1GB.

### HOW TO 

The following video shows how the whole process of creating a flood map from give tiff is operated
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="HOW TO VIDEO" width="240" height="180" border="10" /></a>

### PROGRESS 
I have been able to produce flood hazard maps using grass gis. I have prepared a document that describes step by step how to produce flood maps using grass gis
I have been able to create a python script that can initialize grass session(environment) and hence being able to access grass modules without explicitly starting grass gis. Therefore being able to produce flood maps without using grass gis directly


### CHALLENGES
The most big challenge is the computer processing ability and RAM, this has lead to difficulties in running analysis in maps of size more than 500MB.this has made me rely on sample data set which I obtained from grass gis official website. The data set has raster files with size less than 400MB which my computer could process.


---
layout: event
title: "2D and 3D Visualization of OSM data"
ref: "A12"
name: "Candan Eylül Kilsedar,  Jakub Balhar,  Maria Antonia Brovelli,  Patrick Hogan"
authors: "Candan Eylül Kilsedar ¹, Jakub Balhar ², Maria Antonia Brovelli ¹, Patrick Hogan ³"
affiliations: "¹ Politecnico di Milano, Department of Civil and Environmental Engineering, Milano, Italy,); ² Gisat s.r.o., Praha, Czech Republic; ³ NASA Ames Research Center, Moffett Field, CA, USA"
organization: ""
extra_tags:
  - "academic_track"
room: "S.1.3"
sortroom: "3"
length: "30 minutes"
time: "Sunday 14:00"
recording: true
tags:
  - sotmevent
  - slot24
  - academic_track
slides: "/slides/A12-2D_and_3D_Visualization_of_OSM_data.pdf"
youtube_recording: "TVIG68ip4ww"
---
The OpenStreetMap (OSM) is part of the big data of Web 2.0, having velocity, veracity and volume of big data characteristics. Visualizing big data is one of the challenges regarding the big data phenomenon (Li et al., 2016). The research and the application performed aims to tackle this challenge using open source tools by creating a plugin application programming interface (API) for visualizing the OSM data in two and three dimensions using ESA-NASA Web WorldWind virtual globe, improving the painting performance, fetching a subset of the data for a specific region and visualizing it instantly, creating heatmaps enabling visual analysis. The plugin API developed is available on https://github.com/kilsedar/3dosm and published with MIT license. The project has been developed during Google Summer of Code (GSoC) 2017.

The project visualizes the buildings in 3D and the rest in 2D, while the main focus and challenge is on 3D visualization. The API fetches the OSM data in real time based on a bounding box, or uses a local file or the data itself in GeoJSON format. Height to the buildings can be assigned using the OSM database, a property in GeoJSON file or an arbitrary value for all the buildings. In case the OSM database is used the “height” attribute is used if available, if not “building:levels” attribute is used to approximate the height, if neither are available a 5 level building is assumed. The API can also create a heatmap based on the heights of the buildings. The project also aims to improve the painting performance of 3D buildings in the browser. To achieve the improved performance, Polygons and MultiPolygons are triangulated to construct the buildings using the earcut algorithm (https://github.com/mapbox/earcut). Moreover, during the project Lidar data for Milan and GRASS GIS were used to extract the building heights, store the results in GeoJSON, and visualize this data. http://osm.eoapps.eu can be used get more information and http://osm.eoapps.eu/application/ can be used to visualize the data, which reached the finals at NASA Europa Challenge in 2017.

References
Li, S., Dragicevic, S., Castro, F.A., Sester, M., Winter, S., Çöltekin, A., Pettit, C., Jiang, B., Haworth, J., Stein, A., Cheng T., 2016. Geospatial big data handling theory and methods: A review and research challenges. ISPRS Journal of Photogrammetry and Remote Sensing, 115, pp. 119-133. https://doi.org/10.1016/j.isprsjprs.2015.10.012 
---
layout: event
title: "Investigating the OSM mapping process after disasters: OsmEventAnalyst and its application for the 2016 Italian earthquakes"
ref: "A15"
name: "Luca Delucchi,  Marco Minghini"
authors: "Luca Delucchi 1, Marco Minghini 2"
affiliations: "¹ Fondazione Edmund Mach, Centro Ricerca e Innovazione, San Michele all’Adige, Italy; ² Politecnico di Milano, Department of Civil and Environmental Engineering, Milano, Italy"
organization: ""
extra_tags:
  - "academic_track"
room: "S.1.3"
sortroom: "3"
length: "30 minutes"
time: "Sunday 14:30"
recording: true
tags:
  - sotmevent
  - slot25
  - academic_track
youtube_recording: "6hx8UVaCe5Q"
---
Humanitarian emergencies are among the most important applications of OpenStreetMap (OSM). At the international level, humanitarian mapping activities are coordinated by the Humanitarian OpenStreetMap Team (HOT) through ad hoc tools such as the Tasking Manager (TM). Due to the distributed nature of OSM volunteers, the investigation on who, when, how long and how exactly contributes map data during emergencies is an interesting, yet highly unexplored topic. The purpose of this work is to study the dynamics of the OSM mapping process happened after the earthquakes in Central Italy in 2016, which caused 299 victims and almost 400 injured people. The first big shock (ML 6.0) was registered at the end of August, followed by non-stop schocks over the following months with magnitude peaks at the end of October (ML 6.5). Despite the richness of technologies to analyse and process OSM data, no tools were available which answered the specific needs of the study. Therefore, a new software named OsmEventAnalyst was developed. Written in Python, it is available at https://github.com/osmItalia/OsmEventAnalyst under the GPL license. The tool is based on the OSM Full History Planet File (containing the whole history of OSM) and the OSM tile log (containing the number of visits to OSM map tiles) and uses several open source tools such as Osmium and PostgreSQL/PostGIS. Results show that about 60% of all contributors (506) who made at least one edit in the earthquake area throughout 2016, have modified the area after the first event, and that 83% of these were already registered to OSM before the first event. Thus the response from the OSM community, facilitated by a TM instance setup by the Italian community and using post-event satellite imagery, was mainly driven by already experienced contributors. Almost the 90% of OSM objects in the area were not modified after the earthquakes, while the objects with changes in geometry were about twice those with changes in the tags. Finally, OSM tiles in the study area were almost not visited at all before the event; this was followed by expected peaks after the main events and still a good number of visualizations after a few months. To conclude, this study has shed light on the OSM mapping process happened after the Italian earthquakes in 2016. The software developed, which returns results in the form of files and plots, can be easily reused to analyze OSM mapping activity corresponding to any other event.
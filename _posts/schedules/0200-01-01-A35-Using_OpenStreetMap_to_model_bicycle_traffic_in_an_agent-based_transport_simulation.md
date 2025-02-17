---
layout: event
title: "Using OpenStreetMap to model bicycle traffic in an agent-based transport simulation"
ref: "A35"
name: "Dominik Ziemke,  Simon Metzler"
authors: "Dominik Ziemke, Simon Metzler"
affiliations: "Technische Universität Berlin, Berlin, Germany"
organization: ""
extra_tags:
  - "academic_track"
room: "S.1.3"
sortroom: "3"
length: "30 minutes"
time: "Sunday 17:00"
recording: true
tags:
  - sotmevent
  - slot30
  - academic_track
slides: "/slides/A35-Using_OpenStreetMap_to_model_bicycle_traffic_in_an_agent-based_transport_simulation.pdf"
youtube_recording: "HxOs7Ib9220"
---
Cycling as a mode of transport for everyday life (besides cycling as a leisure activity) is becoming increasingly popular in many regions of the world. Policymakers as well as travelers acknowledge cycling as an environmentally-friendly, energy-efficient, healthy, and practical mode of transport, which can help addressing various problems of modern cities like air pollution, public health, or congestion.

In contrast to motorized individual and public transport, however, there are few transport models that incorporate cycling, even less such models describing cycling with its characteristic properties. In times of increasing significance of cycling, this is clearly a shortcoming because transport models have proven to be an effective tool to support the planning of transport infrastructures and the analysis of transport schemes. This paper intends to address this shortcoming by including cyclists and their highly-diversified travel behavior into a suitable transport model. 

To achieve this, MATSim, an open-source agent-based transport simulation framework, is used. In MATSim, individual travelers are simulated along all their activities and trips over the course of a full day. Due to its microscopic nature, MATSim allows to distinguish between the behavior of heterogeneous agents based on various attributes of the infrastructure and the travelers themselves.

In this study, we discuss and show the use of OpenStreetMap as the main data source to create a transport network that encompasses various properties that are of particular relevance for cyclists. These attributes include roadway smoothness, surface type, highway type, existence of a dedicated cycling infrastructure etc. This information is enriched with other open-source data to account for the roadway gradients in the model.

Based on a growing body of literature on cycling as a mode of transport, rules which describe how those properties are taken into account by cyclists are developed. For validation, our OSM-based cyclists model is applied to an existing transport scenario of the metropolitan region of Berlin, where automated cyclist counts with a high temporal resolution are openly available. As such, simulated cyclist traffic counts can be compared to real-world cyclist counts in 17 locations of the city.

Because of its reliance on OSM as the main data source, the approach is transferable to other spatial contexts.
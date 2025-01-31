---
title: "A Cyber-Physical-System Approach to Data Center Modeling and Control for Energy Efficiency"

# Date first published.
date: "2012-01-30"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
  - Luca Parolini
  - Bruno Sinopoli
  - Bruce H. Krogh
  - Zhikui Wang

publication_types: ["2"]

# Publication name and optional abbreviated version.
publication: "Proceedings of the IEEE"

# Abstract and optional shortened version.
abstract: "This paper presents data centers from a _cyber-physical system_ (CPS) perspective. Current methods for controlling information technology (IT) and cooling technology (CT) in data centers are classified according to the degree to which they take into account both cyber and physical considerations. To evaluate the potential impact of coordinated CPS strategies at the data center level, we introduce a control-oriented model that represents the data center as two coupled networks:

 * a computational network representing the cyber dynamics;

 * a thermal network representing the physical dynamics.


These networks are coupled through the influence of the IT on both networks: servers affect both the quality of service (QoS) delivered by the computational network and the generation of heat in the thermal network. Using this model, three control strategies are evaluated with respect to their energy efficiency and computational performance:

  - a baseline strategy that ignores CPS considerations;

  - an uncoordinated strategy that manages the IT and CT independently;

  - a coordinated strategy that manages the IT and CT together to achieve optimal performance with respect to both QoS and energy efficiency.


Simulation results show that the benefits to be realized from coordinating the control of IT and CT depend on the distribution and heterogeneity of the computational and cooling resources throughout the data center.


A new _cyber-physical index_ (CPI) is introduced as a measure of this combined distribution of cyber and physical effects in a given data center. We illustrate how the CPI indicates the potential impact of using coordinated CPS control strategies."

# Featured image thumbnail (optional)
image_preview: ""

# Is this a selected publication? (true/false)
selected: true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects: ["deep-learning"]` references `content/project/deep-learning.md`.
projects: []

# Links (optional).
url_pdf: "https://ieeexplore.ieee.org/document/6006498/"
url_preprint: ""
url_code: ""
url_dataset: ""
url_project: ""
url_slides: ""
url_video: ""
url_poster: ""
url_source: ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom: [{name: "Custom Link", url: "http://example.org"}]

# Does the content use math formatting?
math: false

# Does the content use source code highlighting?
highlight: false

categories:
   - paper

tags:
  - optimization
  - data center
  - mpc
  - optimal control
  - cyber-physical systems
  - cyber-physical index
  - energy management
  - energy efficiency
  - thermal modeling

image:
  placement: 1  
  preview_only: false
  focal_point: "Smart"
  alt_text: "Relative savings of the coordinated controller with respect to the uncoordinated controller for different cyber-physical index values."
---

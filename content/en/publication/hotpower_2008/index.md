---
title: "Reducing Data Center Energy Consumption via Coordinated Cooling and Load Management"

# Date first published.
date: "2008-12-08"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
 - Luca Parolini
 - Bruno Sinopoli
 - Bruce H. Krogh

publication_types: ["1"]

# Publication name and optional abbreviated version.
publication: "Workshop on Power Aware Computing and Systems, San Diego (CA), USA"
publication_short: "In *HotPower*"

# Abstract and optional shortened version.
abstract: "This paper presents a unified approach to data center energy management based on a modeling framework that characterizes the influence of key decision variables on computational performance, thermal generation, and power consumption. Temperature dynamics are modeled by a network of interconnected components reflecting the spatial distribution of servers, computer room air conditioning (CRAC) units, and non-computational components in the data center. A second network models the distribution of the computational load among the servers. Server power states influence both networks. Formulating the control problem as a Markov decision process (MDP), the coordinated cooling and load management strategy minimizes the integrated weighted sum of power consumption and computational performance. Simulation results for a small example illustrate the potential for a coordinated control strategy to achieve better energy management than traditional schemes that control the computational and cooling subsystems separately. These results suggest several directions for further research."
abstract_short: ""

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
url_pdf: "http://usenix.org/event/hotpower08/tech/full_papers/parolini/parolini.pdf"
url_preprint: "/pdf/HotPower_2008.pdf"
url_code: ""
url_dataset: ""
url_project: ""
url_slides: ""
url_video: ""
url_poster: ""
url_source: ""

# Does the content use math formatting?
math: false

# Does the content use source code highlighting?
highlight: false

image:
  placement: 1
  preview_only: false
  alt_text: "A computational network of server nodes coupled with a thermal network of server, CRAC, and environment nodes."
  caption: "Proposed joint network of servers and CRACs"

tags:
 - data center
 - energy management
 - energy efficiency
 - thermal modeling
 - optimization
 - optimal control
 - cyber-physical systems
 - workshop

---

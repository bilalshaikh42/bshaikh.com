---
title: "BioSimulations: Sharing and reusing biomodels, simulations, and
  visualizations"
abstract: More comprehensive and more predictive models of cells could enable
  the advancement of biology, medicine, and bioengineering. Such models will
  require collaboration between many investigators and domains. In turn, models
  must be shareable, executable, and accessible. While many community resources
  exist, such as BiGG, BNGL, BioModels, CellML, KiSAO, NeuroML, OMEX, SBML, and
  SED-ML, significant barriers to collaboration remain. Different types of
  models remain siloed across multiple repositories, modeling frameworks, model
  formats, simulation algorithms, and simulation tools. For example, flux
  balance models are often obtained from BiGG and simulated with COBRApy, while
  deterministic kinetic models are often obtained from BioModels and simulated
  with tellurium. Future, more comprehensive models will likely require
  capturing biology at multiple scales, requiring the ability to combine
  frameworks, formats, algorithms, and tools. Additionally, installation and
  usage of tools cam be difficult. To address these challenges, we have
  developed BioSimulations (https://run.biosimulations.org), a cloud platform
  for reproducing and reusing models with ease. BioSimulations will provide
  users a unified platform to share, discover, run, and visualize biological
  models across various modeling scales, formats, frameworks, and algorithms.
location: Online
date: 2021-10-11T016:00:00.000Z
date_end: 2021-10-11T16:20:00.000Z
all_day: false
links:
  - url: https://sched.co/nsUM
    name: Event Link
    icon_pack: null
    icon: ""
event: COMBINE 2021
event_url: https://combine-org.github.io/events/
publishDate: 2021-10-07T23:44:43.073Z
draft: false
featured: false
authors:
  - Bilal Shaikh
  - Gnaneswara Marupilla
  - Mike Wilson
  - Michael L Blinov
  - Ion I Moraru
  - Jonathan R Karr
projects:
  - biosimulations
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
**Recent advances**
Recent improvements to the platform have significantly increased the range of supported simulations to 10 model languages, 20 simulation tools, 70 algorithms, and several modeling frameworks including continuous and discrete kinetic, logical, flux balance, spatial, particle-based, and hybrid modeling. To help investigators navigate these tools, the platform can now automatically inspect models and recommend specific algorithms and tools for executing them. Large-scale simulation results up to 5 TB per project can now be saved and queried using the Highly Scalable Data Service (HSDS). Users can also use Vega to visualize simulation results with advanced, interactive diagrams, such as activity flow diagrams, process description maps, and reaction flux maps which can be created with a variety of tools such as Escher, GINSim, and Newt. Furthermore, BioSimulations makes it easy for investigators to reuse such visualizations across multiple projects, such as to compare multiple models or simulations.

**Future directions**
We are developing a repository  of entire simulation projects, including interactive visualizations of results.

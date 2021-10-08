---
title: "BioSimulators: a registry of containerized biosimulation tools with
  standard interfaces that enhance the reuse of biomodels"
abstract: >
  More predictive models could advance biology, medicine, and bioengineering.
  Building such models will likely require teams who can share and reuse models.
  Several standards, including CellML, KiSAO, NeuroML, OMEX, SBML, SBO, and
  SED-ML, facilitate model sharing. To support multiple formalisms such as
  logical, FBA, and kinetic modeling, these standards include numerous features
  such as delays, events, and objectives. Hundreds of simulators support many of
  these features. However, it remains challenging to reuse many models. The
  incomplete support for these features among simulators and the lack of
  centralized documentation of the features supported by each simulator often
  make it difficult to find a simulator for a model. Furthermore, simulators
  frequently become unavailable when projects terminate, old versions of tools
  that support old versions of features are often hard to obtain, many tools are
  cumbersome to install, and it takes significant effort to learn a different
  interface for each tool.
location: Online
date: 2020-11-06T03:15:54.491Z
date_end: 2020-11-06T03:30:00.000Z
all_day: false
event: COMBINE 2020
event_url: http://co.mbine.org/events/COMBINE_2020
publishDate: 2021-10-07T23:59:54.518Z
draft: false
featured: false
projects:
  - biosimulators
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
**Results**: To facilitate model reuse, we are developing Biosimulators, a registry of standardized containers of biosimulation tools. BioSimulators will help researchers find simulators by tracking the formalisms, algorithms, and formats that they support. BioSimulators will also help researchers use these tools by encapsulating them into consistent command-line interfaces inside containers. By facilitating reuse, we anticipate that the registry will promote more predictive models.
**Methods**: To assemble the registry, we have developed a standard command-line interface and container structure for biosimulation tools; a standard format for specifying the capabilities (supported formalisms, algorithms, and formats) of a simulator; and a tool for verifying the capabilities of a container; and a website for finding containers with specific capabilities. We have used these resources to develop several containers for logical, FBA, ODE, stochastic, network-free, and DAE tools.
**Future directions:** We aim to work with the community to develop additional containers that support other formalisms, algorithms, and formats. We plan to expand the testing tool to verify each container's capabilities more rigorously. To make it even easier to reuse models, we are using the registry to develop a simple web application for executing simulations.
**Availability**: BioSimulators is openly available at https://biosimulators.org along with examples and documentation.
**Target audience:** Biomodeling community; Investigators who want to quickly try out and reuse published models or access older versions of simulation tools; Simulation software developers who want to easily distribute their simulation tools or compare the accuracy or performance of their tools with other tools; Peer reviewers and editors who want to evaluate models pre-publication.
Standards: CellML, COMBINE Archive, NeuroML, SBML, SED-ML, BioContainers, EDAM, KiSAO, SBO
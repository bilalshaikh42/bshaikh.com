---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SED-ML Validator: tool for debugging simulation experiments'
subtitle: ''
summary: ''
authors:
- Bilal Shaikh
- A. Freiburger
- Matthias Konig
- Frank T. Bergmann
- D. Nickerson
- H. Sauro
- M. Blinov
- Lucian P. Smith
- I. Moraru
- Jonathan R. Karr
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-09-09T02:40:09-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-09-09T06:40:08.827936Z'
publication_types:
- '3'
abstract: 'More sophisticated models are needed to address problems in bioscience, synthetic biology, and precision medicine. To help facilitate the collaboration needed for such models, the community developed the Simulation Experiment Description Markup Language (SED-ML), a common format for describing simulations. However, the utility of SED-ML has been hampered by limited support for SED-ML among modeling software tools and by different interpretations of SED-ML among the tools that support the format. To help modelers debug their simulations and to push the community to use SED-ML consistently, we developed a tool for validating SED-ML files. We have used the validator to correct the official SED-ML example files. We plan to use the validator to correct the files in the BioModels database so that they can be simulated. We anticipate that the validator will be a valuable tool for developing more predictive simulations and that the validator will help increase the adoption and interoperability of SED-ML.'
publication: ''
---
The validator is freely available as a webform, HTTP API, command-line program, and Python package at https://run.biosimulations.org/utils/validate and https://pypi.org/project/biosimulators-utils. The validator is also embedded into interfaces to 11 simulation tools. The source code is openly available at https://github.com/biosimulators/biosimulators_utils.
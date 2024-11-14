---
title: Addressing imbalanced data for machine learning based mineral prospectivity mapping
subtitle: ""
publication_types:
  - "2"
authors:
  - Fahimeh Farahnakian 
  - admin
  - Luca Zelioli
  - Dipak Nidhi
  - Iiro Seppä
  - Rami Ilo
  - Paavo Nevalainen
  - Jukka Heikkonen 
author_notes:
  - Associate Professor; Department of Computing; University of Turku; Turku; Finland
  - Ph.D. Candidate; Department of Computing; University of Turku; Turku; Finland
  - Ph.D. Candidate; Department of Computing; University of Turku; Turku; Finland
  - Ph.D. Candidate; Department of Computing; University of Turku; Turku; Finland
  - Project Researcher; Department of Computing; University of Turku; Turku; Finland
  - Ph.D. Candidate; Department of Computing; University of Turku; Turku; Finland
  - Specialist RResearcher; Department of Computing; University of Turku; Turku; Finland
  - Professor; Department of Computing; University of Turku; Turku; Finland
doi: https://doi.org/10.1016/j.oregeorev.2024.106270
publication: Ore Geology Reviews
abstract: 'Effective Mineral Prospectivity Mapping (MPM) relies on the ability of Machine Learning (ML) models to extract meaningful patterns from geophysical data. However, in mineral exploration, identifying the presence of mineral deposits is often a rare event compared with the overall geological landscape. This rarity leads to a highly imbalanced dataset, where positive instances (mineralized samples) are considerably less frequent than negative instances (non-mineralized samples). Imbalanced data can potentially bias ML models towards the majority class, leading to inaccurate predictions for the minority class (mineralized samples) which are of primary interest. To address this challenge, we proposed two-level methods in this study. At the data level, we employed imbalanced data handling techniques that operate on the training dataset and change the class distribution. At the algorithmic level, we adjusted the decision threshold of a model to balance the trade-off between false positives and false negatives. Experimental results are collected on a geophysical data from Lapland, Finland. The dataset exhibits a significant class imbalance, comprising 17 positive samples contrasted with 1840000 negative samples. We investigate the effect of handling imbalanced data on the performance of four ML models including Multi-Layer Perceptron (MLP), Random Forest (RF), Decision Tree (DT), and Logistic Regression (LR). From the results, we found that the MLP model achieved the best overall performance, with total accuracy of 97.13% on balanced data using synthetic minority oversampling method. Random forest and DT also performed well, with accuracies of 88.34% and 89.35%, respectively. The implemented methodology of this work is integrated in QGIS as a new toolkit which is called EIS Toolkit for MPM.'
draft: false
featured: true
summary: "This study addresses imbalanced data challenges in Mineral Prospectivity Mapping (MPM) using geophysical data from Lapland, Finland. It applies data-level imbalanced handling techniques and algorithm-level threshold adjustments to improve model predictions of rare mineral deposits. The performance of four ML models—MLP, RF, DT, and LR—was evaluated. The MLP model achieved the best accuracy (97.13%) on balanced data using synthetic oversampling."
tags:
  - Mineral prospectivity mapping
  - Imbalanced data
  - Random forest
  - Multi-perceptron
  - Logistic regression
  - Decision tree
  - EIS toolkit
  - Machine Learning
image:
  image_position: Bottom
  filename: featured.jpg
  focal_point: smart
  preview_only: false
  
date: 2024-10-30T07:21:13.700Z
---
<!--StartFragment-->

{{< icon name="download" pack="fas" >}} Download the {{< staticref "uploads/oregeo.pdf" "newtab" >}}Full Paper{{< /staticref >}}.

<!--EndFragment-->

---
title: "Refined tooth and pulp segmentation using U-Net in CBCT image"
collection: publications
category: manuscripts
permalink: /publication/2021-01-01-refined-tooth-pulp-segmentation
excerpt: 'We propose a two-phase deep learning solution for accurate tooth and pulp cavity segmentation. First, the single tooth bounding box is extracted automatically for both single-rooted tooth (ST) and multirooted tooth (MT). Second, U-Net model is iteratively performed for refined tooth and pulp segmentation.'
date: 2021-01-01
venue: 'Dentomaxillofacial Radiology'
paperurl: 'https://doi.org/10.1259/dmfr.20200251'
---
The aim of this study was extracting any single tooth from a CBCT scan and performing tooth and pulp cavity segmentation to visualize and to have knowledge of internal anatomy relationships before undertaking endodontic therapy.

We propose a two-phase deep learning solution for accurate tooth and pulp cavity segmentation. First, the single tooth bounding box is extracted automatically for both single-rooted tooth (ST) and multirooted tooth (MT). It is achieved by using the Region Proposal Network (RPN) with Feature Pyramid Network (FPN) method from the perspective of panorama. Second, U-Net model is iteratively performed for refined tooth and pulp segmentation against two types of tooth ST and MT, respectively. In light of rough data and annotation problems for dental pulp, we design a loss function with a smoothness penalty in the network. Furthermore, the multi-view data enhancement is proposed to solve the small data challenge and morphology structural problems.

The experimental results show that the proposed method can obtain an average dice 95.7% for ST, 96.2% for MT and 88.6% for pulp of ST, 87.6% for pulp of MT. This study proposed a two-phase deep learning solution for fast and accurately extracting any single tooth from a CBCT scan and performing accurate tooth and pulp cavity segmentation. The 3D reconstruction results can completely show the morphology of teeth and pulps, it also provides valuable data for further research and clinical practice.


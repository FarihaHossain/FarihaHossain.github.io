---
title: "Revolutionizing Space Health (Swin-FSR): Advancing Super-Resolution of Fundus Images for SANS Visual Assessment Technology"
collection: publications
permalink: /publications/MICCAI2023
venue: "The 26th International Conference on Medical Image Computing and Computer Assisted Intervention, MICCAI 2023"
date: 2023-05-24
citation: '<b>Khondker Fariha Hossain</b>, Sharif Amit Kamran, Joshua Ong, Andrew G. Lee, Alireza Tavakkoli'
---
[[Arxiv]](https://arxiv.org/abs/2308.06332)

## Abstract
The rapid accessibility of portable and affordable retinal imaging devices has made early differential diagnosis easier. For example, color funduscopy imaging is readily available in remote villages, which can help to identify diseases like age-related macular degeneration (AMD), glaucoma, or pathological myopia (PM). On the other hand, astronauts at the International Space Station utilize this camera for identifying spaceflight-associated neuro-ocular syndrome (SANS). However, due to the unavailability of experts in these locations, the data has to be transferred to an urban healthcare facility (AMD and glaucoma) or a terrestrial station (e.g, SANS) for more precise disease identification. Moreover, due to low bandwidth limits, the imaging data has to be compressed for transfer between these two places. Different super-resolution algorithms have been proposed throughout the years to address this. Furthermore, with the advent of deep learning, the field has advanced so much that x2 and x4 compressed images can be decompressed to their original form without losing spatial information. In this paper, we introduce a novel model called Swin-FSR that utilizes Swin Transformer with spatial and depth-wise attention for fundus image super-resolution. Our architecture achieves Peak signal-to-noise-ratio (PSNR) of 47.89, 49.00 and 45.32 on three public datasets, namely iChallenge-AMD, iChallenge-PM, and G1020. Additionally, we tested the model's effectiveness on a privately held dataset for SANS and achieved comparable results against previous architectures.  
---
title: "SwinVFTR: A Novel Volumetric Feature-learning Transformer for 3D OCT Fluid Segmentation"
collection: publications
permalink: /publications/SwinVFTR
venue: "22th IEEE International Symposium on Biomedical Imaging"
date: 2025-01-04
citation: '<b>Khondker Fariha Hossain<\b>, Sharif Amit Kamran, Alireza Tavakkoli, George Bebis, Sal Baker'
---
[[ARXIV]](https://arxiv.org/pdf/2303.09233)

## Abstract
Accurately segmenting fluid in 3D optical coherence tomography (OCT) images is critical for detecting eye diseases but remains challenging. Traditional autoencoder-based methods struggle with resolution loss and information recovery. While transformer-based models improve segmentation, they arent optimized for 3D OCT volumes, which vary by vendor and extraction technique. To address this, we propose SwinVFTR, a transformer architecture for precise fluid segmentation in 3D OCT images. SwinVFTR employs channel-wise volumetric sampling and a shifted window transformer block to improve fluid localization. Moreover, a novel volumetric attention block enhances spatial and depth-wise attention. Trained using multi-class dice loss, SwinVFTR outperforms existing models on Spectralis, Cirrus, and Topcon OCT datasets, achieving mean dice scores of 0.72, 0.59, and 0.68, respectively, along with superior performance in mean intersection-over-union (IOU) and structural similarity (SSIM) metrics.
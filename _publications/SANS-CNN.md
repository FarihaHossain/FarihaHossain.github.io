---
title: "SANS-CNN: An automated machine learning technique for spaceflight associated neuro-ocular syndrome with astronaut imaging data"
collection: publications
permalink: /publications/SANS-CNN
venue: "npj Microgravity, Volume-10, Issue-1, Pages-40"
date: 2024/3/28
citation: 'Sharif Amit Kamran,<b>Khondker Fariha Hossain</b>, Joshua Ong, Nasif Zaman, Ethan Waisberg, Phani Paladugu, Andrew G Lee, Alireza Tavakkoli'
---
[[ARXIV]](https://www.nature.com/articles/s41526-024-00364-w.pdf)

## Abstract
Spaceflight associated neuro-ocular syndrome (SANS) is one of the largest physiologic barriers to
spaceflight and requires evaluation and mitigation for future planetary missions. As the spaceflight
environment is a clinically limited environment, the purpose of this research is to provide automated, early
detection and prognosis of SANS with a machine learning model trained and validated on astronaut SANS
optical coherence tomography (OCT) images. In this study, we present a lightweight convolutional neural
network (CNN) incorporating an EfficientNet encoder for detecting SANS from OCT images titled “SANS-
CNN.” We used 6303 OCT B-scan images for training/validation (80%/20% split) and 945 for testing with a
combination of terrestrial images and astronaut SANS images for both testing and validation. SANS-CNN
was validated with SANS images labeled by NASA to evaluate accuracy, specificity, and sensitivity. To
evaluate real-world outcomes, two state-of-the-art pre-trained architectures were also employed on this
dataset. We use GRAD-CAM to visualize activation maps of intermediate layers to test the interpretability
of SANS-CNN’s prediction. SANS-CNN achieved 84.2% accuracy on the test set with an 85.6%
specificity, 82.8% sensitivity, and 84.1% F1-score. Moreover, SANS-CNN outperforms two other state-
of-the-art pre-trained architectures, ResNet50-v2 and MobileNet-v2, in accuracy by 21.4% and 13.1%,
respectively. We also apply two class-activation map techniques to visualize critical SANS features
perceived by the model. SANS-CNN represents a CNN model trained and validated with real astronaut
OCT images, enabling fast and efficient prediction of SANS-like conditions for spaceflight missions
beyond Earth’s orbit in which clinical and computational resources are extremely limited.
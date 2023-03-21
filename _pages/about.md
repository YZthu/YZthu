---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, welcome to my website. I am a PhD student at University of California, Merced, adviced by Dr. Shijia Pan. I obtained my M.S. and B.S. degree in Electronic Engineering from Tsinghua University in 2019 and 2016, respectively. My research interest including multimodal human sensing, deep learning, and smart healthcare. 

In life, I am a big fan of hiking and camping, if you plan to visit Yosemite national park, fell free to contact me. I am also play basketabll and skateboarding.

yzhang58 AT ucmerced dot edu

# Major Research Projects

## 1. Cross-modal Signal Segment Association
<div > 
<img align="left" width="300" height="264" src='/images/CMA_IPSN23.png'/> 
Indoor occupant sensing enables many smart home applications, and various sensing systems have been explored.
Based on their installation requirements, we consider two categories of sensors -- on- and off-body -- and we look into the combination of them for occupant sensing due to their spatial and temporal complementarity. We focus on an example modality pair of wearable IMU and structural vibration that demonstrate modality complementarity in prior work. However, current efforts are built upon the assumption that the knowledge of the signal segments from two modalities are known, which is challenged in a multiple occupants co-living scenario. Therefore, establishing accurate cross-modal signal segment associations is essential to ensure that a correct complementary relationship is learned. We fromulate this problem as a time series prediction problem, and propose AD-TCN, a framework built upon a temporal convolutional network that calculates the amount of shared context between cross-modal segments from the paremters of the time-series prediction model.
<br />
Related publications: <a href="https://yzthu.github.io/publication/2023_IPSN">IPSN 2023</a>
</div>


## 2. Customer Event Detection in Autonomous Retails
<div > 
<img align="left" width="300" height="224" src='/images/CPA_HotMobile23.png'/> 
Customer-product interaction (pickup or put down) detection is essential for autonomous retail. Previous studies have explored many sensing technologies, including vision, load, RFID, and piezo. These approaches often require strict deployment conditions, such as Line-of-Sight (LoS), dense deployment, and/or high cost. Accurate customer event detection is essential in autonomous retails, such as cashierless checkout and inventory monitoring. We present a vibration-based customer-product interaction detection system for autonomous retail -- one vibration sensor placed on the back panel of the gondola to achieve single-point sensing to monitor all the shelves on the gondola. The key challenge is to detect pickup of small items (e.g., candy bar), which induces extremely low SNR vibration signals. We introduce a cyber-physical augmentation scheme to enhance the vibration sensing signal via a physical arc structure and achieves high accuracy labeling-free event detection.
<br />
Related publications: <a href="https://yzthu.github.io/publication/2023_Hotmobile">HotMobile 2023</a>, <a href="https://yzthu.github.io/publication/2023_Hotmobile_Demo">HotMobile 2023 (Demo)</a>.

</div>

## 3. Fine-Grained Human Activity Recognition
<div > 
<img align="left" width="300" height="224" src='/images/VMA_IPSN22.png'/> 
The growth of the Internet of Things (IoT) sensing systems leads to a large number of multimodal datasets over different deployments. Labeling costs for these datasets, especially fine-grained labels, are often tremendous. On the other hand, different data distributions (domain variance) of these datasets prevent models built with labels of one dataset (source domain) from being directly used in another (target domain). This domain variance may be caused by one or more physical factors change in the deployments, such as buildings and/or people. Existing model transfer studies mainly focus on adapting the model to the domain variance caused by only one physical factor change. When multiple factors change between the source and target domains, the model transfer often yields low accuracy due to significant domain variance. We present a model transfer framework for multimodal IoT
sensing data that handles multi-factor domain variance.
<br />
Related publications: <a href="https://yzthu.github.io/publication/2022_IPSN">IPSN 2022</a>.

</div>



# [Centric Probability-Based Sample Selection for Oriented Object Detection](https://arxiv.org/)

Yanqing Yao, Gong Cheng, Member, IEEE, Chunbo Lang, Xingxing Xie, and Junwei Han, Fellow, IEEE

## Introduction

![](structure.jpg)

In object detection, particularly within remote sensing images, the quality of selected samples is crucial for the accuracy and robustness of detection models. However, current sampling strategies demonstrate inherent limitations. They empirically define positive sample sets using fixed thresholds or preset areas, ignoring the actual shapes of the objects and failing to distinguish the intrinsic value of each sample point. To address these critical issues, this article proposes a novel centric probability-based sample selection approach that includes centering probability mapping (CPM), Expectation-Maximizationbased boundary optimization (EBO), and probabilistic random sampling (PRS) technologies. Specifically, the CPM is constructed to assign various confidence levels for all sample points based on their proximity to the center of bounding box, effectively discerning the value of individual samples. Then, the EBO is utilized to dynamically optimize the boundaries for positive and negative samples based on the EM algorithm, thus avoiding the sample imbalance problem associated with empirical thresholds. Finally, the PRS strategy is proposed to select training samples from the sample space constructed by CPM and EBO in a manner of random probability sampling, which could improve the diversity of samples while guaranteeing their quality. Experimental validation on three remote sensing image datasets, including DOTA-v1.0, DOTA-v2.0, and DIOR-R, demonstrates that our method achieves robust performance improvements over baseline and significantly surpasses the advanced sample selection methods.

### Runtime
```
conda create -n mmrotate python==3.10 ; conda activate mmrotate
conda install pytorch==1.12.1 torchvision==0.13.1 cudatoolkit=11.3 -c pytorch
pip install openmim ; mim install mmengine mmcv==2.0.0 mmdet==3.0.0
```
### Introduction
Please check the following website.
https://github.com/open-mmlab/mmrotate/blob/main/README.md
### Dataset
Please check the following website.
https://github.com/open-mmlab/mmrotate/blob/main/tools/data/dota/README.md

### Code
Code will be publicly available soon.

## Contact us
If you have any questions, please email eyao468@gmail.com.

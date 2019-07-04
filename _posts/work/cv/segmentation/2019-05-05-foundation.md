---
layout: article
title:  "「CV」 物体分割资源汇总"
date:   2019-05-05 18:06:40 +0800
key: image-segmentation-foundation-20190505
aside:
  toc: true
category: [CV, segmentation]
tags: 资源
---
<span id='head'></span>

<!--more-->  

# 1 二维
## 1.1 综述

## 1.2 理论

1. [Learning Fully Dense Neural Networks for Image Semantic Segmentation](http://cn.arxiv.org/abs/1905.08929)   
*2019-05-22* [paper](https://arxiv.org/abs/1905.08929)   

1. [Segmentation-Aware Image Denoising without Knowing True Segmentation](http://cn.arxiv.org/abs/1905.08965)   
*2019-05-22* [paper](https://arxiv.org/abs/1905.08965)   

1. [Spatial Sampling Network for Fast Scene Understanding](http://cn.arxiv.org/abs/1905.09033)   
CVPR 2019 (Autonomous Driving) *2019-05-22* [paper](https://arxiv.org/abs/1905.09033)    

1. [End-to-End Learned Random Walker for Seeded Image Segmentation](https://arxiv.org/abs/1905.09045)   
*2019-05-22* [paper](https://arxiv.org/abs/1905.09045)   

1. [WPU-Net:Boundary learning by using weighted propagation in convolution network](https://arxiv.org/abs/1905.09226)   
*2019-05-22* [paper](https://arxiv.org/abs/1905.09226)   

## 1.3 经典

## 1.4 生物医疗
### 1.4.1 肺结核
1. [Dual-branch residual network for lung nodule segmentation](http://cn.arxiv.org/abs/1905.08413)   
*2019-05-21* [paper](https://arxiv.org/abs/1905.08413)   

### 1.4.2 白细胞
1. [A novel algorithm for segmentation of leukocytes in peripheral blood](http://cn.arxiv.org/abs/1905.08416)   
*2019-05-21* [paper](https://arxiv.org/abs/1905.08416)   

### 1.4.3 手术器械
1. [RASNet: Segmentation for Tracking Surgical Instruments in Surgical Videos Using Refined Attention Segmentation Network](http://cn.arxiv.org/abs/1905.08663)   
*2019-05-21* [paper](https://arxiv.org/abs/1905.08663)   

1. [Learning Where to Look While Tracking Instruments in Robot-assisted Surgery](http://cn.arxiv.org/abs/1907.00214)   
MICCAI 2019 *2019-06-29* [paper](https://arxiv.org/abs/1907.00214)    

### 1.4.4 头部 CT
1. [Improved ICH classification using task-dependent learning](http://cn.arxiv.org/abs/1907.00148)   
*2019-06-29* [paper](https://arxiv.org/abs/1907.00148)   
分割、分类双任务同时进行，最后的 loss 有借鉴意义；    

### 1.4.5 骨骼
1. [Permutohedral Attention Module for Efficient Non-Local Neural Networks](http://cn.arxiv.org/abs/1907.00641)   
MICCAI 2019 *2019-07-01* [paper](https://arxiv.org/abs/1907.00641)   
椎骨分割，用了注意力；   

### 1.4.6 皮肤
1. [MobileGAN: Skin Lesion Segmentation Using a Lightweight Generative Adversarial Network](http://cn.arxiv.org/abs/1907.00856)   
*2019-07-01* [paper](https://arxiv.org/abs/1907.00856)   
使用 GAN 进行分割；    

### 1.4.7 肿瘤
1. [An Efficient Solution for Breast Tumor Segmentation and Classification in Ultrasound Images Using Deep Adversarial Learning](https://arxiv.org/abs/1907.00887)   
*2019-07-01* [paper](https://arxiv.org/abs/1907.00887)    
使用了对抗学习；   

### 1.4.7 其他
1. [Task Decomposition and Synchronization for Semantic Biomedical Image Segmentation](http://cn.arxiv.org/abs/1905.08720)   
*2019-05-21* [paper](https://arxiv.org/abs/1905.08720)   

1. [Multi-scale guided attention for medical image segmentation](http://cn.arxiv.org/abs/1906.02849)   
*2019-06-07* [paper](https://arxiv.org/abs/1906.02849) | [pytorch](https://github.com/sinAshish/Multi-Scale-Attention)-offical    
差不多的低层特征在多个尺度上重复提取，我们就设计了一个注意力，来重复利用这些特征；并在腹部磁共振成像（MRI）上进行了实验；    


## 1.5 自然
1. [Semi-Supervised Segmentation of Salt Bodies in Seismic Images using an Ensemble of Convolutional Neural Networks](http://cn.arxiv.org/abs/1904.04445)   
*2019-04-09* [paper](https://arxiv.org/abs/1904.04445) | [pytorch](https://github.com/ybabakhin/kaggle_salt_bes_phalanx)-offical      

## 1.6 其他
1. [ACNet: Attention Based Network to Exploit Complementary Features for RGBD Semantic Segmentation](https://arxiv.org/abs/1905.10089)   
ICIP 2019 *2019-05-24* [paper](https://arxiv.org/abs/1905.10089) | [pytorch](https://github.com/anheidelonghu/ACNet)    

# 2 序列
1. [RVOS: End-to-End Recurrent Network for Video Object Segmentation](http://cn.arxiv.org/abs/1903.05612)   
CVPR 2019 (camera ready) *2019-03-13* [paper](https://arxiv.org/abs/1903.05612) | [project](https://imatge-upc.github.io/rvos/) | [pytorch](https://github.com/imatge-upc/rvos)-offical   

1. [OVSNet : Towards One-Pass Real-Time Video Object Segmentation](http://cn.arxiv.org/abs/1905.10064)   
*2019-05-24* [paper](https://arxiv.org/abs/1905.10064)   

# 3 三维
## 3.1 基于点云
1. [RIU-Net: Embarrassingly simple semantic segmentation of 3D LiDAR point cloud](https://arxiv.org/abs/1905.08748)   
*2019-05-21* [paper](https://arxiv.org/abs/1905.08748)   

## 3.2 基于体素
1. [Learning to Reconstruct High-quality 3D Shapes with Cascaded Fully Convolutional Networks](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yan-Pei_Cao_Learning_to_Reconstruct_ECCV_2018_paper.pdf)    
ECCV 2018 [Paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yan-Pei_Cao_Learning_to_Reconstruct_ECCV_2018_paper.pdf)   
3D FCN  

## 3.3 深度图
1. [RFBNet: Deep Multimodal Networks with Residual Fusion Blocks for RGB-D Semantic Segmentation](http://cn.arxiv.org/abs/1907.00135)   
*2019-06-29* [paper](https://arxiv.org/abs/1907.00135)   

-------------------  
[End](#head)
{:.warning}  


# 附录
## A 参考资料
[1]. tangzhenyu. SemanticSegmentation_DL[EB/OL]. <https://github.com/tangzhenyu/SemanticSegmentation_DL>. -/2019-05-05.   
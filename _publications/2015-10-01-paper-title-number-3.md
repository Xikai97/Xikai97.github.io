---
title: "Multi-layer Clustering-based Residual Sparsifying Transform for Low-dose CT Image Reconstruction"
collection: publications
permalink: /publication/2022-MCST
date: 2022-03
venue: 'Journal 3'
paperurl: '[Submitted to Medical Physics](https://arxiv.org/abs/2203.11565)'
---
 In this study, we propose a network-structured sparsifying transform learning approach for X-ray computed tomography (CT), which we refer to as multi-layer clustering-based residual sparsifying transform (MCST) learning. The proposed MCST scheme learns multiple different unitary transforms in each layer by dividing each layer's input into several classes. We apply the MCST model to low-dose CT (LDCT) reconstruction by deploying the learned MCST model into the regularizer in penalized weighted least squares (PWLS) reconstruction. We conducted LDCT reconstruction experiments on XCAT phantom data and Mayo Clinic data and trained the MCST model with 2 (or 3) layers and with 5 clusters in each layer. The learned transforms in the same layer showed rich features while additional information is extracted from representation residuals. Our simulation results demonstrate that PWLS-MCST achieves better image reconstruction quality than the conventional FBP method and PWLS with edge-preserving (EP) regularizer. It also outperformed recent advanced methods like PWLS with a learned multi-layer residual sparsifying transform prior (MARS) and PWLS with a union of learned transforms (ULTRA), especially for displaying clear edges and preserving subtle details. 

[Download paper here](https://arxiv.org/abs/2203.11565)

# MIM-SPCL

Official implementation of:

**Masked Image Modeling Advanced Spatial Prototype Contrastive Learning For Limited-Source Domain Adaptation**


## Introduction

Limited-source domain adaptation (LSDA) aims to transfer knowledge from a limited labeled source domain to an unlabeled target domain under domain shift.

In this work, we propose **MIM-SPCL**, a novel framework that explores spatial discriminative patterns from limited labeled samples and integrates domain-invariant and domain-specific information for effective cross-domain knowledge transfer.

The proposed framework consists of three key components:

- **Spatial Prototype Contrastive Learning (SPCL)**  
  Explores cross-domain consistent spatial discriminative patterns by leveraging a hybrid CNN-ViT architecture.

- **Low-Ratio Masked Image Modeling (LR-MIM)**  
  Learns target-domain-specific information from unlabeled data through lightweight reconstruction.

- **Pseudo-Label Optimization**  
  Refines pseudo-labels to provide more reliable supervision for target-domain adaptation.

The framework achieves superior performance on both natural and remote sensing scene benchmarks.


## News

🚀 Code will be released soon.


## Method Overview

<p align="center">
<img src="./figures/framework.png" width="90%">
</p>


## Dataset

Experiments are conducted on:

### Natural Scene

- Office-Home


### Remote Sensing Scene

- AID
- NWPU
- UCM


## Installation

The installation instructions will be released after the code publication.


## Results

The experimental results and pretrained models will be released soon.


## Citation

If you find this work useful, please consider citing:

```bibtex
@article{che2026mimspcl,
  title={Masked Image Modeling Advanced Spatial Prototype Contrastive Learning For Limited-Source Domain Adaptation},
  author={Che, Zhihao and Zhu, Guiying and Zhang, Tong and others},
  journal={IEEE Transactions on Image Processing},
  year={2026}
}

# Transform-Based-Representation-Zoo
Tensor Representations in Light of Transforms: An Overview and Perspectives

[![MATLAB](https://img.shields.io/badge/MATLAB-Supported-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()

This repository contains the adapted datasets and MATLAB code for the review paper: **"Transform-Based Tensor Representations in Light of Transforms: An Overview and Perspectives"**[cite: 2]. 

## ✨ Abstract
Transform-based tensor representations have become a powerful framework for modeling high-dimensional data with intrinsic multi-mode structures. In particular, the transform-based tensor singular value decomposition (t-SVD) and its variants have demonstrated remarkable effectiveness in various recovery tasks, such as multispectral image reconstruction, traffic data imputation, and spatial transcriptomics analysis. By incorporating diverse transforms into the t-SVD framework, these methods significantly enhance modeling flexibility and representation capability. Despite rapid progress over the past decade, a systematic and comprehensive overview of transform-based tensor representations is still lacking. To address this gap, this article provides a unified review of recent advances. We first revisit the fundamental algebraic framework of transform-based t-SVD, highlighting key theoretical milestones such as the best rank-$k$ approximation and exact recovery guarantees for tensor recovery. We structure the subsequent review from two fundamental perspectives: transform design and low-rank characterization. Regarding transform design, we cover the progression from traditional linear transforms to nonlinear, group-tube, functional, and spatially irregular ones. As for low-rank characterization, we delve into the evolution of model architectures and learning paradigms, ranging from shallow factorizations to deep tensor representations. Finally, representative methods are empirically evaluated to provide a comparative outlook, followed by a discussion on open challenges and future research directions. 

## 📖 Transform Design

### Linear Transform-Based Tensor Representation

* M. E. Kilmer and C. D. Martin. Factorization strategies for third-order tensors. Linear Algebra and its Applications, 2011.

* E. Kernfeld, M. E. Kilmer, and S. Aeron. Tensor-tensor products with invertible linear transforms. Linear Algebra and its Applications, 2015.

* C. Lu, X. Peng, and Y. Wei. Low-rank tensor completion with a new tensor nuclear norm induced by invertible linear transforms. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2019.

* C. Lu, J. Feng, Y. Chen, W. Liu, Z. Lin, and S. Yan. Tensor robust principal component analysis with a new tensor nuclear norm. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2020.

* T.-X. Jiang, M. K. Ng, X.-L. Zhao, and T.-Z. Huang. Framelet representation of tensor nuclear norm for third-order tensor completion. IEEE Transactions on Image Processing, 2020.

* G.-J. Song, M. K. Ng, and X.-J. Zhang. Robust tensor completion using transformed tensor singular value decomposition. Numerical Linear Algebra with Applications, 2020.

* M. E. Kilmer, L. Horesh, H. Avron, and E. Newman. Tensor-tensor algebra for optimal representation and compression of multiway data. Proceedings of the National Academy of Sciences, 2021.

* T.-X. Jiang, X.-L. Zhao, H. Zhang, and M. K. Ng. Dictionary learning with low-rank coding coefficients for tensor completion. IEEE Transactions on Neural Networks and Learning Systems, 2023.


### Nonlinear Transform-Based Tensor Representation

* B.-Z. Li, X.-L. Zhao, T.-Y. Ji, X.-J. Zhang, and T.-Z. Huang. Nonlinear transform induced tensor nuclear norm for tensor completion. Journal of Scientific Computing, 2022.

* Y.-S. Luo, X.-L. Zhao, T.-X. Jiang, Y. Chang, M. K. Ng, and C. Li. Self-supervised nonlinear transform-based tensor nuclear norm for multi-dimensional image recovery. IEEE Transactions on Image Processing, 2022.

* Z. Tu, K. Yang, J. Lu, and Q. Jiang. Tensor recovery using the tensor nuclear norm based on nonconvex and nonlinear transformations. Signal Processing, 2024.Y. Mei, 

* X. Su, H. Lin, and H. Ge. Nonconvex nonlinear transformation of low-rank approximation for tensor completion. Applied Sciences, 2024.

### Group-Tube Transform-Based Tensor Representation

* [cite_start]**Functional Transforms**: Replaces discrete atom vectors with matrix-valued functions for continuous-domain modeling, highly adaptable to irregular sampling[cite: 235, 338, 342].
* [cite_start]**Spatially Irregular Transforms**: Maps non-rectangular spatial coordinates (e.g., tissue shapes) onto a latent spatio-regular tensor domain to effectively capture multi-way dependencies[cite: 237, 366, 368].

## 🚀 Applications & Datasets

[cite_start]We provide scripts and adapted datasets [cite: 24] to reproduce the empirical evaluations discussed in the paper across three representative data recovery tasks:

1.  [cite_start]**Multispectral Image Completion**: Recovering partially observed MSI tensors[cite: 437, 438].
2.  [cite_start]**Slice-Missing Traffic Data Imputation**: Imputing consecutive missing frontal slices in spatiotemporal traffic scenarios[cite: 442, 443].
3.  [cite_start]**Spatially Irregular Spatial Transcriptomics Data Imputation**: Recovering gene expression levels on tissue spots distributed over irregular biological domains[cite: 565, 567].

## ⚙️ Getting Started

### Prerequisites
* [cite_start]MATLAB (R2020a or later recommended) [cite: 24]

### Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/benzhengli/Trans-TNN-Toolbox.git](https://github.com/benzhengli/Trans-TNN-Toolbox.git)

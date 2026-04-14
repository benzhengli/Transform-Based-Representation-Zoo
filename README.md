# Transform-Based-Tensor-Representation-Zoo
Tensor Representations in Light of Transforms: An Overview and Perspectives

[![MATLAB](https://img.shields.io/badge/MATLAB-Supported-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()

This repository contains the adapted datasets and MATLAB code for the review paper: **Transform-Based Tensor Representations in Light of Transforms: An Overview and Perspectives**. 

## 📝 Citation

If you find this repository or our review paper useful in your research, please consider citing our work:

```bibtex
@article{li2026tensor,
  title   = {Tensor Representations in Light of Transforms: An Overview and Perspectives},
  author  = {Li, Ben-Zheng and Wang, Chuan and Zheng, Yu-Bang and Liu, Sheng and Luo, Yisi and Jiang, Tai-Xiang and Zhao, Xi-Le},
  journal = {CSIAM Transactions on Applied Mathematics},
  volume  = {x},
  number  = {x},
  pages   = {1--30},
  year    = {20xx},
  publisher={Global-Science Press}
}
```

## ✨ Abstract
Transform-based tensor representations have become a powerful framework for modeling high-dimensional data with intrinsic multi-mode structures. Among these, the transform-based tensor singular value decomposition (t-SVD) and its variants have demonstrated remarkable effectiveness in various recovery tasks. By incorporating diverse transforms, the t-SVD framework significantly enhances modeling flexibility and representation capability. Despite rapid progress over the past decade, a systematic and comprehensive overview of this paradigm, specifically the t-SVD framework and its variants, remains absent. To bridge this gap, this article provides a unified and focused review of recent advances. We first revisit the fundamental algebraic framework of transform-based t-SVD, highlighting key theoretical milestones such as the best rank-$k$ approximation and exact recovery guarantees for tensor recovery. Then, we structure the subsequent review from two fundamental perspectives: transform design and low-rank characterization. Regarding transform design, we cover the progression from traditional linear transforms to nonlinear, group-tube, functional, and spatially irregular ones. As for low-rank characterization, we delve into the evolution of representation paradigms, ranging from matrix factorizations to deep tensor representations. Finally, several representative methods are empirically evaluated to provide a comparative outlook, followed by a discussion on open challenges and future research directions.


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

* Z. Tu, K. Yang, J. Lu, and Q. Jiang. Tensor recovery using the tensor nuclear norm based on nonconvex and nonlinear transformations. Signal Processing, 2024. 

* Y. Mei, X. Su, H. Lin, and H. Ge. Nonconvex nonlinear transformation of low-rank approximation for tensor completion. Applied Sciences, 2024.

### Group-Tube Transform-Based Tensor Representation

* B.-Z. Li, X.-L. Zhao, X. Zhang, T.-Y. Ji, X. Chen, and M. K. Ng. A learnable group-tube transform induced tensor nuclear norm and its application for tensor completion. SIAM Journal on Imaging Sciences, 2023.

* G.-W. Yang, L. Yang, T.-X. Jiang, G. Liu, and M. K. Ng. Delta: Deep low-rank tensor representation for multi-dimensional data recovery. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2025.

* B.-Z. Li, X.-L. Zhao, H. Zhang, and D. Chu. Importance-aware nonlocal tensor nuclear norm for high-dimensional image recovery. Inverse Problems, 2026.


### Functional Transforme-Based Tensor Representation

* C. Wang, X.-L. Zhao, Y.-B. Zheng, B.-Z. Li, and M. K. Ng. Functional tensor singular value decomposition. SIAM Journal on Scientific Computing, 2025.

### Spatially Irregular Transform-Based Tensor Representation

* H. Zhang, T.-Z. Huang, X.-L. Zhao, S. Zhang, J.-Y. Xie, T.-X. Jiang, and M. K. Ng. Learnable transform-assisted tensor decomposition for spatio-irregular multidimensional data recovery. ACM Trans. Knowl. Discov. Data, 2024.

## 📖 Transformed Low-Rank Characterization

* P. Zhou, C. Lu, Z. Lin, and C. Zhang. Tensor factorization for low-rank tensor completion. IEEE Transactions on Image Processing, 2018.
  
* F. Wu, Y. Li, C. Li, and Y. Wu. A fast tensor completion method based on tensor qr decomposition and tensor nuclear norm minimization. IEEE Transactions on Computational Imaging, 2021.
  
* Y. Zheng and A.-B. Xu. Tensor completion via tensor qr decomposition and l2,1-norm minimization. Signal Processing, 2021.
  
* J.-Y. Li, J.-Y. Xie, Y.-S. Luo, X.-L. Zhao, and J.-L. Wang. H2tf for hyperspectral image denoising: Where hierarchical nonlinear transform meets hierarchical matrix factorization. IEEE Geoscience and Remote Sensing Letters, 2023.

* T.-W. Zhou, X.-L. Zhao, J.-L. Wang, Y.-S. Luo, M. Wang, and X.-X. Bai. Dtr: A unified deep tensor representation framework for multimedia data recovery. IEEE Transactions on Multimedia, 2025. 


## Multi-Directional and Higher-Order Extensions

* Y.-B. Zheng, T.-Z. Huang, X.-L. Zhao, T.-X. Jiang, T.-Y. Ji, and T.-H. Ma. Tensor n-tubal rank and its convex relaxation for low-rank tensor recovery. Information Sciences, 2020.

* A. Wang, Q. Zhao, Z. Jin, C. Li, and G. Zhou. Robust tensor decomposition via orientation invariant tubal nuclear norms. Science China Technological Sciences, 2022.

* L. Feng, C. Zhu, Z. Long, J. Liu, and Y. Liu. Multiplex transformed tensor decomposition for multidimensional image recovery. IEEE Transactions on Image Processing, 2023.

* H. Wang, J. Peng, W. Qin, J. Wang, and D. Meng. Guaranteed tensor recovery fused low-rankness and smoothness. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023.

* J.-L. Wang, T.-Z. Huang, X.-L. Zhao, Y.-S. Luo, and T.-X. Jiang. Conot: Coupled nonlinear transform-based low-rank tensor representation for multidimensional image completion. IEEE Transactions on Neural Networks and Learning Systems, 2024.

* Z.-W. Shi, Y.-B. Zheng, Y. Zhang, and H.-C. Li. Multidimensional nonlinear transform-based tensor representation for high-dimensional image reconstruction. Pattern Recognition, 2025.


## 🚀 Applications & Datasets

We provide scripts and adapted datasets to reproduce the empirical evaluations discussed in the paper across three representative data recovery tasks:

1.  **Multispectral Image Completion**: Recovering partially observed MSI tensors.
2.  **Slice-Missing Traffic Data Imputation**: Imputing consecutive missing frontal slices in spatiotemporal traffic scenarios.
3.  **Spatially Irregular Spatial Transcriptomics Data Imputation**: Recovering gene expression levels on tissue spots distributed over irregular biological domains.

## ⚙️ Getting Started

### Prerequisites
* [cite_start]MATLAB (R2020a or later recommended) [cite: 24]

### Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/benzhengli/Transform-Based-Representation-Zoo/tree/main](https://github.com/benzhengli/Transform-Based-Representation-Zoo/tree/main)

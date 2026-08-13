# Transform-Based Tensor Representation Zoo

Companion repository for the review article:

**Tensor Representations in Light of Transforms: An Overview and Perspectives**

[![MATLAB](https://img.shields.io/badge/MATLAB-Supported-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
[![Paper](https://img.shields.io/badge/Paper-IEEE%20TNNLS-blue.svg)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5962385)

This repository accompanies our review paper prepared for **[IEEE Transactions on Neural Networks and Learning Systems (TNNLS)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5962385)**. It collects representative papers, code links, datasets, and MATLAB resources related to transform-based tensor representations, with a focus on transform-based t-SVD models and transformed low-rank characterization.

## Citation

If you find this repository or our review paper useful in your research, please consider citing our work:

```bibtex
@article{li2026tensor,
  title   = {Tensor Representations in Light of Transforms: An Overview and Perspectives},
  author  = {Li, Ben-Zheng and Wang, Chuan and Zheng, Yu-Bang and Liu, Sheng and Luo, Yisi and Jiang, Tai-Xiang and Zhao, Xi-Le and Ng, Michael K.},
  journal = {IEEE Transactions on Neural Networks and Learning Systems},
  year    = {2026},
  note    = {Manuscript submitted}
}
```

## Abstract

Transform-based tensor representations have become a powerful framework for modeling high-dimensional data with intrinsic multi-mode structures. Among these, the transform-based tensor singular value decomposition (t-SVD) and its variants have demonstrated remarkable effectiveness in various recovery tasks. By incorporating diverse transforms, the t-SVD framework significantly enhances modeling flexibility and representation capability. Despite rapid progress over the past decade, a systematic and comprehensive overview of this paradigm, specifically the t-SVD framework and its variants, remains absent. To bridge this gap, this article provides a unified and focused review of recent advances. We first revisit the fundamental algebraic framework of transform-based t-SVD, highlighting key theoretical milestones such as the best rank-$k$ approximation and exact recovery guarantees for tensor recovery. Then, we structure the subsequent review from two fundamental perspectives: transform design and transformed low-rank characterization. Regarding transform design, we cover the progression from traditional linear transforms to nonlinear, group-tube, functional, and spatially irregular ones. As for transformed low-rank characterization, we delve into the evolution of representation paradigms, ranging from matrix factorizations to deep tensor representations. Finally, several representative methods are empirically evaluated to provide a comparative outlook, followed by a discussion on open challenges and future research directions.

## Repository Overview

This repository is organized around two complementary views of transform-based tensor representation:

- **Transform design**: from fixed linear transforms to nonlinear, group-tube, functional, and spatially irregular transforms.
- **Transformed low-rank characterization**: from shallow matrix/tensor factorizations to multi-directional, higher-order, and learning-oriented extensions.
- **Applications and datasets**: representative recovery tasks used in the review, including multispectral image completion, slice-missing traffic data imputation, and spatially irregular spatial transcriptomics data imputation.

## Transform Design

### Linear Transform-Based Tensor Representation

| Paper | Venue | Year | Code |
|---|---|---:|---|
| [Factorization strategies for third-order tensors](https://www.sciencedirect.com/science/article/pii/S0024379510004830) | Linear Algebra and its Applications | 2011 |  |
| [Tensor-tensor products with invertible linear transforms](https://www.sciencedirect.com/science/article/pii/S0024379515004358) | Linear Algebra and its Applications | 2015 |  |
| [Low-rank tensor completion with a new tensor nuclear norm induced by invertible linear transforms](https://ieeexplore.ieee.org/document/8953215) | CVPR | 2019 |  |
| [Tensor robust principal component analysis with a new tensor nuclear norm](https://ieeexplore.ieee.org/document/8606166) | IEEE Transactions on Pattern Analysis and Machine Intelligence | 2020 | [Code](https://github.com/canyilu/Tensor-Robust-Principal-Component-Analysis-TRPCA) |
| [Framelet representation of tensor nuclear norm for third-order tensor completion](https://ieeexplore.ieee.org/document/9115254) | IEEE Transactions on Image Processing | 2020 | [Code](https://github.com/TaiXiangJiang/Framelet-TNN) |
| [Robust tensor completion using transformed tensor singular value decomposition](https://onlinelibrary.wiley.com/doi/abs/10.1002/nla.2299) | Numerical Linear Algebra with Applications | 2020 | [Code](https://github.com/xjzhang008/Transformed-Tensor-SVD) |
| [Tensor-tensor algebra for optimal representation and compression of multiway data](https://pubmed.ncbi.nlm.nih.gov/34234014/) | Proceedings of the National Academy of Sciences | 2021 |  |
| [Low Rank Tensor Completion with Poisson Observations](https://ieeexplore.ieee.org/document/9354598) | IEEE Transactions on Pattern Analysis and Machine Intelligence | 2022 | [Code](https://xj-zhang.github.io/math/publications.html) |
| [Dictionary learning with low-rank coding coefficients for tensor completion](https://ieeexplore.ieee.org/document/9525838) | IEEE Transactions on Neural Networks and Learning Systems | 2023 | [Code](https://taixiangjiang.github.io/) |

### Nonlinear Transform-Based Tensor Representation

| Paper | Venue | Year | Code |
|---|---|---:|---|
| [Nonlinear transform induced tensor nuclear norm for tensor completion](https://link.springer.com/article/10.1007/s10915-022-01937-1) | Journal of Scientific Computing | 2022 | [Code](https://github.com/benzhengli/NTTNN-code/tree/main) |
| [Self-supervised nonlinear transform-based tensor nuclear norm for multi-dimensional image recovery](https://ieeexplore.ieee.org/document/9780890) | IEEE Transactions on Image Processing | 2022 | [Code](https://github.com/YisiLuo/S2NTNN) |
| [Tensor recovery using the tensor nuclear norm based on nonconvex and nonlinear transformations](https://www.sciencedirect.com/science/article/abs/pii/S0165168424000197) | Signal Processing | 2024 |  |
| [A nonlinear high-order transformations-based method for high-order tensor completion](https://www.sciencedirect.com/science/article/abs/pii/S0165168424001336) | Signal Processing | 2024 |  |
| [Nonconvex nonlinear transformation of low-rank approximation for tensor completion](https://www.mdpi.com/2076-3417/14/24/11895) | Applied Sciences | 2024 |  |
| [Fusion of low-rankness and smoothness under learnable nonlinear transformation for tensor completion](https://www.sciencedirect.com/science/article/abs/pii/S095070512400551) | Knowledge-Based Systems | 2024 |  |
| [MNT-TNN: spatiotemporal traffic data imputation via compact multimode nonlinear transform-based tensor nuclear norm](https://www.sciencedirect.com/science/article/abs/pii/S0968090X25003523) | Transportation Research Part C: Emerging Technologies | 2025 | [Code](https://github.com/Luoauoa/MNT-TNN) |
| [Multidimensional nonlinear transform-based tensor representation for high-dimensional image reconstruction](https://www.sciencedirect.com/science/article/abs/pii/S0031320325003942) | Pattern Recognition | 2025 |  |
| [Nonlinear transformed low-rank quaternion tensor total variation for multidimensional color image completion](https://ieeexplore.ieee.org/document/11421614) | IEEE Transactions on Image Processing | 2026 |  |

### Group-Tube Transform-Based Tensor Representation

| Paper | Venue | Year | Code |
|---|---|---:|---|
| [A learnable group-tube transform induced tensor nuclear norm and its application for tensor completion](https://epubs.siam.org/doi/10.1137/22M1531907) | SIAM Journal on Imaging Sciences | 2023 |  |
| [Delta: Deep low-rank tensor representation for multi-dimensional data recovery](https://ieeexplore.ieee.org/document/11231348) | IEEE Transactions on Pattern Analysis and Machine Intelligence | 2025 |  |
| [Importance-aware nonlocal tensor nuclear norm for high-dimensional image recovery](https://iopscience.iop.org/article/10.1088/1361-6420/ae2ef7) | Inverse Problems | 2026 |  |

### Functional Transform-Based Tensor Representation

| Paper | Venue | Year | Code |
|---|---|---:|---|
| [Generalized tensor decomposition for understanding multi-output regression under combinatorial shifts](https://proceedings.neurips.cc/paper_files/paper/2024/hash/54ece32fe923c26b3de15d0da182e008-Abstract-Conference.html) | NeurIPS | 2024 | [Code](https://github.com/pingzaiwang/FtSVD4MORCDS) |
| [Functional transform-based low-rank tensor factorization for multi-dimensional data recovery](https://link.springer.com/chapter/10.1007/978-3-031-72751-1_3) | ECCV | 2024 |  |
| [Towards a geometric understanding of tensor learning via the t-product](https://neurips.cc/virtual/2025/loc/san-diego/poster/120278) | NeurIPS | 2025 | [Code](https://github.com/pingzaiwang/BTR4tGeometry) |
| [Functional tensor singular value decomposition](https://epubs.siam.org/doi/10.1137/24M1644687) | SIAM Journal on Scientific Computing | 2025 |  |
| [Hincot: Hierarchical nonlinear continuous transform-based tensor representation for multi-dimensional data recovery](https://ojs.aaai.org/index.php/AAAI/article/view/39982) | AAAI | 2026 |  |
| [Gaussian splatting-based low-rank tensor representation for multi-dimensional image recovery](https://cvpr.thecvf.com/virtual/2026/poster/38121) | CVPR | 2026 |  |
| [Neural operator-grounded continuous tensor function representation and its applications](https://arxiv.org/html/2603.01812v1) | arXiv | 2026 |  |

### Spatially Irregular Transform-Based Tensor Representation

| Paper | Venue | Year | Code |
|---|---|---:|---|
| [Learnable transform-assisted tensor decomposition for spatio-irregular multidimensional data recovery](https://dl.acm.org/doi/10.1145/3701235) | ACM Transactions on Knowledge Discovery from Data | 2024 | [Code](https://github.com/haozhangSWJTU/Irregular-Tensor-Toolbox) |

## Transformed Low-Rank Characterization

| Paper | Venue | Year | Code |
|---|---|---:|---|
| [Tensor factorization for low-rank tensor completion](https://ieeexplore.ieee.org/document/8066348) | IEEE Transactions on Image Processing | 2018 | [Code](https://panzhous.github.io/publication/) |
| [A fast tensor completion method based on tensor QR decomposition and tensor nuclear norm minimization](https://ieeexplore.ieee.org/abstract/document/9627784) | IEEE Transactions on Computational Imaging | 2021 |  |
| [Tensor completion via tensor QR decomposition and l2,1-norm minimization](https://www.sciencedirect.com/science/article/abs/pii/S0165168421002772) | Signal Processing | 2021 |  |
| [H2TF for hyperspectral image denoising: Where hierarchical nonlinear transform meets hierarchical matrix factorization](https://ieeexplore.ieee.org/abstract/document/10181304) | IEEE Geoscience and Remote Sensing Letters | 2023 |  |
| [DTR: A unified deep tensor representation framework for multimedia data recovery](https://ieeexplore.ieee.org/document/11045408) | IEEE Transactions on Multimedia | 2025 |  |

### Multi-Directional Extensions

| Paper | Venue | Year | Code |
|---|---|---:|---|
| [Tensor completion based on triple tubal nuclear norm](https://www.mdpi.com/1999-4893/11/7/94) | Algorithms | 2018 |  |
| [Tensor n-tubal rank and its convex relaxation for low-rank tensor recovery](https://www.sciencedirect.com/science/article/pii/S0020025520303923) | Information Sciences | 2020 | [Code](https://yubangzheng.github.io/) |
| [Multi-dimensional visual data completion via low-rank tensor representation under coupled transform](https://ieeexplore.ieee.org/document/9372832) | IEEE Transactions on Image Processing | 2021 |  |
| [Robust tensor decomposition via orientation invariant tubal nuclear norms](https://link.springer.com/article/10.1007/s11431-021-1976-2) | Science China Technological Sciences | 2022 |  |
| [Multiplex transformed tensor decomposition for multidimensional image recovery](https://ieeexplore.ieee.org/document/10153488/) | IEEE Transactions on Image Processing | 2023 | [Code](https://github.com/yipengliu/mttd) |
| [Guaranteed tensor recovery fused low-rankness and smoothness](https://ieeexplore.ieee.org/document/10078018) | IEEE Transactions on Pattern Analysis and Machine Intelligence | 2023 | [Code](https://github.com/wanghailin97/Guaranteed-Tensor-Recovery-Fused-Low-rankness-and-Smoothness) |
| [CONOT: Coupled nonlinear transform-based low-rank tensor representation for multidimensional image completion](https://ieeexplore.ieee.org/document/9946011) | IEEE Transactions on Neural Networks and Learning Systems | 2024 |  |
| [Hyperspectral image denoising via transformed tensor nuclear norm and nonconvex regularization in spatial-spectral gradient domains](https://ieeexplore.ieee.org/document/11262236) | IEEE Transactions on Geoscience and Remote Sensing | 2025 |  |

### Higher-Order Extensions

| Paper | Venue | Year | Code |
|---|---|---:|---|
| [An order-p tensor factorization with applications in imaging](https://epubs.siam.org/doi/10.1137/110841229) | SIAM Journal on Scientific Computing | 2013 |  |
| [Low-rank high-order tensor completion with applications in visual data](https://ieeexplore.ieee.org/document/9730793) | IEEE Transactions on Image Processing | 2022 | [Code](https://github.com/Qinwenjinswu/TIP-Code) |
| [HOT-SVD: Higher order t-singular value decomposition for tensors based on tensor-tensor product](https://link.springer.com/article/10.1007/s40314-022-02107-7) | Computational and Applied Mathematics | 2022 |  |
| [Revisiting high-order tensor singular value decomposition from basic element perspective](https://ieeexplore.ieee.org/document/10665981) | IEEE Transactions on Signal Processing | 2024 | [Code](https://github.com/liu-sheng/code_METNN) |
| [Nonconvex robust high-order tensor completion using randomized low-rank approximation](https://ieeexplore.ieee.org/document/10496551) | IEEE Transactions on Image Processing | 2024 |  |

### Extensions to Diversified Machine Learning Tasks

| Paper | Venue | Year | Code |
|---|---|---:|---|
| [Essential tensor learning for multi-view spectral clustering](https://ieeexplore.ieee.org/document/8736495) | IEEE Transactions on Image Processing | 2019 | [Code](https://github.com/sikid/Code-for-ETLMSC) |
| [Infrared small target detection based on partial sum of the tensor nuclear norm](https://www.mdpi.com/2072-4292/11/4/382) | Remote Sensing | 2019 |  |
| [Regularized high dimension low tubal-rank tensor regression](https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-16/issue-1/Regularized-high-dimension-low-tubal-rank-tensor-regression/10.1214/22-EJS2004.pdf#:~:text=In%20this%20work%2C%20we%20leverage%20the%20recently%20developed,tubal%20rank%20tensor%20and%20a%20structured%20sparse%20one.) | Electronic Journal of Statistics | 2022 |  |
| [TPpred-ATMV: therapeutic peptide prediction by adaptive multi-view tensor learning model](https://academic.oup.com/bioinformatics/article/38/10/2712/6564690?login=false) | Bioinformatics | 2022 | [Code](https://github.com/cokeyk/TPpred-ATMV) |
| [Attention-guided low-rank tensor completion](https://ieeexplore.ieee.org/document/10601492) | IEEE Transactions on Pattern Analysis and Machine Intelligence | 2024 | [Code](https://github.com/mtntruong/AGTC) |
| [Low-rank tensor transitions (LoRT) for transferable tensor regression](https://openreview.net/forum?id=huu5JErrT1) | ICML | 2025 | [Code](https://github.com/pingzaiwang/LoRT) |
| [Data-Adaptive Transformed Bilateral Tensor Low-Rank Representation for Clustering](https://arxiv.org/abs/2510.20077v1) | arXiv | 2025 | [Code](https://github.com/xianchaoxiu/TBTLRR) |
| [Nonconvex low-rank tensor representation for multi-view subspace clustering with insufficient observed samples](https://ieeexplore.ieee.org/document/10938849) | IEEE Transactions on Knowledge and Data Engineering | 2025 |  |
| [Advanced High-Order Graph Convolutional Networks with Assorted Time-Frequency Transforms](https://ieeexplore.ieee.org/document/11429643) | IEEE/CAA Journal of Automatica Sinica | 2026 |  |
| [ReFTA: Breaking the weight reconstruction bottleneck in tensorized parameter-efficient fine-tuning](https://cvpr.thecvf.com/virtual/2026/poster/38595) | CVPR | 2026 |  |

## Applications and Datasets

The review compares representative transform-based tensor methods on three data recovery tasks. The corresponding scripts and adapted datasets will be organized in this repository following the structure below.

1.  **Multispectral Image Completion**: Recovering partially observed MSI tensors.

* Dataset: CAVE Dataset.

* Description: Comprises 32 multispectral images (MSIs) captured in controlled indoor environments. Each MSI features a spatial resolution of 512 x 512 pixels across 31 spectral bands, spanning a wavelength range from 400 nm to 700 nm with a spectral interval of 10 nm. All data are rescaled to the interval [0,1] and resized to 256 x 256 x 31 for evaluation.

* Original Link: https://cave.cs.columbia.edu/repository/Multispectral

2.  **Slice-Missing Traffic Data Imputation**: Imputing consecutive missing frontal slices in spatiotemporal traffic scenarios.

* Dataset: Guangzhou Urban Traffic Speed Dataset.

* Description: Organized as a tensor of size 214 x 61 x 144, corresponding to 214 road segments, 61 days (Aug. 1 - Sep. 30, 2016), and 144 time intervals per day with 10-minute resolution.

* Original Link: https://doi.org/10.5281/zenodo.1205229

   
3.  **Spatially Irregular Spatial Transcriptomics Data Imputation**:
Recovering gene expression levels that suffer from severe missingness during acquisition, an essential step for subsequent biological analysis.

* Dataset: Human dorsolateral prefrontal cortex (DLPFC) spatial transcriptomics dataset.

* Description: Unlike standard tensor completion settings defined on rectangular grids, this data is collected over an irregular biological domain. The dataset inherently consists of 2702 valid tissue spots (mode-3 fibers), with the third dimension representing 50 distinct genes. For evaluation, the nonzero gene expression entries are treated as the reference set, from which 50%, 70%, and 90% entries are uniformly missing as observations.

* Original Link: http://spatial.libd.org/spatialLIBD/

## Getting Started

### Clone the repository

1. Clone the repository:
   ```bash
   git clone https://github.com/benzhengli/Transform-Based-Representation-Zoo.git
   cd Transform-Based-Representation-Zoo
   ```

2. Add the repository to the MATLAB path:
   ```matlab
   addpath(genpath('Transform-Based-Representation-Zoo'));
   savepath;
   ```

### Code release

The public code and adapted datasets are being organized. The planned demo entries are:

- `Demo_MSI_Completion`: multispectral image completion.
- `Demo_Traffic_Imputation`: slice-missing traffic data imputation.
- `Demo_Spatial_Irregular`: spatially irregular spatial transcriptomics data imputation.

## Repository Structure

```text
.
|-- README.md
|-- Demo_MSI_Completion/        # Multispectral image completion experiments
|-- Demo_Traffic_Imputation/    # Slice-missing traffic data imputation experiments
|-- Demo_Spatial_Irregular/     # Spatially irregular data imputation experiments
|-- Datasets/                   # Adapted and pre-processed datasets
|-- Methods/                    # Representative transform-based TNN methods
|   |-- Linear/                 # TNN, DCTTNN, UTNN, DTNN
|   |-- Nonlinear/              # NTTNN and related nonlinear models
|   |-- GroupTube/              # Group-tube and nonlocal transform models
|   |-- Functional/             # Functional transform-based models
|   `-- Irregular/              # Spatially irregular tensor models
`-- Utils/                      # Shared metrics and helper functions
```

## Contact

If you have any questions or suggestions, please feel free to open an issue or contact:

* Ben-Zheng Li: mathlibz@ccnu.edu.cn

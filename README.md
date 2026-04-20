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

* M. E. Kilmer and C. D. Martin. Factorization strategies for third-order tensors. Linear Algebra and its Applications, 2011. [[Website]](https://www.sciencedirect.com/science/article/pii/S0024379510004830)

* E. Kernfeld, M. E. Kilmer, and S. Aeron. Tensor-tensor products with invertible linear transforms. Linear Algebra and its Applications, 2015.
  [[Website]](https://www.sciencedirect.com/science/article/pii/S0024379515004358)
  
* C. Lu, X. Peng, and Y. Wei. Low-rank tensor completion with a new tensor nuclear norm induced by invertible linear transforms. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2019.
  [[Website]](https://ieeexplore.ieee.org/document/8953215)

* C. Lu, J. Feng, Y. Chen, W. Liu, Z. Lin, and S. Yan. Tensor robust principal component analysis with a new tensor nuclear norm. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2020.
  [[Website]](https://ieeexplore.ieee.org/document/8606166) [[Code]](https://github.com/canyilu/Tensor-Robust-Principal-Component-Analysis-TRPCA)

* T.-X. Jiang, M. K. Ng, X.-L. Zhao, and T.-Z. Huang. Framelet representation of tensor nuclear norm for third-order tensor completion. IEEE Transactions on Image Processing, 2020.
  [[Website]](https://ieeexplore.ieee.org/document/9115254) [[Code]](https://github.com/TaiXiangJiang/Framelet-TNN)

* G.-J. Song, M. K. Ng, and X.-J. Zhang. Robust tensor completion using transformed tensor singular value decomposition. Numerical Linear Algebra with Applications, 2020.
  [[Website]](https://onlinelibrary.wiley.com/doi/abs/10.1002/nla.2299) [[Code]](https://github.com/xjzhang008/Transformed-Tensor-SVD)
  
* X. Zhang and M. K. Ng. Low Rank Tensor Completion with Poisson Observations, IEEE Transactions on Pattern Analysis and Machine Intelligence, 44(8):4239-4251, 2022.
  [[Website]](https://ieeexplore.ieee.org/document/9354598) [[Code]](https://xj-zhang.github.io/math/publications.html)

* M. E. Kilmer, L. Horesh, H. Avron, and E. Newman. Tensor-tensor algebra for optimal representation and compression of multiway data. Proceedings of the National Academy of Sciences, 2021.
  [[Website]](https://pubmed.ncbi.nlm.nih.gov/34234014/)

* T.-X. Jiang, X.-L. Zhao, H. Zhang, and M. K. Ng. Dictionary learning with low-rank coding coefficients for tensor completion. IEEE Transactions on Neural Networks and Learning Systems, 2023.
  [[Website]](https://ieeexplore.ieee.org/document/9525838) [[Code]](https://taixiangjiang.github.io/)



### Nonlinear Transform-Based Tensor Representation

* B.-Z. Li, X.-L. Zhao, T.-Y. Ji, X.-J. Zhang, and T.-Z. Huang. Nonlinear transform induced tensor nuclear norm for tensor completion. Journal of Scientific Computing, 2022.
  [[Website]](https://link.springer.com/article/10.1007/s10915-022-01937-1) [[Code]](https://github.com/benzhengli/NTTNN-code/tree/main)

* Y.-S. Luo, X.-L. Zhao, T.-X. Jiang, Y. Chang, M. K. Ng, and C. Li. Self-supervised nonlinear transform-based tensor nuclear norm for multi-dimensional image recovery. IEEE Transactions on Image Processing, 2022.
  [[Website]](https://ieeexplore.ieee.org/document/9780890) [[Code]](https://github.com/YisiLuo/S2NTNN)

* Z. Tu, K. Yang, J. Lu, and Q. Jiang. Tensor recovery using the tensor nuclear norm based on nonconvex and nonlinear transformations. Signal Processing, 2024.
  [[Website]](https://www.sciencedirect.com/science/article/abs/pii/S0165168424000197)

* L. Luo, Z. Tu, J. Lu, C. Wang, C. Xu, A nonlinear high-order transformations-based method for high-order tensor completion, Signal Processing, 225 (2024), p. 109514.
   [[Website]](https://www.sciencedirect.com/science/article/abs/pii/S0165168424001336)

* Y. Mei, X. Su, H. Lin, and H. Ge. Nonconvex nonlinear transformation of low-rank approximation for tensor completion. Applied Sciences, 2024.
  [[Website]](https://www.mdpi.com/2076-3417/14/24/11895)

* Y. Zhang, Z. Tu, J. Lu, C. Xu, L. Shen, Fusion of low-rankness and smoothness under learnable nonlinear transformation for tensor completion, Knowledge-Based Systems, 296 (2024), p. 111917.
   [[Website]](https://www.sciencedirect.com/science/article/abs/pii/S095070512400551)

* Y. Lu, M. Yousaf, X. Meng, E. Chen, MNT-TNN: spatiotemporal traffic data imputation via compact multimode nonlinear transform-based tensor nuclear norm, Transportation Research Part C: Emerging Technologies, 180 (2025), p. 105348.
  [[Website]](https://www.sciencedirect.com/science/article/abs/pii/S0968090X25003523) [[Code]](https://github.com/Luoauoa/MNT-TNN)

* Z.-W. Shi, Y.-B. Zheng, Y. Zhang, H.-C. Li, Multidimensional nonlinear transform-based tensor representation for high-dimensional image reconstruction, Pattern Recognition, 168 (2025), p. 111734.
 [[Website]](https://www.sciencedirect.com/science/article/abs/pii/S0031320325003942)

* L. Yang, Y. Hu, T.-X. Jiang, Y. Wei, G. Liu, M. K. Ng, Nonlinear transformed low-rank quaternion tensor total variation for multidimensional color image completion, IEEE Transactions on Image Processing, 35 (2026), pp. 2470–2483
  [[Website]](https://ieeexplore.ieee.org/document/11421614)



### Group-Tube Transform-Based Tensor Representation

* B.-Z. Li, X.-L. Zhao, X. Zhang, T.-Y. Ji, X. Chen, and M. K. Ng. A learnable group-tube transform induced tensor nuclear norm and its application for tensor completion. SIAM Journal on Imaging Sciences, 2023.
   [[Website]](https://epubs.siam.org/doi/10.1137/22M1531907)

* G.-W. Yang, L. Yang, T.-X. Jiang, G. Liu, and M. K. Ng. Delta: Deep low-rank tensor representation for multi-dimensional data recovery. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2025.
  [[Website]](https://ieeexplore.ieee.org/document/11231348)

* B.-Z. Li, X.-L. Zhao, H. Zhang, and D. Chu. Importance-aware nonlocal tensor nuclear norm for high-dimensional image recovery. Inverse Problems, 2026.
[[Website]](https://iopscience.iop.org/article/10.1088/1361-6420/ae2ef7)

### Functional Transforme-Based Tensor Representation

* A. Wang, Y. Qiu, M. Bai, Z. Jin, G. Zhou, and Q. Zhao. Generalized tensor decomposition for understanding multi-output regression under combinatorial shifts. Advances in Neural Information Processing Systems, 2024.
[[Website]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/54ece32fe923c26b3de15d0da182e008-Abstract-Conference.html)
[[Code]](https://github.com/pingzaiwang/FtSVD4MORCDS)

* A. Wang, Y. Qiu, H. Huang, Z. Jin, G. Zhou, and Q. Zhao. Towards a geometric understanding of tensor learning via the t-product. Advances in Neural Information Processing Systems, 2025.
 [[Website]](https://neurips.cc/virtual/2025/loc/san-diego/poster/120278) [[Code]](https://github.com/pingzaiwang/BTR4tGeometry)

* C. Wang, X.-L. Zhao, Y.-B. Zheng, B.-Z. Li, and M. K. Ng. Functional tensor singular value decomposition. SIAM Journal on Scientific Computing, 2025.
  [[Website]](https://epubs.siam.org/doi/10.1137/24M1644687) 

* J. Wang and X.-L. Zhao, Functional transform-based low-rank tensor factorization for multi-dimensional data recovery, in Computer Vision – ECCV, 2024.
  [[Website]](https://link.springer.com/chapter/10.1007/978-3-031-72751-1_3)

* T. Yang, W. Wu, and T. Huang, Hincot: Hierarchical nonlinear continuous transform-based tensor representation for multi-dimensional data recovery, in Proceedings of the AAAI Conference on Artificial Intelligence, vol. 40, 2026, pp. 27621–27629.
  [[Website]](https://ojs.aaai.org/index.php/AAAI/article/view/39982) [[Poster]](https://underline.io/lecture/140013-hincot-hierarchical-nonlinear-continuous-transform-based-tensor-representation-for-multi-dimensional-data-recovery) 

* Y. Zeng, X.-L. Zhao, W.-H. Wu, T.-Y. Ji, and C. Wang, Gaussian splatting-based low-rank tensor representation for multi-dimensional image recovery, CVPR,2026.
  [[Website]](https://cvpr.thecvf.com/virtual/2026/poster/38121)

* R. Su, X.-L. Zhao, S. Liu, W.-H. Wu, Y. Luo, and M. K. Ng, Neural operator-grounded continuous tensor function representation and its applications, arXiv preprint arXiv:2603.01812, 2026.
  [[Website]](https://arxiv.org/html/2603.01812v1)  
  

### Spatially Irregular Transform-Based Tensor Representation

* H. Zhang, T.-Z. Huang, X.-L. Zhao, S. Zhang, J.-Y. Xie, T.-X. Jiang, and M. K. Ng. Learnable transform-assisted tensor decomposition for spatio-irregular multidimensional data recovery. ACM Transactions on Knowledge Discovery from Data, 2024.
  [[Website]](https://dl.acm.org/doi/10.1145/3701235) [[Code]](https://github.com/haozhangSWJTU/Irregular-Tensor-Toolbox)


## 📖 Transformed Low-Rank Characterization

* P. Zhou, C. Lu, Z. Lin, and C. Zhang. Tensor factorization for low-rank tensor completion. IEEE Transactions on Image Processing, 2018.
  [[Website]](https://ieeexplore.ieee.org/document/8066348) [[Code]](https://panzhous.github.io/publication/)
  
* F. Wu, Y. Li, C. Li, and Y. Wu. A fast tensor completion method based on tensor QR decomposition and tensor nuclear norm minimization. IEEE Transactions on Computational Imaging, 2021.
   [[Website]](https://ieeexplore.ieee.org/abstract/document/9627784) 
  
* Y. Zheng and A.-B. Xu. Tensor completion via tensor QR decomposition and l2,1-norm minimization. Signal Processing, 2021.
  [[Website]](https://www.sciencedirect.com/science/article/abs/pii/S0165168421002772)
  
* J.-Y. Li, J.-Y. Xie, Y.-S. Luo, X.-L. Zhao, and J.-L. Wang. H2TF for hyperspectral image denoising: Where hierarchical nonlinear transform meets hierarchical matrix factorization. IEEE Geoscience and Remote Sensing Letters, 2023.
  [[Website]](https://ieeexplore.ieee.org/abstract/document/10181304)

* T.-W. Zhou, X.-L. Zhao, J.-L. Wang, Y.-S. Luo, M. Wang, and X.-X. Bai. DTR: A unified deep tensor representation framework for multimedia data recovery. IEEE Transactions on Multimedia, 2025.
   [[Website]](https://ieeexplore.ieee.org/document/11045408)


### Multi-Directional Extensions

* D. Wei, A. Wang, X. Feng, B. Wang, and B. Wang. Tensor completion based on triple tubal nuclear norm. Algorithms, 2018.
  [[Website]](https://www.mdpi.com/1999-4893/11/7/94)

* Y.-B. Zheng, T.-Z. Huang, X.-L. Zhao, T.-X. Jiang, T.-Y. Ji, and T.-H. Ma. Tensor n-tubal rank and its convex relaxation for low-rank tensor recovery. Information Sciences, 2020.
  [[Website]](https://www.sciencedirect.com/science/article/pii/S0020025520303923) [[Code]](https://yubangzheng.github.io/)

* J.-L. Wang, T.-Z. Huang, X.-L. Zhao, T.-X. Jiang, and M. K. Ng. Multi-dimensional visual data completion via low-rank tensor representation under coupled transform. IEEE Transactions on Image Processing, 2021.
  [[Website]](https://ieeexplore.ieee.org/document/9372832) [[Poster]](https://tensorworkshop.github.io/NeurIPS2021/accepted_papers/poster_4_compresse.pdf)
  
* A. Wang, Q. Zhao, Z. Jin, C. Li, and G. Zhou. Robust tensor decomposition via orientation invariant tubal nuclear norms. Science China Technological Sciences, 2022.
  [[Website]](https://link.springer.com/article/10.1007/s11431-021-1976-2)

* L. Feng, C. Zhu, Z. Long, J. Liu, and Y. Liu. Multiplex transformed tensor decomposition for multidimensional image recovery. IEEE Transactions on Image Processing, 2023.
    [[Website]](https://ieeexplore.ieee.org/document/10153488/) [[Code]](https://github.com/yipengliu/mttd)

* H. Wang, J. Peng, W. Qin, J. Wang, and D. Meng. Guaranteed tensor recovery fused low-rankness and smoothness. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023.
  [[Website]](https://ieeexplore.ieee.org/document/10078018) [[Code]](https://github.com/wanghailin97/Guaranteed-Tensor-Recovery-Fused-Low-rankness-and-Smoothness)

* J.-L. Wang, T.-Z. Huang, X.-L. Zhao, Y.-S. Luo, and T.-X. Jiang. CONOT: Coupled nonlinear transform-based low-rank tensor representation for multidimensional image completion. IEEE Transactions on Neural Networks and Learning Systems, 2024.
  [[Website]](https://ieeexplore.ieee.org/document/9946011)

* D. Qiu, T. Li, and X. Zhang. Hyperspectral image denoising via transformed tensor nuclear norm and nonconvex regularization in spatial-spectral gradient domains. IEEE Transactions on Geoscience and Remote Sensing, 2025.
  [[Website]](https://ieeexplore.ieee.org/document/11262236) 
  

### Higher-Order Extensions

* C. D. Martin, R. Shaffer, and B. Larue. An order-p tensor factorization with applications in imaging. SIAM Journal on Scientific Computing, 2013.
  [[Website]](https://epubs.siam.org/doi/10.1137/110841229)

* W. Qin, H. Wang, F. Zhang, J. Wang, X. Luo, and T. Huang. Low-rank high-order tensor completion with applications in visual data. IEEE Transactions on Image Processing, 2022.
  [[Website]](https://ieeexplore.ieee.org/document/9730793) [[Code]](https://github.com/Qinwenjinswu/TIP-Code)

* Y. Wang and Y. Yang. HOT-SVD: Higher order t-singular value decomposition for tensors based on tensor-tensor product. Computational and Applied Mathematics, 2022. 
  [[Website]](https://link.springer.com/article/10.1007/s40314-022-02107-7)

* S. Liu, X.-L. Zhao, J. Leng, B.-Z. Li, J.-H. Yang, and X. Chen. Revisiting high-order tensor singular value decomposition from basic element perspective. IEEE Transactions on Signal Processing, 2024.
  [[Website]](https://ieeexplore.ieee.org/document/10665981) [[Code]](https://github.com/liu-sheng/code_METNN)

* W. Qin, H. Wang, F. Zhang, W. Ma, J. Wang, and T. Huang. Nonconvex robust high-order tensor completion using randomized low-rank approximation. IEEE Transactions on Image Processing, 2024.
  [[Website]](https://ieeexplore.ieee.org/document/10496551)

### Extensions to Diversified Machine Learning Tasks

* S. Roy and G. Michailidis. Regularized high dimension low tubal-rank tensor regression. Electronic Journal of Statistics, 2022.
  [[Website]](https://projecteuclid.org/journals/electronic-journal-of-statistics/volume-16/issue-1/Regularized-high-dimension-low-tubal-rank-tensor-regression/10.1214/22-EJS2004.pdf#:~:text=In%20this%20work%2C%20we%20leverage%20the%20recently%20developed,tubal%20rank%20tensor%20and%20a%20structured%20sparse%20one.)

* A. Wang, Y. Qiu, Z. Jin, G. Zhou, and Q. Zhao. Low-rank tensor transitions (LoRT) for transferable tensor regression. Proceedings of the 42nd International Conference on Machine Learning, 2025.
  [[Website]](https://openreview.net/forum?id=huu5JErrT1) [[Code]](https://github.com/pingzaiwang/LoRT)

* J. Wu, Z. Lin, and H. Zha. Essential tensor learning for multi-view spectral clustering. IEEE Transactions on Image Processing, 2019.
  [[Website]](https://ieeexplore.ieee.org/document/8736495) [[Code]](https://github.com/sikid/Code-for-ETLMSC)

* L. Zhang and Z. Peng. Infrared small target detection based on partial sum of the tensor nuclear norm. Remote Sensing, 2019.
  [[Website]](https://www.mdpi.com/2072-4292/11/4/382)

* Ke Yan, H. Lv, Y. Guo, Y. Chen, H. Wu, B. Liu, TPpred-ATMV: therapeutic peptide prediction by adaptive multi-view tensor learning model. Bioinformatics, 2022.
  [[Website]](https://academic.oup.com/bioinformatics/article/38/10/2712/6564690?login=false) [[Code]](https://github.com/cokeyk/TPpred-ATMV)

* H. Chen, X. Wang, X. Xiu, W. Liu, Data-Adaptive Transformed Bilateral Tensor Low-Rank Representation for Clustering, arXiv:2510.20077v1, 2025.
  [[Website]](https://arxiv.org/abs/2510.20077v1) [[Code]](https://github.com/xianchaoxiu/TBTLRR)

* M. Ding, J.-H. Yang, X.-L. Zhao, J. Zhang, M. K. Ng, Nonconvex low-rank tensor representation for multi-view subspace clustering with insufficient observed samples, IEEE Transactions on Knowledge and Data Engineering, 37 (2025), p. 3583–3597.
  [[Website]](https://ieeexplore.ieee.org/document/10938849)

* L. Wang, Y. Yuan, X. Luo, Advanced High-Order Graph Convolutional Networks with Assorted Time-Frequency Transforms, IEEE/CAA Journal of Automatica Sinica, vol. 13, no. 2, pp. 394-408, 2026.
  [[Website]](https://ieeexplore.ieee.org/document/11429643)

* T. T. Mai, E. Y. Lam, and C. Lee. Attention-guided low-rank tensor completion. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2024.
  [[Website]](https://ieeexplore.ieee.org/document/10601492) [[Code]](https://github.com/mtntruong/AGTC)

* J. Zheng, A. Tang, Q. Mao, Z. Lin, and Y. Cao. ReFTA: Breaking the weight reconstruction bottleneck in tensorized parameter-efficient fine-tuning. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2026.
  [[Website]](https://cvpr.thecvf.com/virtual/2026/poster/38595) 

## 🚀 Applications & Datasets

We provide scripts and adapted datasets to reproduce the empirical evaluations discussed in the paper across three representative data recovery tasks.

1.  **Multispectral Image Completion**: Recovering partially observed MSI tensors.

* Dataset: CAVE Dataset.

* Description: Comprises 32 multispectral images (MSIs) captured in controlled indoor environments. Each MSI features a spatial resolution of 512×512 pixels across 31 spectral bands, spanning a wavelength range from 400 nm to 700 nm with a spectral interval of 10 nm. All data are rescaled to the interval [0,1] and resize to 256×256×31 for evaluation.

* Original Link: https://cave.cs.columbia.edu/repository/Multispectral

2.  **Slice-Missing Traffic Data Imputation**: Imputing consecutive missing frontal slices in spatiotemporal traffic scenarios.

* Dataset: Guangzhou Urban Traffic Speed Dataset.

* Description: Organized as a tensor of size 214×61×144, corresponding to 214 road segments, 61 days (Aug. 1 - Sep. 30, 2016), and 144 time intervals per day with 10-minute resolution.

* Original Link: https://doi.org/10.5281/zenodo.1205229

   
3.  **Spatially Irregular Spatial Transcriptomics Data Imputation**:
Recovering gene expression levels that suffer from severe missingness during acquisition, an essential step for subsequent biological analysis.

* Dataset: Human dorsolateral prefrontal cortex (DLPFC) spatial transcriptomics dataset.

* Description: Unlike standard tensor completion settings defined on rectangular grids, this data is collected over an irregular biological domain. It is organized as a spatio-irregular tensor of size 74 × 49 × 50. Here, 74 and 49 denote the height and width of the smallest rectangle enclosing the tissue domain, while 50 is the number of frontal slices. The tensor contains 2702 valid mode-3 fibers in total. For evaluation, the nonzero gene expression entries are treated as the reference set, from which 50%, 70%, and 90% entries are uniformly missing as observations.

* Original Link: http://spatial.libd.org/spatialLIBD/

## ⚙️ Getting Started

### Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/benzhengli/Transform-Based-Representation-Zoo/tree/main](https://github.com/benzhengli/Transform-Based-Representation-Zoo/tree/main)

2. Add to Path:
   Open MATLAB and add the repository and its subfolders to your MATLAB path:
   ```matlab
   addpath(genpath('Transform-Based-Tensor-Representation-Zoo'));
   savepath;

3. Quick Start. We provide two demo scripts to help you get started quickly with the representative tasks discussed in the paper:

* **Multispectral Image Recovery**:
  Navigate to `./Applications/MSI_Completion/` and run `demo_msi.m`.

* **Spatial Transcriptomics Imputation**:
  Navigate to `./Applications/Spatial_Irregular/` and run `demo_spatial.m`.

## 📂 Repository Structure

```text
├── Demo_MSI_Completion     # Multispectral image recovery experiments
├── Demo_Spatial_Irregular  # Spatially irregular data recovery
├── Datasets/               # Adapted and pre-processed datasets
├── Methods/                # Implementation of core TNN-based models
│   ├── Linear/             # TNN, DCTTNN, UTNN, DTNN
│   ├── Nonlinear/          # NTTNN
│   ├── GroupTube/          # NTNN
│   ├── Irregular/          # SIR-LRTC
└── Utils/                  # Shared helper functions (PSNR, SSIM calculation, etc.)
```

## 📧 Contact

If you have any questions or suggestions, please feel free to open an issue or contact:

* Ben-Zheng Li (李本正): mathlibz@ccnu.edu.cn

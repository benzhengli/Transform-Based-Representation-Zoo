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
  [[PDF]]([https://doi.org/10.1016/j.laa.2010.10.011](https://www.sciencedirect.com/science/article/pii/S0024379510004830))

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

* A. Wang, Y. Qiu, M. Bai, Z. Jin, G. Zhou, and Q. Zhao. Generalized tensor decomposition for understanding multi-output regression under combinatorial shifts. Advances in Neural Information Processing Systems, 2024.

* A. Wang, Y. Qiu, H. Huang, Z. Jin, G. Zhou, and Q. Zhao. Towards a geometric understanding of tensor learning via the t-product. Advances in Neural Information Processing Systems, 2025.

* C. Wang, X.-L. Zhao, Y.-B. Zheng, B.-Z. Li, and M. K. Ng. Functional tensor singular value decomposition. SIAM Journal on Scientific Computing, 2025.

* J. Wang and X.-L. Zhao, Functional transform-based low-rank tensor factorization for multi-dimensional data recovery, in Computer Vision – ECCV, 2024.

* T. Yang, W. Wu, and T. Huang, Hincot: Hierarchical nonlinear continuous transform-based tensor representation for multi-dimensional data recovery, in Proceedings of the AAAI Conference on Artificial Intelligence, vol. 40, 2026, pp. 27621–27629.

* Y. Zeng, X.-L. Zhao, W.-H. Wu, T.-Y. Ji, and C. Wang, Gaussian splatting-based low-rank tensor representation for multi-dimensional image recovery, CVPR,2026.

* R. Su, X.-L. Zhao, S. Liu, W.-H. Wu, Y. Luo, and M. K. Ng, Neural operator-grounded continuous tensor function representation and its applications, arXiv preprint arXiv:2603.01812, 2026.

### Spatially Irregular Transform-Based Tensor Representation

* H. Zhang, T.-Z. Huang, X.-L. Zhao, S. Zhang, J.-Y. Xie, T.-X. Jiang, and M. K. Ng. Learnable transform-assisted tensor decomposition for spatio-irregular multidimensional data recovery. ACM Trans. Knowl. Discov. Data, 2024.

## 📖 Transformed Low-Rank Characterization

* P. Zhou, C. Lu, Z. Lin, and C. Zhang. Tensor factorization for low-rank tensor completion. IEEE Transactions on Image Processing, 2018.
  
* F. Wu, Y. Li, C. Li, and Y. Wu. A fast tensor completion method based on tensor qr decomposition and tensor nuclear norm minimization. IEEE Transactions on Computational Imaging, 2021.
  
* Y. Zheng and A.-B. Xu. Tensor completion via tensor qr decomposition and l2,1-norm minimization. Signal Processing, 2021.
  
* J.-Y. Li, J.-Y. Xie, Y.-S. Luo, X.-L. Zhao, and J.-L. Wang. H2tf for hyperspectral image denoising: Where hierarchical nonlinear transform meets hierarchical matrix factorization. IEEE Geoscience and Remote Sensing Letters, 2023.

* T.-W. Zhou, X.-L. Zhao, J.-L. Wang, Y.-S. Luo, M. Wang, and X.-X. Bai. Dtr: A unified deep tensor representation framework for multimedia data recovery. IEEE Transactions on Multimedia, 2025. 


### Multi-Directional Extensions

* D. Wei, A. Wang, X. Feng, B. Wang, and B. Wang. Tensor completion based on triple tubal nuclear norm. Algorithms, 2018.

* Y.-B. Zheng, T.-Z. Huang, X.-L. Zhao, T.-X. Jiang, T.-Y. Ji, and T.-H. Ma. Tensor n-tubal rank and its convex relaxation for low-rank tensor recovery. Information Sciences, 2020.

* J.-L. Wang, T.-Z. Huang, X.-L. Zhao, T.-X. Jiang, and M. K. Ng. Multi-dimensional visual data completion via low-rank tensor representation under coupled transform. IEEE Transactions on Image Processing, 2021.
  
* A. Wang, Q. Zhao, Z. Jin, C. Li, and G. Zhou. Robust tensor decomposition via orientation invariant tubal nuclear norms. Science China Technological Sciences, 2022.

* L. Feng, C. Zhu, Z. Long, J. Liu, and Y. Liu. Multiplex transformed tensor decomposition for multidimensional image recovery. IEEE Transactions on Image Processing, 2023.

* H. Wang, J. Peng, W. Qin, J. Wang, and D. Meng. Guaranteed tensor recovery fused low-rankness and smoothness. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023.

* J.-L. Wang, T.-Z. Huang, X.-L. Zhao, Y.-S. Luo, and T.-X. Jiang. Conot: Coupled nonlinear transform-based low-rank tensor representation for multidimensional image completion. IEEE Transactions on Neural Networks and Learning Systems, 2024.

* D. Qiu, T. Li, and X. Zhang. Hyperspectral image denoising via transformed tensor nuclear norm and nonconvex regularization in spatial-spectral gradient domains. IEEE Transactions on Geoscience and Remote Sensing, 2025.
  
* Z.-W. Shi, Y.-B. Zheng, Y. Zhang, and H.-C. Li. Multidimensional nonlinear transform-based tensor representation for high-dimensional image reconstruction. Pattern Recognition, 2025.

### Higher-Order Extensions

* C. D. Martin, R. Shaffer, and B. Larue. An order-p tensor factorization with applications in imaging. SIAM Journal on Scientific Computing, 2013. 

* Y.-B. Zheng, T.-Z. Huang, X.-L. Zhao, T.-X. Jiang, T.-Y. Ji, and T.-H. Ma. Tensor n-tubal rank and its convex relaxation for low-rank tensor recovery. Information Sciences, 2020.

* W. Qin, H. Wang, F. Zhang, J. Wang, X. Luo, and T. Huang. Low-rank high-order tensor completion with applications in visual data. IEEE Transactions on Image Processing, 2022. 

* Y. Wang and Y. Yang. Hot-svd: Higher order t-singular value decomposition for tensors based on tensor-tensor product. Computational and Applied Mathematics, 2022. 

* S. Liu, X.-L. Zhao, J. Leng, B.-Z. Li, J.-H. Yang, and X. Chen. Revisiting high-order tensor singular value decomposition from basic element perspective. IEEE Transactions on Signal Processing, 2024. 

* W. Qin, H. Wang, F. Zhang, W. Ma, J. Wang, and T. Huang. Nonconvex robust high-order tensor completion using randomized low-rank approximation. IEEE Transactions on Image Processing, 2024.

### Extensions to Diversified Machine Learning Tasks

* S. Roy and G. Michailidis. Regularized high dimension low tubal-rank tensor regression. Electronic Journal of Statistics, 2022.

* A. Wang, Y. Qiu, Z. Jin, G. Zhou, and Q. Zhao. Low-rank tensor transitions (lort) for transferable tensor regression. Proceedings of the 42nd International Conference on Machine Learning, 2025.

* J. Wu, Z. Lin, and H. Zha. Essential tensor learning for multi-view spectral clustering. IEEE Transactions on Image Processing, 2019.

* L. Zhang and Z. Peng. Infrared small target detection based on partial sum of the tensor nuclear norm. Remote Sensing, 2019.

* B.-Y. Jing, T. Li, Z. Lyu, and D. Xia. Community detection on mixture multilayer networks via regularized tensor decomposition. The Annals of Statistics, 2021.

* K. Yan et al. Tppred-atmv: therapeutic peptide prediction by adaptive multi-view tensor learning model. Bioinformatics, 2022.

* T. T. Mai, E. Y. Lam, and C. Lee. Attention-guided low-rank tensor completion. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2024.

* J. Zheng, A. Tang, Q. Mao, Z. Lin, and Y. Cao. Refta: Breaking the weight reconstruction bottleneck in tensorized parameter-efficient fine-tuning. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2026.

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

   
3.  **Spatially Irregular Spatial Transcriptomics Data Imputation**: Recovering gene expression levels on tissue spots distributed over irregular biological domains.

* Dataset: Human Heart Tissue Spatial Transcriptomics Dataset.

* Description: Organized as a spatio-irregular tensor of size 22×16×250, where 22 and 16 denote the height and width of the smallest rectangle enclosing the tissue domain, and 250 is the number of frontal slices (genes). The tensor contains 210 valid mode-3 fibers in total corresponding to the irregular tissue spots.

* Link: Available within our provided repository code.

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
├── Applications/           # Scripts for specific recovery tasks
│   ├── MSI_Completion/     # Multispectral image recovery experiments
│   ├── Traffic_Imputation/ # Traffic data slice-missing recovery
│   └── Spatial_Irregular/  # Spatially irregular data recovery
├── Datasets/               # Adapted and pre-processed datasets
├── Methods/                # Implementation of core TNN-based models
│   ├── Linear/             # TNN, DCTTNN, UTNN, DTNN
│   ├── Nonlinear/          # NTTNN, S2NTNN
│   ├── GroupTube/          # GTNN, NTNN
│   └── Functional/         # FunTNN
└── Utils/                  # Shared helper functions (PSNR, SSIM calculation, etc.)
```

## 📧 Contact

If you have any questions, please feel free to open an issue or contact:

* Ben-Zheng Li (李本正): mathlibz@ccnu.edu.cn

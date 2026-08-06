---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html

---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an Assistant Researcher in the College of Science at the National University of Defense Technology. My research focuses on nonsmooth optimization, manifold optimization, decentralized optimization, and second-order algorithms. If you are interested in academic collaboration, please feel free to contact me at **freedeng1208@gmail.com**.

I received my bachelor's degree from Fujian Normal University and my Ph.D. from the Research Center for Discrete Mathematics (离散数学研究中心), Fuzhou University, under the supervision of [Zheng Peng (彭拯)](http://www.pzhengxtu.com/). I then conducted postdoctoral research at the Beijing International Center for Mathematical Research (BICMR，北京国际数学研究中心), Peking University, under the supervision of [Zaiwen Wen (文再文)](http://faculty.bicmr.pku.edu.cn/~wenzw/index.html).

# 📖 Research Experience & Education

- *2023.04–present*, Assistant Researcher, College of Science, National University of Defense Technology, Changsha.
- *2020.09–2023.04*, Postdoctoral Researcher, Beijing International Center for Mathematical Research, Peking University, Beijing.
- *2015.06–2020.06*, Ph.D., Research Center for Discrete Mathematics, Fuzhou University, Fuzhou.
- *2011.09–2015.06*, B.Sc., School of Mathematics and Computer Science, Fujian Normal University, Fuzhou.

# 🔥 News

- *2026.02*: One paper was accepted by **Applied Mathematical Modelling**.
- *2026.01*: One paper was accepted by **IMA Journal of Numerical Analysis**.
- *2025.12*: One paper was accepted by **Applied Numerical Mathematics**.
- *2025.09*: One paper was accepted by **SIAM Review**.
- *2025.09*: Two papers were accepted by **NeurIPS 2025**.
- *2025.09*: One paper was accepted by **Journal of Optimization Theory and Applications**.
- *2025.09*: One paper was accepted by **Numerische Mathematik**.
- *2025.08*: One paper was accepted by **Mathematics of Operations Research**.
- *2025.07*: One paper was accepted by **Journal of Applied Analysis and Computation**.
- *2025.05*: One paper was accepted by **Journal of Scientific Computing**.
- *2025.02*: One paper was accepted by **IEEE Transactions on Automatic Control**.
- *2025.02*: One paper was accepted by **Journal of the Operations Research Society of China**.

# 📝 Preprints

- [A Single-loop Stochastic Riemannian ADMM for Nonsmooth Optimization](https://arxiv.org/abs/2512.22750), Jiachen Jin, Kangkang Deng, Hongxia Wang, 2025.
- [Single-loop $\mathcal{O}(\epsilon^{-3})$ Stochastic Smoothing Algorithms for Nonsmooth Riemannian Optimization](https://arxiv.org/abs/2505.09485), Kangkang Deng, Zheng Peng, Weihe Wu, 2025.
- [An Efficient Primal-Dual Semismooth Newton Method for Semidefinite Programming](https://arxiv.org/abs/2504.14333), Zhanwang Deng, Jiang Hu, Kangkang Deng, Zaiwen Wen, 2025.
- [Stochastic Momentum ADMM for Nonconvex and Nonsmooth Optimization with Application to PnP Algorithm](https://arxiv.org/abs/2504.08223), Kangkang Deng, Shuchang Zhang, Boyu Wang, Jiachen Jin, Juan Zhou, Hongxia Wang, 2025.
- [Improving the Communication in Decentralized Manifold Optimization through Single-Step Consensus and Compression](https://arxiv.org/abs/2407.08904), Jiang Hu, Kangkang Deng, 2024.

# 📝 Publications

- [The Augmented Lagrangian Methods: Overview and Recent Advances](https://doi.org/10.1137/24M1706153), Kangkang Deng, Rui Wang, Zhenyuan Zhu, Junyu Zhang, Zaiwen Wen, **SIAM Review**, 2026.
- [SAM-DNN: Bilevel Convergent Sequential Averaging Methods with Denoising Neural Network](https://www.sciencedirect.com/science/article/abs/pii/S0307904X26000788), Shuchang Zhang, Kangkang Deng, Hui Zhang, Hongxia Wang, **Applied Mathematical Modelling**, 2026.
- [Stochastic ADMM with Batch Size Adaptation for Nonconvex Nonsmooth Optimization](https://doi.org/10.1016/j.apnum.2025.12.007), Jiachen Jin, Kangkang Deng, Boyu Wang, Hongxia Wang, **Applied Numerical Mathematics**, 2026.
- [A Cut-and-Project Perspective for Linearized Bregman Iterations](https://doi.org/10.1093/imanum/drag022), Yu-Hong Dai, Kangkang Deng, Hui Zhang, **IMA Journal of Numerical Analysis**, 2026.
- [A Novel Riemannian Conjugate Gradient Method with Iteration Complexity Guarantees](https://doi.org/10.11948/20240564), Juan Zhou, Kangkang Deng, Hongxia Wang, Zheng Peng, **Journal of Applied Analysis and Computation**, 2026.
- [Anderson Acceleration of Derivative-Free Projection Methods for Constrained Monotone Nonlinear Equations](https://doi.org/10.1007/s10957-025-02841-y), Jiachen Jin, Hongxia Wang, Kangkang Deng, **Journal of Optimization Theory and Applications**, 2026.
- [Rethinking Gradient Step Denoiser: Towards Truly Pseudo-Contractive Operator](https://openreview.net/forum?id=J5XXBS6wPz), Shuchang Zhang, Yaoyun Zeng, Kangkang Deng, Hongxia Wang, **NeurIPS 2025**, 2025.
- [Adaptive Riemannian ADMM for Nonsmooth Optimization: Optimal Complexity without Smoothing](https://openreview.net/forum?id=lni933mlvF), Kangkang Deng, Jiachen Jin, Jiang Hu, Hongxia Wang, **NeurIPS 2025**, 2025. [Code](https://github.com/KKDeng/Adaptive-Riemannian-ADMM)
- [Decentralized Projected Riemannian Gradient Method for Smooth Optimization on Compact Submanifolds Embedded in the Euclidean Space](https://doi.org/10.1007/s00211-025-01497-0), Kangkang Deng, Jiang Hu, **Numerische Mathematik**, 2025.
- [Oracle Complexities of Augmented Lagrangian Methods for Nonsmooth Manifold Optimization](https://doi.org/10.1287/moor.2024.0498), Kangkang Deng, Jiang Hu, Jiayuan Wu, Zaiwen Wen, **Mathematics of Operations Research**, 2025. [Code](https://github.com/KKDeng/ManIAL)
- [Inexact Riemannian Gradient Descent Method for Nonconvex Optimization with Strong Convergence](https://doi.org/10.1007/s10915-025-02913-1), Juan Zhou, Kangkang Deng*, Hongxia Wang, Zheng Peng, **Journal of Scientific Computing**, 2025.
- [Decentralized Riemannian Natural Gradient Methods with Kronecker Product Approximations](https://doi.org/10.1007/s40305-025-00583-2), Jiang Hu, Kangkang Deng*, Quanzheng Li, **Journal of the Operations Research Society of China**, 2025.
- [Decentralized Projected Riemannian Stochastic Recursive Momentum Method for Nonconvex Optimization](https://doi.org/10.1609/aaai.v39i11.33218), Kangkang Deng, Jiang Hu, **AAAI 2025**, 2025.
- [LDPP-MIG Detectors in Sample-Starved Nonhomogeneous Clutter](https://doi.org/10.1109/TAES.2025.3548007), Xiaoqiang Hua, Chuanfu Xu, Zhenghua Wang, Weijian Liu, Kangkang Deng, Alfonso Farina, Danilo Orlando, **IEEE Transactions on Aerospace and Electronic Systems**, 2025.
- [An Augmented Lagrangian Primal-Dual Semismooth Newton Method for Multi-Block Composite Optimization](https://doi.org/10.1007/s10915-025-02794-4), Zhanwang Deng, Kangkang Deng, Jiang Hu, Zaiwen Wen, **Journal of Scientific Computing**, 2025. [Code](https://github.com/optsuite/SSNCVX)
- [Achieving Local Consensus over Compact Submanifolds](https://doi.org/10.1109/TAC.2025.3545711), Jiang Hu, Jiaojiao Zhang, Kangkang Deng*, **IEEE Transactions on Automatic Control**, 2025.
- [New Vector Transport Operators Extending a Riemannian CG Algorithm to Generalized Stiefel Manifold with Low-Rank Applications](https://doi.org/10.1016/j.cam.2024.116070), Xuejie Wang, Kangkang Deng*, Zheng Peng, Chengcheng Yan, **Journal of Computational and Applied Mathematics**, 2024.
- [Decentralized Douglas-Rachford Splitting Methods for Smooth Optimization over Compact Submanifolds](https://arxiv.org/abs/2311.16399), Kangkang Deng, Jiang Hu, Hongxia Wang, **Journal of Computational Mathematics**, 2024.
- [Trace Lasso Regularization for Adaptive Sparse Canonical Correlation Analysis via Manifold Optimization Approach](https://doi.org/10.1007/s40305-022-00449-x), Kangkang Deng, Zheng Peng, **Journal of the Operations Research Society of China**, 2024. [Code](https://github.com/KKDeng/ASCCA)
- [A Projected Semismooth Newton Method for a Class of Nonconvex Composite Programs with Strong Prox-Regularity](https://www.jmlr.org/papers/v25/23-0371.html), Jiang Hu, Kangkang Deng*, Jiayuan Wu, Quanzheng Li, **Journal of Machine Learning Research**, 2024. [Code](https://github.com/KKDeng/Prox-Regular-SSN)
- [Riemannian Smoothing Gradient Type Algorithms for Nonsmooth Optimization Problems on Compact Riemannian Submanifolds Embedded in Euclidean Space](https://doi.org/10.1007/s00245-023-10061-x), Zheng Peng, Weihe Wu, Jiang Hu, Kangkang Deng*, **Applied Mathematics & Optimization**, 2023.
- [High-Performance Placement Engine for Modern Large-Scale FPGAs with Heterogeneity and Clock Constraints](https://doi.org/10.1109/TCAD.2023.3328209), Ziran Zhu, Yangjie Mei, Kangkang Deng, Huan He, Jianli Chen, Jun Yang, Yao-Wen Chang, **IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems**, 2023.
- [An Entropy-Regularized ADMM for Binary Quadratic Programming](https://doi.org/10.1007/s10898-022-01144-0), Haoming Liu, Kangkang Deng, Haoyang Liu, Zaiwen Wen, **Journal of Global Optimization**, 2023.
- [A Decomposition Augmented Lagrangian Method for Low-Rank Semidefinite Programming](https://doi.org/10.1137/22M1474539), Yifei Wang, Kangkang Deng, Haoyang Liu, Zaiwen Wen, **SIAM Journal on Optimization**, 2023. [Code](https://github.com/optsuite/SDPDAL)
- [A Manifold Inexact Augmented Lagrangian Method for Nonsmooth Optimization on Riemannian Submanifolds in Euclidean Space](https://doi.org/10.1093/imanum/drac018), Kangkang Deng, Zheng Peng, **IMA Journal of Numerical Analysis**, 2023. [Code](https://github.com/KKDeng/mialm_code_share)
- [A Discriminative Projection and Representation-Based Classification Framework for Face Recognition](https://doi.org/10.1137/19M1253873), Kangkang Deng, Zheng Peng, Wenxing Zhu, **SIAM Journal on Imaging Sciences**, 2020. [Code](https://github.com/KKDeng/DPRC_code)

\* Corresponding author.

# 🎖 Honors and Service

- *2025.12*, First Prize, Young Outstanding Paper Award, Hunan Society for Computational Mathematics and Applied Software (湖南省计算数学应用软件学会青年优秀论文一等奖).
- *2025.11*, Young Council Member, Mathematics and Intelligence Branch of the Operations Research Society of China (中国运筹学会数学与智能分会青年理事).
- *2025.08*, Young Talent Support, Hunan Furong Program (湖南省芙蓉计划青年托举).
- *2025.04*, Council Member, Operations Research Society of Hunan (湖南省运筹学会理事).

# 💬 Invited Talks

- *2025.08*, “Iteration Complexity of Riemannian ADMM,” The First Youth Scholars Conference of the Operations Research Society of China, Taiyuan.
- *2025.05*, “Nonsmooth Optimization on Riemannian Manifolds,” Annual Meeting of the Mathematical Programming Branch of the Operations Research Society of China, Shanghai.

<small>Last updated: August 2026.</small>

<div align="center">

# Yongchun Jiang

**GPU Systems · High-Performance Computing · AI Infrastructure**

M.Eng. student at the Institute of Software, Chinese Academy of Sciences  
University of Chinese Academy of Sciences

[![Email](https://img.shields.io/badge/Email-jiangyongchun24%40mails.ucas.ac.cn-5a9f00?style=flat-square)](mailto:jiangyongchun24@mails.ucas.ac.cn)
[![GitHub](https://img.shields.io/badge/GitHub-yongqiu--star-181717?style=flat-square&logo=github)](https://github.com/yongqiu-star)

</div>

I work on GPU training systems and high-performance graph learning. My research
focuses on finding the real execution bottleneck, designing a mechanism around
it, and validating the result with performance, correctness, and reproducibility
evidence.

My current interests include:

- GPU systems and CUDA performance engineering;
- low-precision numerical execution for iterative solvers;
- temporal graph learning and training systems; and
- reproducible systems research across modern GPU architectures.

## Selected Systems and Artifacts

| Project | What it does | Evidence |
| --- | --- | --- |
| **[ATLAS](https://github.com/yongqiu-star/ATLAS)** | Asynchronous state-aware training runtime for temporal graph neural networks | **ICPP 2026**; 5.55x geometric-mean and 11.60x peak speedup on RTX PRO 6000 |
| **[Coherent SVM](https://github.com/yongqiu-star/coherent-svm)** | Coherent low-precision execution for nonlinear RBF-SVM training | 1.351x over a matched FP32 control on EMBER-65K with nearly unchanged held-out accuracy |
| **[ATNSF](https://github.com/yongqiu-star/ATNSF)** | Parallel pairwise negative sampling for temporal link prediction | **IJCAI-ECAI 2026**; average AP improved from 0.724 to 0.827, with 2.57x geometric-mean training speedup |
| **[BTC-TC](https://github.com/fanna1234/btc-tc-artifact)** | Exact GPU triangle counting with hybrid Bit Tensor Cores and CUDA Cores | **SC 2026**; exact on 36 graphs, with 1.92x kernel and 8.0x end-to-end geometric-mean speedup |

## Publications

- **Yongchun Jiang**, Yongchao Liu, Kaifan Jia, and Heng Zhang.  
  **[ATLAS: Enabling an Asynchronous State-Aware Pipeline for Efficient Training of Temporal Graph Neural Networks](https://doi.org/10.1145/3832810.3832844).**  
  *55th International Conference on Parallel Processing (ICPP)*, 2026.

- **Yongchun Jiang**, Heng Zhang, Jian Gao, and Xin Zheng.  
  **[History Doesn't Repeat, but Its Patterns Echo: A Parallel Pairwise Negative-Sampling Framework for Temporal Link Prediction](https://github.com/yongqiu-star/ATNSF).**  
  *35th International Joint Conference on Artificial Intelligence (IJCAI-ECAI)*, 2026.

- Kaifan Jia, **Yongchun Jiang**, Zhihao Ling, Minghui Zhang, Xuran Wang, Ran Bao, Haonan Zou, and Heng Zhang.  
  **[BTC-TC: Exact GPU Triangle Counting with Hybrid Bit Tensor Cores and CUDA Cores](https://github.com/fanna1234/btc-tc-artifact).**  
  *International Conference for High Performance Computing, Networking, Storage, and Analysis (SC)*, 2026.

- Chengying Huan, Heng Zhang, Yongchao Liu, Likang Chen, Xuran Wang, **Yongchun Jiang**, Shaonan Ma, and Yanjun Wu.  
  **[TeMatch: A Fast Temporal Subgraph Matching Framework with Temporal-Aware Subgraph Matching Algorithms](https://doi.org/10.1109/ICDE65448.2025.00082).**  
  *41st IEEE International Conference on Data Engineering (ICDE)*, 2025.

## Toolbox

`CUDA C++` · `C/C++` · `Python` · `PyTorch` · `PyTorch Geometric` ·
`Nsight Systems` · `Nsight Compute` · `CUDA Graphs` · `Linux` · `Git`

## Contact

I am open to research collaborations and opportunities in GPU systems,
high-performance computing, and AI infrastructure.

- Email: [jiangyongchun24@mails.ucas.ac.cn](mailto:jiangyongchun24@mails.ucas.ac.cn)


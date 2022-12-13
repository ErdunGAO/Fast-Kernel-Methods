# Fast-Kernel-Methods

This repo is a collection of AWESOME things about kernel-based methods, mainly focusing on the recent developments on fast kernel methods, and including papers, codes, etc. Feel free to fork.

![](https://img.shields.io/badge/Resources-@CLeaR_Unimelb-red.svg) ![](https://img.shields.io/badge/License-@MIT-green.svg)

&#x1F60D; Recommend！

## Kernel Approximation
### Data independent (random feature)
- Quadrature-based features for kernel approximation. [[neurips18]](https://papers.nips.cc/paper/2018/file/6e923226e43cd6fac7cfe1e13ad000ac-Paper.pdf) [[codes]](https://github.com/maremun/quffka)
- GPyTorch: Blackbox Matrix-Matrix Gaussian Process Inference with GPU Acceleration. [[neurips18]](https://papers.nips.cc/paper/2018/file/27e8e17134dd7083b050476733207ea1-Paper.pdf) [[codes]](https://gpytorch.ai)
- Fourier Sparse Leverage Scores and Approximate Kernel Learning. [[neurips20]](https://papers.nips.cc/paper/2020/file/012d9fe15b2493f21902cd55603382ec-Paper.pdf) [[codes (matlab)]](https://github.com/cpmusco/leverage_score_rff)
- The Fast Kernel Transform. [[aistats22]](https://proceedings.mlr.press/v151/ryan22a/ryan22a.pdf) [[codes (julia)]](https://github.com/jpryan1/FastKernelTransform.jl)
- Linear Time Kernel Matrix Approximation via Hyperspherical Harmonics. [[arxiv22]](https://arxiv.org/pdf/2202.03655.pdf) [[codes (julia)]](https://github.com/jpryan1/HarmonicDecompFact.jl)
- (**Binary-Tree Kernel**) Log-Linear-Time Gaussian Processes Using Binary Tree Kernels. [[neurips22]](https://openreview.net/pdf?id=VB_mBqL4VW-)[[codes]](https://github.com/mkc1000/btgp)

### Data dependent (nystrom method)
- On the Nystrom Method for Approximating a Gram Matrix for Improved Kernel-Based Learning. [[JMLR05]](https://www.jmlr.org/papers/volume6/drineas05a/drineas05a.pdf)
- Large-Scale Data-Dependent Kernel Approximation. [[aistats17]](http://proceedings.mlr.press/v54/ionescu17a/ionescu17a.pdf)

## Kernel-based independence test
### Theory 
- Kernel Measures of Conditional Dependence. [[neurips07]](https://papers.nips.cc/paper/2007/file/3a0772443a0739141292a5429b952fe6-Paper.pdf)
- (KCI) Kernel-based Conditional Independence Test and Application in Causal Discovery. [[uai12]](https://arxiv.org/pdf/1202.3775.pdf) [[codes]](https://github.com/cmu-phil/causal-learn/blob/main/causallearn/utils/KCI/KCI.py)
- Approximate Kernel-based Conditional Independence Tests for Fast Non-Parametric Causal Discovery. [[JCI19]](https://arxiv.org/pdf/1702.03877.pdf)
- Kernel-Based Hypothesis Tests: Large-Scale Approximations and Bayesian Perspectives. [[Phd thesis]](https://ora.ox.ac.uk/objects/uuid:5e6c96eb-7924-45e6-8060-7de58e643f67/download_file?file_format=application%2Fpdf&safe_filename=Qinyi_s_thesis_final_final.pdf&type_of_work=Thesis)[[codes]](https://github.com/oxcsml/kerpy)
- An Asymptotic Test for Conditional Independence using Analytic Kernel Embeddings. [[icml22]](https://proceedings.mlr.press/v162/scetbon22a/scetbon22a.pdf)[[codes]](https://github.com/meyerscetbon/lp-ci-test)

## Continuous Kernel learning
- Incremental kernel PCA and the Nystrom method. [[paper]](https://arxiv.org/pdf/1802.00043.pdf)
- Incremental Randomized Sketching for Online Kernel Learning. [[icml22]](http://proceedings.mlr.press/v97/zhang19h/zhang19h.pdf)


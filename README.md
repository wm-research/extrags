<div align="center">
<h3>ExtraGS: Geometric-Aware Trajectory Extrapolation with Uncertainty-Guided Generative Priors</h3>

Kaiyuan Tan<sup>1,2</sup>, Yingying Shen<sup>2</sup>, Haohui Zhu<sup>2</sup>, Zhiwei Zhan<sup>2</sup>, Shan Zhao<sup>2</sup>, Mingfei Tu<sup>2</sup>, Hongcheng Luo<sup>2</sup>, Haiyang Sun<sup>2†</sup>, Bing Wang<sup>2✉</sup>, Guang Chen<sup>2</sup>, Hangjun Ye<sup>2</sup>

<sup>1</sup>UIUC
<sup>2</sup>Xiaomi EV  

(†) Project leader. (✉) Corresponding author.  

<a href="https://arxiv.org/abs/2508.15529"><img src='https://img.shields.io/badge/arXiv-ExtraGS-red' alt='Paper PDF'></a>
<a href="https://wm-research.github.io/extrags/"><img src='https://img.shields.io/badge/Project_Page-ExtraGS-green' alt='Project Page'></a>
</div>


<!-- ## Introduction -->
## Abstract
Synthesizing extrapolated views from recorded driving logs is critical for simulating driving scenes for autonomous driving vehicles, yet it remains a challenging task. Recent methods leverage generative priors as pseudo ground truth, but often lead to poor geometric consistency and over-smoothed renderings. To address these limitations, we propose ExtraGS, a holistic framework for trajectory extrapolation that integrates both geometric and generative priors. At the core of ExtraGS is a novel Road Surface Gaussian(RSG) representation based on a hybrid Gaussian-Signed Distance Function (SDF) design, and Far Field Gaussians (FFG) that use learnable scaling factors to efficiently handle distant objects. Furthermore, we develop a self-supervised uncertainty estimation framework based on spherical harmonics that enables selective integration of generative priors only where extrapolation artifacts occur. Extensive experiments on multiple datasets, diverse multi-camera setups, and various generative priors demonstrate that ExtraGS significantly enhances the realism and geometric consistency of extrapolated views, while preserving high fidelity along the original trajectory.
         

## Overview
<div align="center">
<img src="static/images/pipeline_new_v2.png" width="1000">
</div>

<!-- ## News


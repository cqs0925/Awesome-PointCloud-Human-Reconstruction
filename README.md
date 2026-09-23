# Awesome Point Cloud Human Reconstruction

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/cqs0925/Awesome-PointCloud-Human-Reconstruction)](https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/stargazers)
[![Forks](https://img.shields.io/github/forks/cqs0925/Awesome-PointCloud-Human-Reconstruction)](https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/forks)
[![Issues](https://img.shields.io/github/issues/cqs0925/Awesome-PointCloud-Human-Reconstruction)](https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/issues)
[![License: MIT](https://img.shields.io/github/license/cqs0925/Awesome-PointCloud-Human-Reconstruction)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/cqs0925/Awesome-PointCloud-Human-Reconstruction)](https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/commits/main)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/pulls)

A curated list of methods that recover human pose, shape, mesh, and registration from point clouds, including LiDAR, depth, and mmWave.

A few related general 3D point-cloud works are included as well.

> **Note.** "Point Clouds, scattered collections of points in 2D or 3D, are arguably the simplest shape representation, and the raw output of most 3D data acquisition device (depth, mmWave, Lidar... )." — DGCNN

## Overview

- [2026](#2026) — [ICLR](#2026-iclr) · [CVPR](#2026-cvpr) · [ECCV](#2026-eccv) · [SIGGRAPH Asia](#2026-siggraph-asia) · [Journal papers](#2026-journal-papers)
- [2025](#2025) — [WACV](#2025-wacv) · [ICLR](#2025-iclr) · [CVPR](#2025-cvpr) · [ICCV](#2025-iccv) · [MM](#2025-mm) · [BMVC](#2025-bmvc)
- [2024](#2024) — [CVPR](#2024-cvpr) · [ECCV](#2024-eccv)
- [2023](#2023) — [CVPR](#2023-cvpr) · [ICCV](#2023-iccv)
- [2022](#2022) — [CVPR](#2022-cvpr) · [ECCV](#2022-eccv)
- [2021](#2021) — [CVPR](#2021-cvpr) · [MM](#2021-mm) · [arXiv papers](#2021-arxiv-papers)
- [2020](#2020) — [CVPR](#2020-cvpr) · [ECCV](#2020-eccv) · [NeurIPS](#2020-neurips)
- [2019](#2019) — [ICRA](#2019-icra) · [CVPR](#2019-cvpr) · [ICCV](#2019-iccv) · [Journal papers](#2019-journal-papers)

**Links:** `[Paper]` official PDF / proceedings · `[arXiv]` preprint · `[Project]` project page · `[Code]` source · `[DOI]` publisher DOI · `[OpenReview]` venue forum

## Papers

Years are newest first. Within a year, venues follow conference chronology, and journal papers come last.

## 2026

<a id="2026-iclr"></a>
### ICLR

- **Human3R**: Everyone Everywhere All at Once [arXiv](https://arxiv.org/abs/2510.06219) [Project](https://fanegg.github.io/Human3R/) [Code](https://github.com/fanegg/Human3R) [OpenReview](https://openreview.net/forum?id=y7duXr0JXF)

<a id="2026-cvpr"></a>
### CVPR

- **M4Human**: A Large-Scale Multimodal mmWave Radar Benchmark for Human Mesh Reconstruction [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Fan_M4Human_A_Large-Scale_Multimodal_mmWave_Radar_Benchmark_for_Human_Mesh_CVPR_2026_paper.html) [arXiv](https://arxiv.org/abs/2512.12378) [Project](https://fanjunqiao.github.io/M4Human-site/) [Code](https://github.com/FanJunqiao/M4Human)
- **UniSH**: Unifying Scene and Human Reconstruction in a Feed-Forward Pass [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Li_UniSH_Unifying_Scene_and_Human_Reconstruction_in_a_Feed-Forward_Pass_CVPR_2026_paper.html) [Project](https://murphylmf.github.io/UniSH/)

<a id="2026-eccv"></a>
### ECCV

- **ETCH-X**: Robustify Expressive Body Fitting to Clothed Humans with Composable Datasets [arXiv](https://arxiv.org/abs/2604.08548) [Project](https://xiaobenli00.github.io/ETCH-X) [Code](https://github.com/XiaobenLi00/ETCH-X)
- **OmniFit**: Multi-modal 3D Body Fitting via Scale-agnostic Dense Landmark Prediction [arXiv](https://arxiv.org/abs/2604.21575) [Project](https://zcai0612.github.io/OmniFit/) [Code](https://github.com/zcai0612/OmniFit) [DOI](https://doi.org/10.1007/978-3-032-36969-7_24)

<a id="2026-siggraph-asia"></a>
### SIGGRAPH Asia

- **DirtyMoCap**: Robust Motion Capture from Unconstrained Markers [arXiv](https://arxiv.org/abs/2609.19927) [Project](https://wanglongzju.github.io/DirtyMoCap-Project-Page) [Code](https://github.com/WangLongZJU/DirtyMoCap)

<a id="2026-journal-papers"></a>
### Journal papers

- **PointHPS**: Cascaded 3D Human Pose and Shape Estimation from Point Clouds — IJCV 2026 [arXiv](https://arxiv.org/abs/2308.14492) [Project](http://caizhongang.com/projects/PointHPS/) [Code](https://github.com/MotrixLab/PointHPS) [DOI](https://doi.org/10.1007/s11263-026-02750-1)

## 2025

<a id="2025-wacv"></a>
### WACV

- **PocoLoco**: A Point Cloud Diffusion Model of Human Shape in Loose Clothing [Paper](https://openaccess.thecvf.com/content/WACV2025/html/Seth_PocoLoco_A_Point_Cloud_Diffusion_Model_of_Human_Shape_in_WACV_2025_paper.html)

<a id="2025-iclr"></a>
### ICLR

- **OAR**: Occlusion-aware Non-Rigid Point Cloud Registration via Unsupervised Neural Deformation Correntropy [arXiv](https://arxiv.org/abs/2502.10704) [Code](https://github.com/zikai1/OAReg)

<a id="2025-cvpr"></a>
### CVPR

- **Mamba4D**: Efficient 4D Point Cloud Video Understanding with Disentangled Spatial-Temporal State Space Models [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Mamba4D_Efficient_4D_Point_Cloud_Video_Understanding_with_Disentangled_Spatial-Temporal_CVPR_2025_paper.html) [arXiv](https://arxiv.org/abs/2405.14338)

<a id="2025-iccv"></a>
### ICCV

- **ETCH**: Generalizing Body Fitting to Clothed Humans via Equivariant Tightness (Highlight) [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Li_ETCH_Generalizing_Body_Fitting_to_Clothed_Humans_via_Equivariant_Tightness_ICCV_2025_paper.html) [Project](https://boqian-li.github.io/ETCH/)
- **VoxelKP**: A Voxel-based Network Architecture for Human Keypoint Estimation in LiDAR Data [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Shi_VoxelKP_A_Voxel-based_Network_Architecture_for_Human_Keypoint_Estimation_in_ICCV_2025_paper.html)

<a id="2025-mm"></a>
### MM

- **SS-HMR**: Self-Supervised Human Mesh Recovery from Partial Point Cloud via a Self-Improving Loop [DOI](https://doi.org/10.1145/3746027.3755570)

<a id="2025-bmvc"></a>
### BMVC

- **DepthHMR**: Leveraging Depth Around Humans for Multi-Human Mesh Generation [Paper](https://bmvc2025.bmva.org/proceedings/328/)

## 2024

<a id="2024-cvpr"></a>
### CVPR

- **PTv3**: Point Transformer V3: Simpler, Faster, Stronger [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wu_Point_Transformer_V3_Simpler_Faster_Stronger_CVPR_2024_paper.html) [Code](https://github.com/Pointcept/PointTransformerV3)
- **LiveHPS**: LiDAR-based Scene-level Human Pose and Shape Estimation in Free Environment [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Ren_LiveHPS_LiDAR-based_Scene-level_Human_Pose_and_Shape_Estimation_in_Free_CVPR_2024_paper.html) [arXiv](https://arxiv.org/abs/2402.17171) [Code](https://github.com/4DVLab/LiveHPS)

<a id="2024-eccv"></a>
### ECCV

- **NICP**: Neural ICP for 3D Human Registration at Scale [arXiv](https://arxiv.org/abs/2312.14024) [Project](https://neural-icp.github.io/)
- **LiveHPS++**: Robust and Coherent Motion Capture in Dynamic Free Environment [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04179.pdf) [arXiv](https://arxiv.org/abs/2407.09833)

## 2023

<a id="2023-cvpr"></a>
### CVPR

- **SLOPER4D**: A Scene-Aware Dataset for Global 4D Human Pose Estimation in Urban Environments [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Dai_SLOPER4D_A_Scene-Aware_Dataset_for_Global_4D_Human_Pose_Estimation_CVPR_2023_paper.html)
- **GC-KPL**: 3D Human Keypoints Estimation from Point Clouds in the Wild without Human Labels [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Weng_3D_Human_Keypoints_Estimation_From_Point_Clouds_in_the_Wild_CVPR_2023_paper.html)

<a id="2023-iccv"></a>
### ICCV

- **ArtEq**: Generalizing Neural Human Fitting to Unseen Poses With Articulated SE(3) Equivariance [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Feng_Generalizing_Neural_Human_Fitting_to_Unseen_Poses_With_Articulated_SE3_ICCV_2023_paper.html) [Project](https://arteq.is.tue.mpg.de)
- **NSF**: Neural Surface Fields for Human Modeling from Monocular Depth [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Xue_NSF_Neural_Surface_Fields_for_Human_Modeling_from_Monocular_Depth_ICCV_2023_paper.html) [Project](https://yuxuan-xue.com/nsf/)

## 2022

<a id="2022-cvpr"></a>
### CVPR

- **LiDARCap**: Long-range Marker-less 3D Human Motion Capture with LiDAR Point Clouds [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Li_LiDARCap_Long-Range_Marker-Less_3D_Human_Motion_Capture_With_LiDAR_Point_CVPR_2022_paper.html) [arXiv](https://arxiv.org/abs/2203.14698) [Code](https://github.com/jingyi-zhang/LiDARCap)

<a id="2022-eccv"></a>
### ECCV

- **VisDB**: Learning Visibility for Robust Dense Human Body Estimation [arXiv](https://arxiv.org/abs/2208.10652) [Code](https://github.com/chhankyao/visdb)

## 2021

<a id="2021-cvpr"></a>
### CVPR

- **P4Transformer**: Point 4D Transformer Networks for Spatio-Temporal Modeling in Point Cloud Videos [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Fan_Point_4D_Transformer_Networks_for_Spatio-Temporal_Modeling_in_Point_Cloud_CVPR_2021_paper.html)

<a id="2021-mm"></a>
### MM

- **VoteHMR**: Occlusion-Aware Voting Network for Robust 3D Human Mesh Recovery from Partial Point Clouds [DOI](https://doi.org/10.1145/3474085.3475309) [arXiv](https://arxiv.org/abs/2110.08729) [Code](https://github.com/hanabi7/VoteHMR)

<a id="2021-arxiv-papers"></a>
### arXiv papers

- **SelfSupHMR**: Self-supervised 3D Human Mesh Recovery from Noisy Point Clouds [arXiv](https://arxiv.org/abs/2107.07539)

## 2020

<a id="2020-cvpr"></a>
### CVPR

- **Deep Geometric Functional Maps**: Robust Feature Learning for Shape Correspondence [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Donati_Deep_Geometric_Functional_Maps_Robust_Feature_Learning_for_Shape_Correspondence_CVPR_2020_paper.html)
- **HPSE**: Sequential 3D Human Pose and Shape Estimation from Point Clouds [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Sequential_3D_Human_Pose_and_Shape_Estimation_From_Point_Clouds_CVPR_2020_paper.html)

<a id="2020-eccv"></a>
### ECCV

- **IP-Net**: Combining Implicit Function Learning and Parametric Models for 3D Human Reconstruction [arXiv](https://arxiv.org/abs/2007.11432) [Project](https://virtualhumans.mpi-inf.mpg.de/ipnet/) [Code](https://github.com/bharat-b7/IPNet)

<a id="2020-neurips"></a>
### NeurIPS

- **LoopReg**: Self-supervised Learning of Implicit Surface Correspondences, Pose and Shape for 3D Human Mesh Registration [arXiv](https://arxiv.org/abs/2010.12447) [Project](https://virtualhumans.mpi-inf.mpg.de/loopreg/)

## 2019

<a id="2019-icra"></a>
### ICRA

- **FastDepth**: Fast Monocular Depth Estimation on Embedded Systems [arXiv](https://arxiv.org/abs/1903.03273)

<a id="2019-cvpr"></a>
### CVPR

- **LBS Autoencoder**: Self-supervised Fitting of Articulated Meshes to Point Clouds [Paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Li_LBS_Autoencoder_Self-Supervised_Fitting_of_Articulated_Meshes_to_Point_Clouds_CVPR_2019_paper.html)

<a id="2019-iccv"></a>
### ICCV

- **SkeletonAware**: Skeleton-Aware 3D Human Shape Reconstruction From Point Clouds [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Jiang_Skeleton-Aware_3D_Human_Shape_Reconstruction_From_Point_Clouds_ICCV_2019_paper.html)

<a id="2019-journal-papers"></a>
### Journal papers

- **DGCNN**: Dynamic Graph CNN for Learning on Point Clouds — ACM TOG 2019 [DOI](https://doi.org/10.1145/3326362) [arXiv](https://arxiv.org/abs/1801.07829)

## Contributing

Pull requests are welcome.

- Place each paper under its **year** (newest first) and **venue**.
- Within a year, keep venues in chronological order: earlier conferences first, **Journal papers** last.
- Use `- **ShortName**: Full Title [Paper]() [arXiv]() [Project]() [Code]() …` and include only links that exist. Journal entries keep `— Journal Abbr Year` after the title.
- Open every link and confirm it resolves. Do not invent venues, years, or URLs.
- Update the Overview when a year or venue is added.

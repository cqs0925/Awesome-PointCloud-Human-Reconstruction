# Awesome-PointCloud-Human-Reconstruction

"Point Clouds, scattered collections of points in 2D or 3D, are arguably the simplest shape representation, and the raw output of most 3D data acquisition device (depth, mmWave, Lidar... )." -- DGCNN

This is a curated list of methods for deriving 3D humans from point clouds, including but not limited to 3D human registration and human mesh recovery (HMR). 
(We additionally include some interesting work in the more general 3D vision field, in seperate.)

## 📋 Overview

- [2026](#2026)
- [2025](#2025)
- [2024](#2024)
- [2023](#2023)
- [2022](#2022)
- [2021](#2021)
- [2020](#2020)
- [2019](#2019)

## 📄 Papers

### 2026

**arXiv papers**

- M4Human: A Large-Scale Multimodal mmWave Radar Benchmark for Human Mesh Reconstruction [[arXiv](https://arxiv.org/abs/2512.12378)] [[project](https://fanjunqiao.github.io/M4Human-site/)]

### 2025

**CVPR**

- Mamba4D: Efficient 4D Point Cloud Video Understanding with Disentangled Spatial-Temporal State Space Models [[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Mamba4D_Efficient_4D_Point_Cloud_Video_Understanding_with_Disentangled_Spatial-Temporal_CVPR_2025_paper.html)] [[arXiv](https://arxiv.org/abs/2405.14338)]

**ICLR**

- Occlusion-aware Non-Rigid Point Cloud Registration via Unsupervised Neural Deformation Correntropy (OAR) [[arXiv](https://arxiv.org/abs/2502.10704)] [[code](https://github.com/zikai1/OAReg)]

**BMVC**

- DepthHMR: Leveraging Depth Around Humans for Multi-Human Mesh Generation [[paper](https://bmvc2025.bmva.org/proceedings/328/)]

**MM**

- Self-Supervised Human Mesh Recovery from Partial Point Cloud via a Self-Improving Loop (SS-HMR) [[DOI](https://doi.org/10.1145/3746027.3755570)]

### 2024

**CVPR**

- Point Transformer V3: Simpler, Faster, Stronger (PTv3) [[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wu_Point_Transformer_V3_Simpler_Faster_Stronger_CVPR_2024_paper.html)] [[code](https://github.com/Pointcept/PointTransformerV3)]

**ECCV**

- NICP: Neural ICP for 3D Human Registration at Scale [[project](https://neural-icp.github.io/)] [[arXiv](https://arxiv.org/abs/2312.14024)]

### 2023

**CVPR**

- SLOPER4D: A Scene-Aware Dataset for Global 4D Human Pose Estimation in Urban Environments [[paper](https://openaccess.thecvf.com/content/CVPR2023/html/Dai_SLOPER4D_A_Scene-Aware_Dataset_for_Global_4D_Human_Pose_Estimation_CVPR_2023_paper.html)]
- 3D Human Keypoints Estimation from Point Clouds in the Wild without Human Labels (GC-KPL) [[paper](https://openaccess.thecvf.com/content/CVPR2023/html/Weng_3D_Human_Keypoints_Estimation_From_Point_Clouds_in_the_Wild_CVPR_2023_paper.html)]

**ICCV**

- Generalizing Neural Human Fitting to Unseen Poses With Articulated SE(3) Equivariance (ArtEq) [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Feng_Generalizing_Neural_Human_Fitting_to_Unseen_Poses_With_Articulated_SE3_ICCV_2023_paper.html)] [[project](https://arteq.is.tue.mpg.de)]
- NSF: Neural Surface Fields for Human Modeling from Monocular Depth [[paper](https://openaccess.thecvf.com/content/ICCV2023/html/Xue_NSF_Neural_Surface_Fields_for_Human_Modeling_from_Monocular_Depth_ICCV_2023_paper.html)] [[project](https://yuxuan-xue.com/nsf/)]

### 2022

**ECCV**

- Learning Visibility for Robust Dense Human Body Estimation (VisDB) [[arXiv](https://arxiv.org/abs/2208.10652)] [[code](https://github.com/chhankyao/visdb)]

### 2021

**CVPR**

- Point 4D Transformer Networks for Spatio-Temporal Modeling in Point Cloud Videos (P4Transformer) [[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Fan_Point_4D_Transformer_Networks_for_Spatio-Temporal_Modeling_in_Point_Cloud_CVPR_2021_paper.html)]

**MM**

- VoteHMR: Occlusion-Aware Voting Network for Robust 3D Human Mesh Recovery from Partial Point Clouds [[DOI](https://doi.org/10.1145/3474085.3475309)] [[arXiv](https://arxiv.org/abs/2110.08729)] [[code](https://github.com/hanabi7/VoteHMR)]

**arXiv papers**

- Self-supervised 3D Human Mesh Recovery from Noisy Point Clouds [[arXiv](https://arxiv.org/abs/2107.07539)]

### 2020

**CVPR**

- Deep Geometric Functional Maps: Robust Feature Learning for Shape Correspondence [[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Donati_Deep_Geometric_Functional_Maps_Robust_Feature_Learning_for_Shape_Correspondence_CVPR_2020_paper.html)]
- Sequential 3D Human Pose and Shape Estimation from Point Clouds (HPSE) [[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Sequential_3D_Human_Pose_and_Shape_Estimation_From_Point_Clouds_CVPR_2020_paper.html)]

**ECCV**

- Combining Implicit Function Learning and Parametric Models for 3D Human Reconstruction (IP-Net) [[project](https://virtualhumans.mpi-inf.mpg.de/ipnet/)] [[arXiv](https://arxiv.org/abs/2007.11432)] [[code](https://github.com/bharat-b7/IPNet)]

**NeurIPS**

- LoopReg: Self-supervised Learning of Implicit Surface Correspondences, Pose and Shape for 3D Human Mesh Registration [[project](https://virtualhumans.mpi-inf.mpg.de/loopreg/)] [[arXiv](https://arxiv.org/abs/2010.12447)]

### 2019

**CVPR**

- LBS Autoencoder: Self-supervised Fitting of Articulated Meshes to Point Clouds [[paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Li_LBS_Autoencoder_Self-Supervised_Fitting_of_Articulated_Meshes_to_Point_Clouds_CVPR_2019_paper.html)]

**ICCV**

- Skeleton-Aware 3D Human Shape Reconstruction From Point Clouds [[paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Jiang_Skeleton-Aware_3D_Human_Shape_Reconstruction_From_Point_Clouds_ICCV_2019_paper.html)]

**ICRA**

- FastDepth: Fast Monocular Depth Estimation on Embedded Systems [[arXiv](https://arxiv.org/abs/1903.03273)]

**Journal papers**

- Dynamic Graph CNN for Learning on Point Clouds (DGCNN) — ACM TOG 2019 [[DOI](https://doi.org/10.1145/3326362)] [[arXiv](https://arxiv.org/abs/1801.07829)]

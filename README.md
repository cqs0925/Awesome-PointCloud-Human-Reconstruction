# Awesome-PointCloud-Human-Reconstruction

"Point Clouds, scattered collections of points in 2D or 3D, are arguably the simplest shape representation, and the raw output of most 3D data acquisition device (depth, mmWave, Lidar... )." -- DGCNN

This is a curated list of methods for deriving 3D humans from point clouds, including but not limited to 3D human registration and human mesh recovery (HMR). 
(We additionally include some interesting work in the more general 3D vision field, separately.)

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

**CVPR**

- M4Human: A Large-Scale Multimodal mmWave Radar Benchmark for Human Mesh Reconstruction [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Fan_M4Human_A_Large-Scale_Multimodal_mmWave_Radar_Benchmark_for_Human_Mesh_CVPR_2026_paper.html)] [[arXiv](https://arxiv.org/abs/2512.12378)] [[Project](https://fanjunqiao.github.io/M4Human-site/)] [[Code](https://github.com/FanJunqiao/M4Human)]
- UniSH: Unifying Scene and Human Reconstruction in a Feed-Forward Pass [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Li_UniSH_Unifying_Scene_and_Human_Reconstruction_in_a_Feed-Forward_Pass_CVPR_2026_paper.html)] [[Project](https://murphylmf.github.io/UniSH/)]

**Journal papers**

- PointHPS: Cascaded 3D Human Pose and Shape Estimation from Point Clouds — IJCV 2026 [[arXiv](https://arxiv.org/abs/2308.14492)] [[Project](http://caizhongang.com/projects/PointHPS/)] [[Code](https://github.com/MotrixLab/PointHPS)] [[DOI](https://doi.org/10.1007/s11263-026-02750-1)]

### 2025

**CVPR**

- Mamba4D: Efficient 4D Point Cloud Video Understanding with Disentangled Spatial-Temporal State Space Models [[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Mamba4D_Efficient_4D_Point_Cloud_Video_Understanding_with_Disentangled_Spatial-Temporal_CVPR_2025_paper.html)] [[arXiv](https://arxiv.org/abs/2405.14338)]

**ICCV**

- ETCH: Generalizing Body Fitting to Clothed Humans via Equivariant Tightness (Highlight) [[Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Li_ETCH_Generalizing_Body_Fitting_to_Clothed_Humans_via_Equivariant_Tightness_ICCV_2025_paper.html)] [[Project](https://boqian-li.github.io/ETCH/)]
- VoxelKP: A Voxel-based Network Architecture for Human Keypoint Estimation in LiDAR Data [[Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Shi_VoxelKP_A_Voxel-based_Network_Architecture_for_Human_Keypoint_Estimation_in_ICCV_2025_paper.html)]

**ICLR**

- Occlusion-aware Non-Rigid Point Cloud Registration via Unsupervised Neural Deformation Correntropy (OAR) [[arXiv](https://arxiv.org/abs/2502.10704)] [[Code](https://github.com/zikai1/OAReg)]

**WACV**

- PocoLoco: A Point Cloud Diffusion Model of Human Shape in Loose Clothing [[Paper](https://openaccess.thecvf.com/content/WACV2025/html/Seth_PocoLoco_A_Point_Cloud_Diffusion_Model_of_Human_Shape_in_WACV_2025_paper.html)]

**BMVC**

- DepthHMR: Leveraging Depth Around Humans for Multi-Human Mesh Generation [[Paper](https://bmvc2025.bmva.org/proceedings/328/)]

**MM**

- Self-Supervised Human Mesh Recovery from Partial Point Cloud via a Self-Improving Loop (SS-HMR) [[DOI](https://doi.org/10.1145/3746027.3755570)]

### 2024

**CVPR**

- Point Transformer V3: Simpler, Faster, Stronger (PTv3) [[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wu_Point_Transformer_V3_Simpler_Faster_Stronger_CVPR_2024_paper.html)] [[Code](https://github.com/Pointcept/PointTransformerV3)]
- LiveHPS: LiDAR-based Scene-level Human Pose and Shape Estimation in Free Environment [[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Ren_LiveHPS_LiDAR-based_Scene-level_Human_Pose_and_Shape_Estimation_in_Free_CVPR_2024_paper.html)] [[Code](https://github.com/4DVLab/LiveHPS)] [[arXiv](https://arxiv.org/abs/2402.17171)]

**ECCV**

- NICP: Neural ICP for 3D Human Registration at Scale [[Project](https://neural-icp.github.io/)] [[arXiv](https://arxiv.org/abs/2312.14024)]
- LiveHPS++: Robust and Coherent Motion Capture in Dynamic Free Environment [[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04179.pdf)] [[arXiv](https://arxiv.org/abs/2407.09833)]

### 2023

**CVPR**

- SLOPER4D: A Scene-Aware Dataset for Global 4D Human Pose Estimation in Urban Environments [[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Dai_SLOPER4D_A_Scene-Aware_Dataset_for_Global_4D_Human_Pose_Estimation_CVPR_2023_paper.html)]
- 3D Human Keypoints Estimation from Point Clouds in the Wild without Human Labels (GC-KPL) [[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Weng_3D_Human_Keypoints_Estimation_From_Point_Clouds_in_the_Wild_CVPR_2023_paper.html)]

**ICCV**

- Generalizing Neural Human Fitting to Unseen Poses With Articulated SE(3) Equivariance (ArtEq) [[Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Feng_Generalizing_Neural_Human_Fitting_to_Unseen_Poses_With_Articulated_SE3_ICCV_2023_paper.html)] [[Project](https://arteq.is.tue.mpg.de)]
- NSF: Neural Surface Fields for Human Modeling from Monocular Depth [[Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Xue_NSF_Neural_Surface_Fields_for_Human_Modeling_from_Monocular_Depth_ICCV_2023_paper.html)] [[Project](https://yuxuan-xue.com/nsf/)]

### 2022

**CVPR**

- LiDARCap: Long-range Marker-less 3D Human Motion Capture with LiDAR Point Clouds [[Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Li_LiDARCap_Long-Range_Marker-Less_3D_Human_Motion_Capture_With_LiDAR_Point_CVPR_2022_paper.html)] [[arXiv](https://arxiv.org/abs/2203.14698)] [[Code](https://github.com/jingyi-zhang/LiDARCap)]

**ECCV**

- Learning Visibility for Robust Dense Human Body Estimation (VisDB) [[arXiv](https://arxiv.org/abs/2208.10652)] [[Code](https://github.com/chhankyao/visdb)]

### 2021

**CVPR**

- Point 4D Transformer Networks for Spatio-Temporal Modeling in Point Cloud Videos (P4Transformer) [[Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Fan_Point_4D_Transformer_Networks_for_Spatio-Temporal_Modeling_in_Point_Cloud_CVPR_2021_paper.html)]

**MM**

- VoteHMR: Occlusion-Aware Voting Network for Robust 3D Human Mesh Recovery from Partial Point Clouds [[DOI](https://doi.org/10.1145/3474085.3475309)] [[arXiv](https://arxiv.org/abs/2110.08729)] [[Code](https://github.com/hanabi7/VoteHMR)]

**arXiv papers**

- Self-supervised 3D Human Mesh Recovery from Noisy Point Clouds [[arXiv](https://arxiv.org/abs/2107.07539)]

### 2020

**CVPR**

- Deep Geometric Functional Maps: Robust Feature Learning for Shape Correspondence [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Donati_Deep_Geometric_Functional_Maps_Robust_Feature_Learning_for_Shape_Correspondence_CVPR_2020_paper.html)]
- Sequential 3D Human Pose and Shape Estimation from Point Clouds (HPSE) [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Sequential_3D_Human_Pose_and_Shape_Estimation_From_Point_Clouds_CVPR_2020_paper.html)]

**ECCV**

- Combining Implicit Function Learning and Parametric Models for 3D Human Reconstruction (IP-Net) [[Project](https://virtualhumans.mpi-inf.mpg.de/ipnet/)] [[arXiv](https://arxiv.org/abs/2007.11432)] [[Code](https://github.com/bharat-b7/IPNet)]

**NeurIPS**

- LoopReg: Self-supervised Learning of Implicit Surface Correspondences, Pose and Shape for 3D Human Mesh Registration [[Project](https://virtualhumans.mpi-inf.mpg.de/loopreg/)] [[arXiv](https://arxiv.org/abs/2010.12447)]

### 2019

**CVPR**

- LBS Autoencoder: Self-supervised Fitting of Articulated Meshes to Point Clouds [[Paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Li_LBS_Autoencoder_Self-Supervised_Fitting_of_Articulated_Meshes_to_Point_Clouds_CVPR_2019_paper.html)]

**ICCV**

- Skeleton-Aware 3D Human Shape Reconstruction From Point Clouds [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Jiang_Skeleton-Aware_3D_Human_Shape_Reconstruction_From_Point_Clouds_ICCV_2019_paper.html)]

**ICRA**

- FastDepth: Fast Monocular Depth Estimation on Embedded Systems [[arXiv](https://arxiv.org/abs/1903.03273)]

**Journal papers**

- Dynamic Graph CNN for Learning on Point Clouds (DGCNN) — ACM TOG 2019 [[DOI](https://doi.org/10.1145/3326362)] [[arXiv](https://arxiv.org/abs/1801.07829)]

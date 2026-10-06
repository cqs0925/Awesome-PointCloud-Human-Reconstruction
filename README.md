<h1 align="center">Awesome Point Cloud Human Reconstruction</h1>

<p align="center">
  A curated collection of research on human pose, shape, fitting, and motion capture from point clouds.
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a>
  <a href="https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/stargazers"><img src="https://img.shields.io/github/stars/cqs0925/Awesome-PointCloud-Human-Reconstruction?style=flat-square&amp;color=ca8a04" alt="GitHub stars"></a>
  <a href="https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/forks"><img src="https://img.shields.io/github/forks/cqs0925/Awesome-PointCloud-Human-Reconstruction?style=flat-square&amp;color=64748b" alt="GitHub forks"></a>
  <a href="https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/issues"><img src="https://img.shields.io/github/issues/cqs0925/Awesome-PointCloud-Human-Reconstruction?style=flat-square&amp;color=0891b2" alt="Open issues"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/cqs0925/Awesome-PointCloud-Human-Reconstruction?style=flat-square&amp;color=2563eb" alt="License: MIT"></a>
  <a href="https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/commits/main"><img src="https://img.shields.io/github/last-commit/cqs0925/Awesome-PointCloud-Human-Reconstruction?style=flat-square&amp;color=64748b" alt="Last commit"></a>
  <a href="https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/pulls"><img src="https://img.shields.io/badge/PRs-welcome-0d9488?style=flat-square" alt="Pull requests welcome"></a>
</p>

<p align="center">
  <strong>47 papers</strong> &nbsp;·&nbsp; 35 Core / 12 Related &nbsp;·&nbsp; 2019–2026
</p>

<p align="center">
  <a href="#browse-by-task">Browse by task</a> &nbsp; / &nbsp;
  <a href="#overview">Browse by year</a> &nbsp; / &nbsp;
  <a href="#reading-the-tags">Reading the tags</a> &nbsp; / &nbsp;
  <a href="#contributing">Contribute</a>
</p>

---

<a id="scope"></a>
> **Scope.** **Core** work studies human point clouds, body scans, depth/radar observations, or optical-marker point sets, including human shape generation and datasets. **Related** work covers RGB-only human methods and general 3D techniques included as background. These labels describe relevance to this collection.

## Browse by task

Expand a category to jump to a paper. Each Core paper is indexed by its primary contribution; a method can support additional tasks. Related papers are grouped separately by their reason for inclusion.

<!-- Task index: update category membership and counts when adding or reclassifying a paper. -->
<a id="task-pose-keypoints"></a>
<details>
<summary><strong>Pose & keypoints</strong> · 3 papers</summary>

Human joint and keypoint estimation.

- [DenseCompletionHPE (2026)](#paper-densecompletionhpe)
- [VoxelKP (2025)](#paper-voxelkp)
- [GC-KPL (2023)](#paper-gc-kpl)

</details>

<a id="task-shape-mesh"></a>
<details>
<summary><strong>Shape & mesh</strong> · 12 papers</summary>

Human mesh recovery, surface modeling, and point-cloud shape generation.

- [SynHMR (2026)](#paper-synhmr)
- [PointHPS (2026)](#paper-pointhps)
- [PocoLoco (2025)](#paper-pocoloco)
- [SS-HMR (2025)](#paper-ss-hmr)
- [LiDAR-HMR (2025)](#paper-lidar-hmr)
- [LiveHPS (2024)](#paper-livehps)
- [NSF (2023)](#paper-nsf)
- [VoteHMR (2021)](#paper-votehmr)
- [SelfSupHMR (2021)](#paper-selfsuphmr)
- [HPSE (2020)](#paper-hpse)
- [IP-Net (2020)](#paper-ip-net)
- [SkeletonAware (2019)](#paper-skeletonaware)

</details>

<a id="task-registration-fitting"></a>
<details>
<summary><strong>Registration & fitting</strong> · 7 papers</summary>

Human-template registration and body-model fitting to 3D observations.

- [ETCH-X (2026)](#paper-etch-x)
- [OmniFit (2026)](#paper-omnifit)
- [ETCH (2025)](#paper-etch)
- [NICP (2024)](#paper-nicp)
- [ArtEq (2023)](#paper-arteq)
- [LoopReg (2020)](#paper-loopreg)
- [LBS-AE (2019)](#paper-lbs-ae)

</details>

<a id="task-motion-capture"></a>
<details>
<summary><strong>Motion capture</strong> · 11 papers</summary>

Temporal human motion recovery from LiDAR, fused observations, or optical-marker point sets.

- [DirtyMoCap (2026)](#paper-dirtymocap)
- [OptimalCap (2026)](#paper-optimalcap)
- [LiDAR-FMC (2026)](#paper-lidar-fmc)
- [FreeCap (2025)](#paper-freecap)
- [OpenMoCap (2025)](#paper-openmocap)
- [DAMO (2025)](#paper-damo)
- [LiveHPS++ (2024)](#paper-livehps-plus-plus)
- [RoMo (2024)](#paper-romo)
- [LocalMoCap (2023)](#paper-localmocap)
- [LiDARCap (2022)](#paper-lidarcap)
- [SOMA (2021)](#paper-soma)

</details>

<a id="task-datasets-benchmarks"></a>
<details>
<summary><strong>Datasets & benchmarks</strong> · 2 papers</summary>

Human datasets and evaluation benchmarks.

- [M4Human (2026)](#paper-m4human)
- [SLOPER4D (2023)](#paper-sloper4d)

</details>

<a id="related-work"></a>
<details>
<summary><strong>Related work</strong> · 12 papers</summary>

**RGB human reconstruction.** Human reconstruction methods that use RGB images or video; internally estimated depth or point clouds do not make their inputs measured 3D observations.

[Human3R (2026)](#paper-human3r) · [UniSH (2026)](#paper-unish) · [DepthHMR (2025)](#paper-depthhmr) · [VisDB (2022)](#paper-visdb)

**General point-cloud models.** General spatial or temporal point-cloud feature models that can inform human-specific methods.

[Mamba4D (2025)](#paper-mamba4d) · [PTv3 (2024)](#paper-ptv3) · [P4Transformer (2021)](#paper-p4transformer) · [DGCNN (2019)](#paper-dgcnn)

**General registration & correspondence.** General 3D registration and shape correspondence, rather than human-body fitting methods.

[OAR (2025)](#paper-oar) · [GeomFmaps (2020)](#paper-geomfmaps)

**RGB view synthesis & depth.** Related RGB view-synthesis and monocular depth-estimation methods.

[MultiHumanNVS (2022)](#paper-multihumannvs) · [FastDepth (2019)](#paper-fastdepth)

</details>

## Overview

| Year | Papers | Venues |
| :--- | ---: | :--- |
| [**2026**](#2026) | 11 | [ICLR](#2026-iclr) · [CVPR](#2026-cvpr) · [ECCV](#2026-eccv) · [SIGGRAPH Asia](#2026-siggraph-asia) · [Journals](#2026-journal-papers) |
| [**2025**](#2025) | 11 | [WACV](#2025-wacv) · [AAAI](#2025-aaai) · [ICLR](#2025-iclr) · [CVPR](#2025-cvpr) · [ICCV](#2025-iccv) · [MM](#2025-mm) · [BMVC](#2025-bmvc) · [Journals](#2025-journal-papers) |
| [**2024**](#2024) | 5 | [CVPR](#2024-cvpr) · [ECCV](#2024-eccv) · [SIGGRAPH Asia](#2024-siggraph-asia) |
| [**2023**](#2023) | 5 | [CVPR](#2023-cvpr) · [ICCV](#2023-iccv) · [SIGGRAPH Asia](#2023-siggraph-asia) |
| [**2022**](#2022) | 3 | [CVPR](#2022-cvpr) · [SIGGRAPH](#2022-siggraph) · [ECCV](#2022-eccv) |
| [**2021**](#2021) | 4 | [CVPR](#2021-cvpr) · [ICCV](#2021-iccv) · [MM](#2021-mm) · [arXiv](#2021-arxiv-papers) |
| [**2020**](#2020) | 4 | [CVPR](#2020-cvpr) · [ECCV](#2020-eccv) · [NeurIPS](#2020-neurips) |
| [**2019**](#2019) | 4 | [ICRA](#2019-icra) · [CVPR](#2019-cvpr) · [ICCV](#2019-iccv) · [Journals](#2019-journal-papers) |

## Reading the tags

Each entry separates three kinds of information:

- **Scope:** `Core` or `Related`, as defined [above](#scope).
- **Task:** the primary research contribution, linked to its navigation category.
- **Data sources:** colored badges for data used in training, evaluation, or supervision. Multiple badges are allowed; they do not identify the model's inference inputs or require every tagged source at inference.

For example, [FastDepth](#paper-fastdepth) predicts depth from RGB, while its depth data provides supervision/evaluation. It is Related work, and its `Depth` badge does not mean that depth is an input. [NSF](#paper-nsf) models human surfaces from depth observations with pose conditioning, so its primary task is Shape & mesh.

<a id="data-sources"></a>

<details>
<summary><strong>View the data-source legend</strong></summary>

| Badge | Meaning |
| :--- | :--- |
| ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) | Real LiDAR point clouds (e.g., LiDARHuman26M, SLOPER4D, Waymo, FreeMotion) |
| ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) | Depth cameras / RGB-D (Kinect, RealSense, ToF), including point clouds back-projected from depth |
| ![Radar](https://img.shields.io/badge/Radar-ea580c?style=flat-square) | mmWave radar |
| ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) | 3D body scans or multi-view reconstructions (e.g., FAUST, DFAUST, CAPE, 4D-Dress, BUFF, RenderPeople) |
| ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) | Optical-marker mocap point clouds, or point clouds synthesized from mocap motion (e.g., AMASS, CMU) |
| ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) | Simulated or rendered data (e.g., SURREAL, NoiseMotion, BEDLAM, ModelNet/ShapeNet CAD, simulated garments) |
| ![RGB](https://img.shields.io/badge/RGB-0891b2?style=flat-square) | RGB imagery used in experiments, including image/video inputs or visual cues; the badge alone does not imply RGB-only inference |
| ![Unverified](https://img.shields.io/badge/Unverified-64748b?style=flat-square) | Source could not be verified from the paper |

</details>

**Resource links:** **Paper** — official PDF / proceedings · **arXiv** — preprint · **Project** — project page · **Code** — source · **DOI** — publisher DOI · **OpenReview** — venue forum

## Papers

Years are newest first. Within a year, venues follow conference chronology, and journal papers come last.

Every entry carries its scope and primary task before the experimental data-source badges. Existing paper titles and resource links are kept in one chronological list.

## 2026

<a id="2026-iclr"></a>
### ICLR

- <a id="paper-human3r"></a>**Human3R**: Everyone Everywhere All at Once<br>
  `Related` · [RGB human reconstruction](#related-work) &nbsp;|&nbsp; ![RGB](https://img.shields.io/badge/RGB-0891b2?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2510.06219) · [Project](https://fanegg.github.io/Human3R/) · [Code](https://github.com/fanegg/Human3R) · [OpenReview](https://openreview.net/forum?id=y7duXr0JXF)

<a id="2026-cvpr"></a>
### CVPR

- <a id="paper-m4human"></a>**M4Human**: A Large-Scale Multimodal mmWave Radar Benchmark for Human Mesh Reconstruction<br>
  `Core` · [Datasets & benchmarks](#task-datasets-benchmarks) &nbsp;|&nbsp; ![Radar](https://img.shields.io/badge/Radar-ea580c?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Fan_M4Human_A_Large-Scale_Multimodal_mmWave_Radar_Benchmark_for_Human_Mesh_CVPR_2026_paper.html) · [arXiv](https://arxiv.org/abs/2512.12378) · [Project](https://fanjunqiao.github.io/M4Human-site/) · [Code](https://github.com/FanJunqiao/M4Human)

- <a id="paper-unish"></a>**UniSH**: Unifying Scene and Human Reconstruction in a Feed-Forward Pass<br>
  `Related` · [RGB human reconstruction](#related-work) &nbsp;|&nbsp; ![RGB](https://img.shields.io/badge/RGB-0891b2?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Li_UniSH_Unifying_Scene_and_Human_Reconstruction_in_a_Feed-Forward_Pass_CVPR_2026_paper.html) · [Project](https://murphylmf.github.io/UniSH/)

<a id="2026-eccv"></a>
### ECCV

- <a id="paper-etch-x"></a>**ETCH-X**: Robustify Expressive Body Fitting to Clothed Humans with Composable Datasets<br>
  `Core` · [Registration & fitting](#task-registration-fitting) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2604.08548) · [Project](https://xiaobenli00.github.io/ETCH-X) · [Code](https://github.com/XiaobenLi00/ETCH-X)

- <a id="paper-omnifit"></a>**OmniFit**: Multi-modal 3D Body Fitting via Scale-agnostic Dense Landmark Prediction<br>
  `Core` · [Registration & fitting](#task-registration-fitting) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2604.21575) · [Project](https://zcai0612.github.io/OmniFit/) · [Code](https://github.com/zcai0612/OmniFit) · [DOI](https://doi.org/10.1007/978-3-032-36969-7_24)

- <a id="paper-synhmr"></a>**SynHMR**: Synergistic Joint-Mesh Modeling for LiDAR-based Human Mesh Reconstruction<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) &nbsp;·&nbsp; [Code](https://github.com/ShiRui1208/SynHMR) · [DOI](https://doi.org/10.1007/978-3-032-37314-4_21)

<a id="2026-siggraph-asia"></a>
### SIGGRAPH Asia

- <a id="paper-dirtymocap"></a>**DirtyMoCap**: Robust Motion Capture from Unconstrained Markers<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2609.19927) · [Project](https://wanglongzju.github.io/DirtyMoCap-Project-Page) · [Code](https://github.com/WangLongZJU/DirtyMoCap)

<a id="2026-journal-papers"></a>
### Journal papers

- <a id="paper-pointhps"></a>**PointHPS**: Cascaded 3D Human Pose and Shape Estimation from Point Clouds — IJCV 2026<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2308.14492) · [Project](http://caizhongang.com/projects/PointHPS/) · [Code](https://github.com/MotrixLab/PointHPS) · [DOI](https://doi.org/10.1007/s11263-026-02750-1)

- <a id="paper-optimalcap"></a>**OptimalCap**: Efficient and Robust LiDAR-Based Motion Capture in Free Environments — IEEE TPAMI 2026<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [DOI](https://doi.org/10.1109/TPAMI.2026.3669427)

- <a id="paper-lidar-fmc"></a>**LiDAR-FMC**: Accurate and Robust Human Capture From Point-Cloud Video — IEEE TCSVT 2026<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [DOI](https://doi.org/10.1109/TCSVT.2026.3670967)

- <a id="paper-densecompletionhpe"></a>**DenseCompletionHPE**: Robust 3D Human Pose Estimation via Dense Point Cloud Completion — IEEE TMM 2026<br>
  `Core` · [Pose & keypoints](#task-pose-keypoints) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) &nbsp;·&nbsp; [DOI](https://doi.org/10.1109/TMM.2026.3724742)

<p align="right"><a href="#overview">↑ Back to overview</a></p>

---

## 2025

<a id="2025-wacv"></a>
### WACV

- <a id="paper-pocoloco"></a>**PocoLoco**: A Point Cloud Diffusion Model of Human Shape in Loose Clothing<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/WACV2025/html/Seth_PocoLoco_A_Point_Cloud_Diffusion_Model_of_Human_Shape_in_WACV_2025_paper.html)

<a id="2025-aaai"></a>
### AAAI

- <a id="paper-freecap"></a>**FreeCap**: Hybrid Calibration-Free Motion Capture in Open Environments<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) ![RGB](https://img.shields.io/badge/RGB-0891b2?style=flat-square) &nbsp;·&nbsp; [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32977) · [arXiv](https://arxiv.org/abs/2411.04469) · [DOI](https://doi.org/10.1609/aaai.v39i9.32977)

<a id="2025-iclr"></a>
### ICLR

- <a id="paper-oar"></a>**OAR**: Occlusion-aware Non-Rigid Point Cloud Registration via Unsupervised Neural Deformation Correntropy<br>
  `Related` · [General registration & correspondence](#related-work) &nbsp;|&nbsp; ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2502.10704) · [Code](https://github.com/zikai1/OAReg)

<a id="2025-cvpr"></a>
### CVPR

- <a id="paper-mamba4d"></a>**Mamba4D**: Efficient 4D Point Cloud Video Understanding with Disentangled Spatial-Temporal State Space Models<br>
  `Related` · [General point-cloud models](#related-work) &nbsp;|&nbsp; ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Mamba4D_Efficient_4D_Point_Cloud_Video_Understanding_with_Disentangled_Spatial-Temporal_CVPR_2025_paper.html) · [arXiv](https://arxiv.org/abs/2405.14338)

<a id="2025-iccv"></a>
### ICCV

- <a id="paper-etch"></a>**ETCH**: Generalizing Body Fitting to Clothed Humans via Equivariant Tightness (Highlight)<br>
  `Core` · [Registration & fitting](#task-registration-fitting) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Li_ETCH_Generalizing_Body_Fitting_to_Clothed_Humans_via_Equivariant_Tightness_ICCV_2025_paper.html) · [Project](https://boqian-li.github.io/ETCH/)

- <a id="paper-voxelkp"></a>**VoxelKP**: A Voxel-based Network Architecture for Human Keypoint Estimation in LiDAR Data<br>
  `Core` · [Pose & keypoints](#task-pose-keypoints) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Shi_VoxelKP_A_Voxel-based_Network_Architecture_for_Human_Keypoint_Estimation_in_ICCV_2025_paper.html)

<a id="2025-mm"></a>
### MM

- <a id="paper-ss-hmr"></a>**SS-HMR**: Self-Supervised Human Mesh Recovery from Partial Point Cloud via a Self-Improving Loop<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [DOI](https://doi.org/10.1145/3746027.3755570)

- <a id="paper-openmocap"></a>**OpenMoCap**: Rethinking Optical Motion Capture under Real-world Occlusion<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2508.12610) · [Project](https://qianchen214.github.io/openmocap.github.io/) · [Code](https://github.com/qianchen214/OpenMoCap) · [DOI](https://doi.org/10.1145/3746027.3754932)

<a id="2025-bmvc"></a>
### BMVC

- <a id="paper-depthhmr"></a>**DepthHMR**: Leveraging Depth Around Humans for Multi-Human Mesh Generation<br>
  `Related` · [RGB human reconstruction](#related-work) &nbsp;|&nbsp; ![RGB](https://img.shields.io/badge/RGB-0891b2?style=flat-square) &nbsp;·&nbsp; [Paper](https://bmvc2025.bmva.org/proceedings/328/)

<a id="2025-journal-papers"></a>
### Journal papers

- <a id="paper-lidar-hmr"></a>**LiDAR-HMR**: 3D Human Mesh Recovery from LiDAR — IEEE TMM 2025<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2311.11971) · [Code](https://github.com/soullessrobot/LiDAR-HMR) · [DOI](https://doi.org/10.1109/TMM.2025.3590928)

- <a id="paper-damo"></a>**DAMO**: A Deep Solver for Arbitrary Marker Configuration in Optical Motion Capture — ACM TOG 2025<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [Code](https://github.com/CritBear/damo) · [DOI](https://doi.org/10.1145/3695865)

<p align="right"><a href="#overview">↑ Back to overview</a></p>

---

## 2024

<a id="2024-cvpr"></a>
### CVPR

- <a id="paper-ptv3"></a>**PTv3**: Point Transformer V3: Simpler, Faster, Stronger<br>
  `Related` · [General point-cloud models](#related-work) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wu_Point_Transformer_V3_Simpler_Faster_Stronger_CVPR_2024_paper.html) · [Code](https://github.com/Pointcept/PointTransformerV3)

- <a id="paper-livehps"></a>**LiveHPS**: LiDAR-based Scene-level Human Pose and Shape Estimation in Free Environment<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Ren_LiveHPS_LiDAR-based_Scene-level_Human_Pose_and_Shape_Estimation_in_Free_CVPR_2024_paper.html) · [arXiv](https://arxiv.org/abs/2402.17171) · [Code](https://github.com/4DVLab/LiveHPS)

<a id="2024-eccv"></a>
### ECCV

- <a id="paper-nicp"></a>**NICP**: Neural ICP for 3D Human Registration at Scale<br>
  `Core` · [Registration & fitting](#task-registration-fitting) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2312.14024) · [Project](https://neural-icp.github.io/)

- <a id="paper-livehps-plus-plus"></a>**LiveHPS++**: Robust and Coherent Motion Capture in Dynamic Free Environment<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04179.pdf) · [arXiv](https://arxiv.org/abs/2407.09833)

<a id="2024-siggraph-asia"></a>
### SIGGRAPH Asia

- <a id="paper-romo"></a>**RoMo**: A Robust Solver for Full-body Unlabeled Optical Motion Capture<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2410.02788) · [Code](https://github.com/non-void/RoMo) · [DOI](https://doi.org/10.1145/3680528.3687615)

<p align="right"><a href="#overview">↑ Back to overview</a></p>

---

## 2023

<a id="2023-cvpr"></a>
### CVPR

- <a id="paper-sloper4d"></a>**SLOPER4D**: A Scene-Aware Dataset for Global 4D Human Pose Estimation in Urban Environments<br>
  `Core` · [Datasets & benchmarks](#task-datasets-benchmarks) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Dai_SLOPER4D_A_Scene-Aware_Dataset_for_Global_4D_Human_Pose_Estimation_CVPR_2023_paper.html)

- <a id="paper-gc-kpl"></a>**GC-KPL**: 3D Human Keypoints Estimation from Point Clouds in the Wild without Human Labels<br>
  `Core` · [Pose & keypoints](#task-pose-keypoints) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Weng_3D_Human_Keypoints_Estimation_From_Point_Clouds_in_the_Wild_CVPR_2023_paper.html)

<a id="2023-iccv"></a>
### ICCV

- <a id="paper-arteq"></a>**ArtEq**: Generalizing Neural Human Fitting to Unseen Poses With Articulated SE(3) Equivariance<br>
  `Core` · [Registration & fitting](#task-registration-fitting) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Feng_Generalizing_Neural_Human_Fitting_to_Unseen_Poses_With_Articulated_SE3_ICCV_2023_paper.html) · [Project](https://arteq.is.tue.mpg.de)

- <a id="paper-nsf"></a>**NSF**: Neural Surface Fields for Human Modeling from Monocular Depth<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Xue_NSF_Neural_Surface_Fields_for_Human_Modeling_from_Monocular_Depth_ICCV_2023_paper.html) · [Project](https://yuxuan-xue.com/nsf/)

<a id="2023-siggraph-asia"></a>
### SIGGRAPH Asia

- <a id="paper-localmocap"></a>**LocalMoCap**: A Locality-based Neural Solver for Optical Motion Capture<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2309.00428) · [Code](https://github.com/non-void/LocalMoCap) · [DOI](https://doi.org/10.1145/3610548.3618148)

<p align="right"><a href="#overview">↑ Back to overview</a></p>

---

## 2022

<a id="2022-cvpr"></a>
### CVPR

- <a id="paper-lidarcap"></a>**LiDARCap**: Long-range Marker-less 3D Human Motion Capture with LiDAR Point Clouds<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Li_LiDARCap_Long-Range_Marker-Less_3D_Human_Motion_Capture_With_LiDAR_Point_CVPR_2022_paper.html) · [arXiv](https://arxiv.org/abs/2203.14698) · [Code](https://github.com/jingyi-zhang/LiDARCap)

<a id="2022-siggraph"></a>
### SIGGRAPH

- <a id="paper-multihumannvs"></a>**MultiHumanNVS**: Novel View Synthesis of Human Interactions from Sparse Multi-view Videos<br>
  `Related` · [RGB view synthesis & depth](#related-work) &nbsp;|&nbsp; ![RGB](https://img.shields.io/badge/RGB-0891b2?style=flat-square) &nbsp;·&nbsp; [Project](https://chingswy.github.io/easymocap-public-doc/works/multinb.html) · [Code](https://github.com/zju3dv/EasyMocap) · [DOI](https://doi.org/10.1145/3528233.3530704)

<a id="2022-eccv"></a>
### ECCV

- <a id="paper-visdb"></a>**VisDB**: Learning Visibility for Robust Dense Human Body Estimation<br>
  `Related` · [RGB human reconstruction](#related-work) &nbsp;|&nbsp; ![RGB](https://img.shields.io/badge/RGB-0891b2?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2208.10652) · [Code](https://github.com/chhankyao/visdb)

<p align="right"><a href="#overview">↑ Back to overview</a></p>

---

## 2021

<a id="2021-cvpr"></a>
### CVPR

- <a id="paper-p4transformer"></a>**P4Transformer**: Point 4D Transformer Networks for Spatio-Temporal Modeling in Point Cloud Videos<br>
  `Related` · [General point-cloud models](#related-work) &nbsp;|&nbsp; ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Fan_Point_4D_Transformer_Networks_for_Spatio-Temporal_Modeling_in_Point_Cloud_CVPR_2021_paper.html)

<a id="2021-iccv"></a>
### ICCV

- <a id="paper-soma"></a>**SOMA**: Solving Optical Marker-Based MoCap Automatically<br>
  `Core` · [Motion capture](#task-motion-capture) &nbsp;|&nbsp; ![MoCap](https://img.shields.io/badge/MoCap-dc2626?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Ghorbani_SOMA_Solving_Optical_Marker-Based_MoCap_Automatically_ICCV_2021_paper.html) · [arXiv](https://arxiv.org/abs/2110.04431) · [Project](https://soma.is.tue.mpg.de/) · [Code](https://github.com/nghorbani/soma)

<a id="2021-mm"></a>
### MM

- <a id="paper-votehmr"></a>**VoteHMR**: Occlusion-Aware Voting Network for Robust 3D Human Mesh Recovery from Partial Point Clouds<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [DOI](https://doi.org/10.1145/3474085.3475309) · [arXiv](https://arxiv.org/abs/2110.08729) · [Code](https://github.com/hanabi7/VoteHMR)

<a id="2021-arxiv-papers"></a>
### arXiv papers

- <a id="paper-selfsuphmr"></a>**SelfSupHMR**: Self-supervised 3D Human Mesh Recovery from Noisy Point Clouds<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2107.07539)

<p align="right"><a href="#overview">↑ Back to overview</a></p>

---

## 2020

<a id="2020-cvpr"></a>
### CVPR

- <a id="paper-geomfmaps"></a>**GeomFmaps**: Deep Geometric Functional Maps: Robust Feature Learning for Shape Correspondence<br>
  `Related` · [General registration & correspondence](#related-work) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Donati_Deep_Geometric_Functional_Maps_Robust_Feature_Learning_for_Shape_Correspondence_CVPR_2020_paper.html)

- <a id="paper-hpse"></a>**HPSE**: Sequential 3D Human Pose and Shape Estimation from Point Clouds<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Sequential_3D_Human_Pose_and_Shape_Estimation_From_Point_Clouds_CVPR_2020_paper.html)

<a id="2020-eccv"></a>
### ECCV

- <a id="paper-ip-net"></a>**IP-Net**: Combining Implicit Function Learning and Parametric Models for 3D Human Reconstruction<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2007.11432) · [Project](https://virtualhumans.mpi-inf.mpg.de/ipnet/) · [Code](https://github.com/bharat-b7/IPNet)

<a id="2020-neurips"></a>
### NeurIPS

- <a id="paper-loopreg"></a>**LoopReg**: Self-supervised Learning of Implicit Surface Correspondences, Pose and Shape for 3D Human Mesh Registration<br>
  `Core` · [Registration & fitting](#task-registration-fitting) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/2010.12447) · [Project](https://virtualhumans.mpi-inf.mpg.de/loopreg/)

<p align="right"><a href="#overview">↑ Back to overview</a></p>

---

## 2019

<a id="2019-icra"></a>
### ICRA

- <a id="paper-fastdepth"></a>**FastDepth**: Fast Monocular Depth Estimation on Embedded Systems<br>
  `Related` · [RGB view synthesis & depth](#related-work) &nbsp;|&nbsp; ![RGB](https://img.shields.io/badge/RGB-0891b2?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [arXiv](https://arxiv.org/abs/1903.03273)

<a id="2019-cvpr"></a>
### CVPR

- <a id="paper-lbs-ae"></a>**LBS-AE**: LBS Autoencoder: Self-supervised Fitting of Articulated Meshes to Point Clouds<br>
  `Core` · [Registration & fitting](#task-registration-fitting) &nbsp;|&nbsp; ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Li_LBS_Autoencoder_Self-Supervised_Fitting_of_Articulated_Meshes_to_Point_Clouds_CVPR_2019_paper.html)

<a id="2019-iccv"></a>
### ICCV

- <a id="paper-skeletonaware"></a>**SkeletonAware**: Skeleton-Aware 3D Human Shape Reconstruction From Point Clouds<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) ![Scan](https://img.shields.io/badge/Scan-7c3aed?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Jiang_Skeleton-Aware_3D_Human_Shape_Reconstruction_From_Point_Clouds_ICCV_2019_paper.html)

<a id="2019-journal-papers"></a>
### Journal papers

- <a id="paper-dgcnn"></a>**DGCNN**: Dynamic Graph CNN for Learning on Point Clouds — ACM TOG 2019<br>
  `Related` · [General point-cloud models](#related-work) &nbsp;|&nbsp; ![Synthetic](https://img.shields.io/badge/Synthetic-ca8a04?style=flat-square) ![Depth](https://img.shields.io/badge/Depth-16a34a?style=flat-square) &nbsp;·&nbsp; [DOI](https://doi.org/10.1145/3326362) · [arXiv](https://arxiv.org/abs/1801.07829)

## Contributing

Pull requests are welcome.

- Place each paper under its **year** (newest first) and **venue**.
- Within a year, keep venues in chronological order: earlier conferences first, **Journal papers** last.
- Give each paper a unique `paper-shortname` anchor. Put the title on the first line and its scope, primary task, source badges, and resource links on the second, following the template below. Include only links that exist. Journal entries keep `— Journal Abbr Year` after the title.
- Classify human-specific point-cloud, scan, depth/radar, and optical-marker methods or datasets as `Core`; classify RGB-only human methods and general 3D background work as `Related`. Confirm scope and task from the paper or official author resources. Human data used to evaluate a general method does not by itself make that method Core.
- Choose the primary task from the navigation categories. Index Core papers once under that task; place Related papers in the matching background group and state why they belong. Update the task index and its counts when adding or reclassifying a paper.
- Tag every paper with the data-source badge(s) from the legend above, based on the datasets/sensors used in its experiments. Use the gray `Unverified` badge if the source cannot be confirmed.
- Keep experimental data-source tags separate from inference inputs. Do not infer a sensor requirement from training data, supervision, or an internally predicted depth/point-cloud representation.
- Open every link and confirm it resolves. Do not invent venues, years, or URLs.
- Update the paper and scope totals in the header and the yearly totals in Overview when adding a paper, and the venue navigation when adding a year or venue.

Copy this entry format, replace the placeholders, and leave a blank line between papers:

```markdown
- <a id="paper-shortname"></a>**ShortName**: Full Title<br>
  `Core` · [Shape & mesh](#task-shape-mesh) &nbsp;|&nbsp; ![LiDAR](https://img.shields.io/badge/LiDAR-2563eb?style=flat-square) &nbsp;·&nbsp; [Paper](PAPER_URL) · [arXiv](ARXIV_URL) · [Project](PROJECT_URL) · [Code](CODE_URL)
```

<p align="center">
  <a href="https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/issues/new">Suggest a paper</a> &nbsp;·&nbsp;
  <a href="https://github.com/cqs0925/Awesome-PointCloud-Human-Reconstruction/pulls">Submit a pull request</a> &nbsp;·&nbsp;
  <a href="#overview">↑ Back to overview</a>
</p>

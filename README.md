<p align="center">
  <h1 align="center">
  Awesome Diffusion-based SLAM
  </h1>
</p>

This repository contains a curated list of resources addressing SLAM related task employing Diffusion Model, including view/feature correspondences, depth estimation, 3D reconstruction, pose estimation, etc.

If you find some ignored papers, **feel free to [*create pull requests*](https://github.com/KwanWaiPang/Awesome-Transformer-based-SLAM/blob/pdf/How-to-PR.md), or [*open issues*](https://github.com/KwanWaiPang/Awesome-Diffusion-based-SLAM/issues/new)**. 

Contributions in any form to make this list more comprehensive are welcome.

If you find this repositorie is useful, a simple star should be the best affirmation. 😊

Feel free to share this list with others!

# Overview

- [Matching](#Matching)
- [Depth Estimation](#Depth-Estimation)
- [Pose Estimation](#Pose-Estimation)
- [Other Resource](#Other-Resource)


## Matching

or data association, or correspondence

<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`arXiv`|[MATCHA: Towards Matching Anything](https://arxiv.org/pdf/2501.14945)|---|SD+DINOv2|
|2024|`CVPR`|[Sd4match: Learning to prompt stable diffusion model for semantic matching](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_SD4Match_Learning_to_Prompt_Stable_Diffusion_Model_for_Semantic_Matching_CVPR_2024_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/ActiveVisionLab/SD4Match.svg)](https://github.com/ActiveVisionLab/SD4Match)|[website](https://sd4match.active.vision/)|
|2023|`NIPS`|[Emergent correspondence from image diffusion](https://proceedings.neurips.cc/paper_files/paper/2023/file/0503f5dce343a1d06d16ba103dd52db1-Paper-Conference.pdf)|[![Github stars](https://img.shields.io/github/stars/Tsingularity/dift.svg)](https://github.com/Tsingularity/dift)|[website](https://diffusionfeatures.github.io/)<br>DIFT|
|2023|`NIPS`|[A tale of two features: Stable diffusion complements dino for zero-shot semantic correspondence](https://proceedings.neurips.cc/paper_files/paper/2023/file/8e9bdc23f169a05ea9b72ccef4574551-Paper-Conference.pdf)|[![Github stars](https://img.shields.io/github/stars/Junyi42/sd-dino.svg)](https://github.com/Junyi42/sd-dino)|[website](https://sd-complements-dino.github.io/)<br>SD+DINO|
|2023|`NIPS`|[Diffusion hyperfeatures: Searching through time and space for semantic correspondence](https://proceedings.neurips.cc/paper_files/paper/2023/file/942032b61720a3fd64897efe46237c81-Paper-Conference.pdf)|[![Github stars](https://img.shields.io/github/stars/diffusion-hyperfeatures/diffusion_hyperfeatures.svg)](https://github.com/diffusion-hyperfeatures/diffusion_hyperfeatures)|[website](https://diffusion-hyperfeatures.github.io/)<br>DHF|


## Depth Estimation

or 3D reconstruction

<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2025|`arXiv`|[Can Video Diffusion Model Reconstruct 4D Geometry ?](https://arxiv.org/pdf/2503.21082)|---|[website](https://wayne-mai.github.io/publication/sora3r_arxiv_2025/)<br>Sora3R|
|2025|`arXiv`|[Bolt3D: Generating 3D Scenes in Seconds](https://arxiv.org/pdf/2503.14445)|---|[website](https://szymanowiczs.github.io/bolt3d)|
|2025|`arXiv`|[Stable Virtual Camera: Generative View Synthesis with Diffusion Models](https://arxiv.org/pdf/2503.14489)|[![Github stars](https://img.shields.io/github/stars/Stability-AI/stable-virtual-camera.svg)](https://github.com/Stability-AI/stable-virtual-camera) |---|
|2025|`CVPR`|[GenFusion: Closing the Loop between Reconstruction and Generation via Videos](https://arxiv.org/pdf/2503.21219)|[![Github stars](https://img.shields.io/github/stars/Inception3D/GenFusion.svg)](https://github.com/Inception3D/GenFusion)|[website](https://genfusion.sibowu.com/)|
|2025|`CVPR`|[Learning temporally consistent video depth from video diffusion priors](https://arxiv.org/pdf/2406.01493)|[![Github stars](https://img.shields.io/github/stars/jiahao-shao1/ChronoDepth.svg)](https://github.com/jiahao-shao1/ChronoDepth)|[website](https://xdimlab.github.io/ChronoDepth/)| 
|2025|`CVPR`|[Depthcrafter: Generating consistent long depth sequences for open-world videos](https://arxiv.org/pdf/2409.02095)|[![Github stars](https://img.shields.io/github/stars/Tencent/DepthCrafter.svg)](https://github.com/Tencent/DepthCrafter)|[website](https://depthcrafter.github.io/)|
|2025|`CVPR`|[Multi-view Reconstruction via SfM-guided Monocular Depth Estimation](https://arxiv.org/pdf/2503.14483)|[![Github stars](https://img.shields.io/github/stars/zju3dv/Murre.svg)](https://github.com/zju3dv/Murre)|[website](https://zju3dv.github.io/murre/)<br>Murre|
|2025|`CVPR`|[Difix3D+: Improving 3D Reconstructions with Single-Step Diffusion Models](https://arxiv.org/pdf/2503.01774?)|---|[website](https://research.nvidia.com/labs/toronto-ai/difix3d/)|
|2025|`CVPR`|[Align3r: Aligned monocular depth estimation for dynamic videos](https://arxiv.org/pdf/2412.03079)|[![Github stars](https://img.shields.io/github/stars/jiah-cloud/Align3R.svg)](https://github.com/jiah-cloud/Align3R)|---|
|2024|`NIPS`|[Cat3d: Create anything in 3d with multi-view diffusion models](https://arxiv.org/pdf/2405.10314)|---|[website](https://cat3d.github.io/)|
|2024|`CVPR`|[Repurposing Diffusion-Based Image Generators for Monocular Depth Estimation](https://openaccess.thecvf.com/content/CVPR2024/papers/Ke_Repurposing_Diffusion-Based_Image_Generators_for_Monocular_Depth_Estimation_CVPR_2024_paper.pdf)| [![Github stars](https://img.shields.io/github/stars/prs-eth/marigold.svg)](https://github.com/prs-eth/marigold)|[website](https://marigoldmonodepth.github.io/)|
|2024|`ECCV`|[Diffusiondepth: Diffusion denoising approach for monocular depth estimation](https://arxiv.org/pdf/2303.05021)|[![Github stars](https://img.shields.io/github/stars/duanyiqun/DiffusionDepth.svg)](https://github.com/duanyiqun/DiffusionDepth)|[website](https://igl-hkust.github.io/Align3R.github.io/)|
|2024|`arXiv`|[World-consistent Video Diffusion with Explicit 3D Modeling](https://arxiv.org/pdf/2412.01821)|---|[website](https://zqh0253.github.io/wvd/)| 
|2023|`NIPS`|[The surprising effectiveness of diffusion models for optical flow and monocular depth estimation](https://proceedings.neurips.cc/paper_files/paper/2023/file/7c119415672ae2186e17d492e1d5da2f-Paper-Conference.pdf)|---|[website](https://diffusion-vision.github.io/)|
|2023|`arXiv`|[Monocular depth estimation using diffusion models](https://arxiv.org/pdf/2302.14816)|---|[website](https://depth-gen.github.io/)| 
|2023|`arXiv`|[Mvdream: Multi-view diffusion for 3d generation](https://arxiv.org/pdf/2308.16512)|[![Github stars](https://img.shields.io/github/stars/bytedance/MVDream.svg)](https://github.com/bytedance/MVDream)|[website](https://mv-dream.github.io/)|

## Pose Estimation

<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2023|`ICCV`|[Posediffusion: Solving pose estimation via diffusion-aided bundle adjustment](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_PoseDiffusion_Solving_Pose_Estimation_via_Diffusion-aided_Bundle_Adjustment_ICCV_2023_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/facebookresearch/PoseDiffusion.svg)](https://github.com/facebookresearch/PoseDiffusion)|[website](https://posediffusion.github.io/)|


## Other Resource

* Survey for Learning-based VO,VIO,IO：[Paper List](https://github.com/KwanWaiPang/Awesome-Learning-based-VO-VIO)
* Survey for Transformer-based SLAM：[Paper List](https://github.com/KwanWaiPang/Awesome-Transformer-based-SLAM)
* [Awesome-Diffusion-Models](https://github.com/diff-usion/Awesome-Diffusion-Models)
* Some basic paper for Diffusion Model:

<!-- |---|`arXiv`|---|---|---| -->
<!-- [![Github stars](https://img.shields.io/github/stars/***.svg)]() -->

| Year | Venue | Paper Title | Repository | Note |
|:----:|:-----:| ----------- |:----------:|:----:|
|2022|`CVPR`|[High-resolution image synthesis with latent diffusion models](https://openaccess.thecvf.com/content/CVPR2022/papers/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.pdf)|[![Github stars](https://img.shields.io/github/stars/CompVis/latent-diffusion.svg)](https://github.com/CompVis/latent-diffusion)|stable diffusion|
|2021|`NIPS`|[Diffusion models beat gans on image synthesis](https://proceedings.neurips.cc/paper_files/paper/2021/file/49ad23d1ec9fa4bd8d77d02681df5cfa-Paper.pdf)|---|Ablated Diffusion Model(ADM)|
|2020|`ICLR`|[Denoising diffusion implicit models](https://arxiv.org/pdf/2010.02502)|---|DDIM|
|2020|`NIPS`|[Denoising diffusion probabilistic models](https://proceedings.neurips.cc/paper/2020/file/4c5bcfec8584af0d967f1ab10179ca4b-Paper.pdf)|[![Github stars](https://img.shields.io/github/stars/hojonathanho/diffusion.svg)](https://github.com/hojonathanho/diffusion)|DDPM|

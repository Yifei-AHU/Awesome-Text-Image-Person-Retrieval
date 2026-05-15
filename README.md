# Awesome-Text-Image Person Retrieval ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
A collection of deep learning based Text-Image Person Retrieval methods, codes and datasets.

Welcome to add valuable papers and codes, feel free to star and contact me. Keep updating....🚀

## Contents  

1. [Text-Image Person Retrieval](#Text-Image-Person-Retrieval)
2. [Text-Image Aerial Person Retrieval](#Text-Image-Aerial-Person-Retrieval)
3. [Text-RGBT Person Retrieval](#Text-RGBT-Person-Retrieval)

--------------------------------------------------------------------------------------
# Text-Image Person Retrieval
## Datasets
|Dataset                        | Years |    Images   |Captions|   IDs  |
|-------------------------------|-------|-------------|------  |--------|
|[CUHK-PEDES](https://github.com/ShuangLI59/Person-Search-with-Natural-Language-Description)|2017|40,206|80,412|13,003|
|[RSTPReid](https://github.com/NjtechCVLab/RSTPReid-Dataset)|2021|20,505|41010|4,101|
|[ICFG-PEDES](https://github.com/zifyloo/SSAN)|2021|54,522|54,522|4,102|
[UFineBench](https://github.com/Zplusdragon/UFineBench)|2024|26,206|52,412|6,926|

<!-- |[MMPD](https://github.com/jin-s13/MMPD-Dataset)|2024|RGB, LWIR|1200+|1| -->
<!-- [Multi-Spectral Stereo](https://github.com/UkcheolShin/MS2-MultiSpectralStereoDataset), -->

## Papers

### 2026
1. Geometry-Aware Noisy Correspondence Mitigation for Cross-Modal Text-Based Person Retrieval, AAAI 2026, Xinpan Yuan et al., [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/38218)]
2. KPDM: Key Phrase Dynamic Masking for Robust Text-to-Image Person Retrieval, AAAI 2026, Shaofeng You et al., [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/38199)]
3. Hierarchical Prompt Learning for Image- and Text-Based Person Re-Identification, AAAI 2026, Linhan Zhou et al., [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/38380)]
4. Pedestrian-Centric Discriminative and Fine-grained Semantic Mining for Text-based Person Retrieval, WWW 2026, Yuheng Liang et al., [[PDF](https://dl.acm.org/doi/abs/10.1145/3774904.3792134)]
5. Cross-modal Person Retrieval with One-to-Many Relation Modeling, TIFS 2026, Yifei Deng et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/11503671)]
6. Taking Astray Domain Back Home for Single-Source Domain Generalizable Text-to-Image Person Retrieval, TIP 2026, Guan-Nan Dong et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/11433531)]

### 2025
1. Visual perturbation for text-based person search, AAAI 2025, Pengcheng Zhang et al., [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/33091)]
2. DM-Adapter: Domain-Aware Mixture-of-Adapters for Text-Based Person Retrieval, AAAI 2025, Yating Liu et al., [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/32608)]
3. Chat-Driven Text Generation and Interaction for Person Retrieval, EMNLP 2025, Zequn Xie et al., [[PDF](https://aclanthology.org/2025.emnlp-main.266/)]
4. Beyond Walking: A Large-Scale Image-Text Benchmark for Text-based Person Anomaly Search, ICCV 2025, Shuyu Yang et al., [[PDF](https://openaccess.thecvf.com/content/ICCV2025/papers/Yang_Beyond_Walking_A_Large-Scale_Image-Text_Benchmark_for_Text-based_Person_Anomaly_ICCV_2025_paper.pdf)]

### 2024

### 2023

### 2022

--------------------------------------------------------------------------------------

# Text-Image Aerial Person Retrieval
## Datasets

|Dataset                        | Years |Modality     |Images| Classes|Alignment|
|-------------------------------|-------|-------------|------|--------|---------|
|[DroneVehicle](https://github.com/VisDrone/DroneVehicle)|2021|RGB, LWIR|56K|5|Partially|
|[VEDAI](https://downloads.greyc.fr/vedai/)|2014|RGB, NIR|1K|9|Strictly|
|[DVTOD](https://github.com/VDT-2048/DVTOD)|2014|RGB, LWIR|2K|3|Misaligned|
|[NII-CU](https://www.nii-cu-multispectral.org/)|2022|RGB, LWIR|5K|1|Strictly|
|[VTSaR](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10833840)|2024|RGB, LWIR|40K|1|Strictly|
|[RGBT-Tiny](https://github.com/XinyiYing/RGBT-Tiny)|2025|RGB, LWIR|93K|7|Partially|
|ATR-UMOD|2025|RGB, LWIR|13K|11|Partially|
|[MODA](https://github.com/shuaihao-han/MODA)|2026|RGB, NIR|13K|8|Strictly|

## Papers
1. MODA: The First Challenging Benchmark for Multispectral Object Detection in Aerial Images, AAAI 2026, Shuaihao Han et al., [[PDF](https://arxiv.org/abs/2512.09489)][[Code](https://github.com/shuaihao-han/MODA)]

--------------------------------------------------------------------------------------

# Text-RGBT Person Retrieval
## Datasets
|Dataset                        | Years |Modality     |Images| Classes|
|-------------------------------|-------|-------------|------|--------|
|[MFNet](https://www.mi.t.u-tokyo.ac.jp/static/projects/mil_multispectral/)|2017|RGB, LWIR|1.5K|8|
|[PST900](https://github.com/ShreyasSkandanS/pst900_thermal_rgb)|2020|RGB, LWIR|900|5|
|[SemanticRT](https://github.com/jiwei0921/SemanticRT)|2023|RGB, LWIR|11K|13|
|[FMB](https://github.com/JinyuanLiu-CV/SegMiF)|2023|RGB, LWIR|1.5K|14|
|[IDD-AW (Adverse Weather)](https://iddaw.github.io/)|2023|RGB, NIR|5K|18|
|[Caltech Aerial RGBT](https://github.com/aerorobotics/caltech-aerial-rgbt-dataset)|2024|RGB, LWIR|4K|10|

## Papers
1. UniRGB-IR: A Unified Framework for Visible-Infrared Downstream Tasks via Adapter Tuning, ACM MM 2025, Maoxun Yuan et al., [[PDF](https://arxiv.org/abs/2404.17360)][[Code](https://github.com/PoTsui99/UniRGB-IR)]

--------------------------------------------------------------------------------------

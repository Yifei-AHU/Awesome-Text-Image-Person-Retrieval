# Awesome-Text-Image Person Retrieval ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
A collection of deep learning based Text-Image Person Retrieval methods, codes and datasets.

Welcome to add valuable papers and codes, feel free to star and contact me. Keep updating....🚀

<!-- <details>
<summary>Some News: 🆕</summary>

🚀 **2025.08.18 A major update to this repository.** <br>

💎 **2025.07.04 Add one our paper in RGB-T Aerial Object Detection.** <br>

👀 **2025.04.01 Add one dataset in RGB-T-Aerial-Object-Detection (RGBT-Tiny).** <br>

💎 **2025.02.17 Add one dataset-SMOD and some papers in Multispectral Pedestrian Detection.** <br>

👀 **2025.02.12 Add one dataset-MFAD in Multispectral Pedestrian Detection.** <br>

👀 **2024.12.23 Add one TPAMI paper in RGB-T Salient Object Detection.** <br>

💎 **2024.10.31 Add one our paper in Pixel-level Fusion for Detection.** <br>

👀 **2024.10.19 Add one dataset in Multispectral Pedestrian Detection.** <br>

💎 **2024.06.24 Add one our paper and one CVPR paper.** <br>

👀 **2024.05.23 Add one dataset in RGB-T Aerial Object Detection.** <br>

💎 **2024.04.23 Add more papers about RGB-T Salient Object Detection.** <br>

👀 **2024.03.17 Add one CVPR paper.** <br>

💎 **2024.03.15 Add new content about RGB-T Semantic segmentation.** <br>

👀 **2024.03.12 Add one our paper and one CVPR paper.** <br>

</details> -->

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

### Pretrained Generalist Model
1. LoME: LoRA-Driven Multimodal Extractor for  RGB-X Vision Tasks, TCSVT 2026, Yusi Zhang et al., [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11133673)][[Code](https://github.com/zyszxhy/LoME)]
2. M-SpecGene: Generalized Foundation Model for RGBT Multispectral Vision, ICCV 2025, Kailai Zhou et al., [[PDF](https://openaccess.thecvf.com/content/ICCV2025/html/Zhou_M-SpecGene_Generalized_Foundation_Model_for_RGBT_Multispectral_Vision_ICCV_2025_paper.html)][[Code](https://github.com/CalayZhou/M-SpecGene)]
3. UniRGB-IR: A Unified Framework for Visible-Infrared Downstream Tasks via Adapter Tuning, ACM MM 2025, Maoxun Yuan et al., [[PDF](https://arxiv.org/abs/2404.17360)][[Code](https://github.com/PoTsui99/UniRGB-IR)]
4. When Pedestrian Detection Meets Multi-Modal Learning: Generalist Model and Benchmark Dataset, ECCV 2024, Yi Zhang et al., [[PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06487.pdf)][[Code](https://github.com/BubblyYi/MMPedestron)]
5. Mixed Patch Visible-Infrared Modality Agnostic Object Detection, WACV 2025, Heitor R. Medeiros et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10943701)][[Code](https://github.com/heitorrapela/MiPa)]

### Modality Bias
1. UniRGB-IR: A Unified Framework for Visible-Infrared Downstream Tasks via Adapter Tuning, ACM MM 2025, Maoxun Yuan et al., [[PDF](https://arxiv.org/abs/2404.17360)][[Code](https://github.com/PoTsui99/UniRGB-IR)]
2. Modality Translation for Object Detection Adaptation Without Forgetting Prior Knowledge, ECCV 2024, Medeiros, Heitor Rapela et al., [[PDF](https://eccv.ecva.net/virtual/2024/poster/816)][[Code](https://github.com/heitorrapela/ModTr)]
3. AMFD: Distillation via Adaptive Multimodal Fusion for Multispectral Pedestrian Detection, Arxiv 2024, Zizhao Chen et al., [[PDF](https://arxiv.org/pdf/2405.12944)][[Code](https://github.com/bigD233/AMFD)]
4. D3T: Distinctive Dual-Domain Teacher Zigzagging Across RGB-Thermal Gap for Domain-Adaptive Object Detection, CVPR 2024, Dinh Phat Do et al., [[PDF](https://arxiv.org/pdf/2403.09359.pdf)][[Code](https://github.com/EdwardDo69/D3T)]
5. Causal Mode Multiplexer: A Novel Framework for Unbiased Multispectral Pedestrian Detection, CVPR 2024, Taeheon Kim et al. [[PDF](https://arxiv.org/pdf/2403.01300.pdf)][[Code](https://github.com/ssbin0914/Causal-Mode-Multiplexer)]
6. HalluciDet: Hallucinating RGB Modality for Person Detection Through Privileged Information, WACV 2024, Medeiros, Heitor Rapela et al., [[PDF](https://openaccess.thecvf.com/content/WACV2024/papers/Medeiros_HalluciDet_Hallucinating_RGB_Modality_for_Person_Detection_Through_Privileged_Information_WACV_2024_paper.pdf)][[Code](https://github.com/heitorrapela/HalluciDet)]
7. Unsupervised Domain Adaptation for Multispectral Pedestrian Detection, CVPR 2019 Workshop , Dayan Guan et al.[[PDF](https://arxiv.org/abs/1904.03692)][[Code](https://github.com/dayanguan/unsupervised_multispectral_pedestrian_detectio)]
8. Pedestrian detection with unsupervised multispectral feature learning using deep neural networks, Information Fusion 2019, Y. Cao et al. Information Fusion 2019, [[PDF](https://www.sciencedirect.com/science/article/pii/S1566253517305948)][[Code](https://github.com/Huaqing-lucky/unsupervised_multispectral_pedestrian_detection)]
9. Learning crossmodal deep representations for robust pedestrian detection, CVPR 2017, D. Xu et al.[[PDF](https://openaccess.thecvf.com/content_cvpr_2017/papers/Xu_Learning_Cross-Modal_Deep_CVPR_2017_paper.pdf)][[Code](https://github.com/danxuhk/CMT-CNN)]

### Pixel-level Fusion for Detection
1. CtrlFuse: Mask-Prompt Guided Controllable Infrared and Visible Image Fusion, AAAI 2026, Yiming Sun et al., [[PDF](https://arxiv.org/pdf/2601.08619)][[Code](https://github.com/Sevryy/CtrlFuse)]
2. DDFD: Diffusion-Based Denoising Fusion for Object Detection in Infrared-Visible Images, ACM MM 2025, Min Dang et al., [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3755183)]
3. LUT-Fuse: Towards Extremely Fast Infrared and Visible Image Fusion via Distillation to Learnable Look-Up Tables, ICCV 2025, Haodong Zhu et al., [[PDF](https://openaccess.thecvf.com/content/ICCV2025/papers/Yi_LUT-Fuse_Towards_Extremely_Fast_Infrared_and_Visible_Image_Fusion_via_ICCV_2025_paper.pdf)][[Code](https://github.com/zyb5/LUT-Fuse)]
4. DCEvo: Discriminative Cross-Dimensional Evolutionary Learning for Infrared and Visible Image Fusion, CVPR 2025, Jinyuan Liu et al. [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Liu_DCEvo_Discriminative_Cross-Dimensional_Evolutionary_Learning_for_Infrared_and_Visible_Image_CVPR_2025_paper.pdf)][[Code](https://github.com/Beate-Suy-Zhang/DCEvo)]
5. Task-driven Image Fusion with Learnable Fusion Loss, CVPR 2025, Haowen Bai et al., [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Bai_Task-driven_Image_Fusion_with_Learnable_Fusion_Loss_CVPR_2025_paper.pdf)][[Code](https://github.com/HaowenBai/TDFusion)]
6. DANet: A Dual-Branch Framework With Diffusion-Integrated Autoencoder for Infrared–Visible Image Fusion, TIM 2025,  Chengyi Pan et al. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10919151)][[Code](https://github.com/Pancy9476/DANet)]
7. RT-X Net: RGB-Thermal cross attention network for Low-Light Image Enhancement, ICIP 2025, Raman Jha et al., [[PDF](https://arxiv.org/abs/2505.24705)][[Code](https://github.com/jhakrraman/rt-xnet)]
8. SFDFusion: An Efficient Spatial-Frequency Domain Fusion Network for Infrared and Visible Image Fusion, ECAI 2024, KunHu et al. [[PDF](https://arxiv.org/pdf/2410.22837)][[Code](https://github.com/lqz2/SFDFusion)]
9. E2E-MFD: Towards End-to-End Synchronous Multimodal Fusion Detection, Neurips 2024, Jiaqing Zhang et al. [[PDF](https://arxiv.org/abs/2403.09323)][[Code]( https://github.com/icey-zhang/EfficientMFD)]
10. Multi-modal Gated Mixture of Local-to-Global Experts for Dynamic Image Fusion, ICCV 2023, Yiming Sun et al.[[PDF](https://arxiv.org/abs/2302.01392)][[Code]( https://github.com/SunYM2020/MoE-Fusion)]
11. MetaFusion : Infrared and Visible Image Fusion via Meta-Feature Embedding from Object Detection, CVPR 2023, Wenda Zhao et al. [[PDF](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_MetaFusion_Infrared_and_Visible_Image_Fusion_via_Meta-Feature_Embedding_From_CVPR_2023_paper.pdf)][[Code](https://github.com/wdzhao123/MetaFusion)]
12. Locality guided cross-modal feature aggregation and pixel-level fusion for multispectral pedestrian detection, Information Fusion 2022, Yanpeng Cao et al. [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1566253522000549)]
13. Target-aware Dual Adversarial Learning and a Multi-scenario Multi-Modality Benchmark to Fuse Infrared and Visible for Object Detection, CVPR 2022, Jinyuan Liu et al.[[PDF](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Target-Aware_Dual_Adversarial_Learning_and_a_Multi-Scenario_Multi-Modality_Benchmark_To_CVPR_2022_paper.pdf)][[Code](https://github.com/dlut-dimt/TarDAL)]
14. DetFusion: A Detection-driven Infrared and Visible Image Fusion Network, ACM Multimedia 2022, Yiming Sun et al. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3503161.3547902)][[Code](https://github.com/SunYM2020/DetFusion)]

### Illumination Aware
1. Efficient Multispectral Object Detection with attentive feature aggregation leveraging zero-shot implicit illumination guidance, Information Fusion 2025, Zhongxia Xiong et al., [[PDF](https://www.sciencedirect.com/science/article/pii/S1566253525000120)]
2. EI<sup>2</sup>Det: Edge-Guided Illumination-Aware Interactive Learning for Visible-Infrared Object Detection, TCSVT 2025, Ke Hu et al., [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10877920)] [[Code](https://github.com/hukefy/EI2Det)]
3. RGB-X Object Detection via Scene-Specific Fusion Modules, WACV 2024, Sri Aditya Deevi et al. [[PDF](https://arxiv.org/abs/2310.19372)] [[Code](https://github.com/dsriaditya999/RGBXFusion)]
4. Illumination-Guided RGBT Object Detection With Inter- and Intra-Modality Fusion, IEEE Transactions on Instrumentation and Measurement 2023, Yan Zhang et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/10057437/)][[Code](https://github.com/NNNNerd/Triple-I-Net-TINet)]
5. IGT: Illumination-guided RGB-T object detection with transformers, Knowledge-Based Systems 2023, Keyu Chen et al. [[PDF](https://www.sciencedirect.com/science/article/pii/S0950705123001739)]
6. Task-conditioned Domain Adaptation for Pedestrian Detection in Thermal Imagery, ECCV 2020, My Kieu et al. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670545.pdf)][[Code](https://github.com/mrkieumy/task-conditioned)]
7. Improving Multispectral Pedestrian Detection by Addressing Modality Imbalance Problems, ECCV 2020, Kailai Zhou et al. [[PDF](https://arxiv.org/pdf/2008.03043.pdf)][[Code](https://github.com/CalayZhou/MBNet)]
8. Fusion of Multispectral Data Through Illumination-aware Deep Neural Networks for Pedestrian Detection, Information Fusion 2019, Dayan Guan et al.[[PDF](https://arxiv.org/abs/1802.09972)][[Code](https://github.com/dayanguan/illumination-aware_multispectral_pedestrian_detection/)]
9.  Illumination-aware Faster R-CNN for Robust Multispectral Pedestrian Detection, Pattern Recognition 2018, Chengyang Li et al.[[PDF](https://www.sciencedirect.com/science/article/pii/S0031320318303030)][[Code](https://github.com/Li-Chengyang/IAF-RCNN)]


### Feature Alignment
1.  Contextually-Guided State Space Fusion for Misaligned Multi-Spectral Object Detection, ACMMM 2025, Guyue Jin et al., [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3754550)]
2.  CF-Deformable DETR: An End-to-End Alignment-Free Model for Weakly Aligned Visible-Infrared Object Detection,  IJCAI 2024, Haolong Fu et al. [[PDF](https://www.ijcai.org/proceedings/2024/0084.pdf)][[Code](https://github.com/116508/CF-Deformable-DETR)]
3. C<sup>2</sup>Former: Calibrated and Complementary Transformer for RGB-Infrared Object Detection, TGRS 2024, Maoxun Yuan et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/10472947)][[Code](https://github.com/yuanmaoxun/C2Former)]
4. Cross-Modality Proposal-guided Feature Mining for Unregistered RGB-Thermal Pedestrian Detection, TMM 2024, Chao Tian et al. [[PDF](https://ieeexplore.ieee.org/document/10382506)]
5. Multi-Modal Feature Pyramid Transformer for RGB-Infrared Object Detection, TITS 2023, Yaohui Zhu et al., [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10105844)]
6. Attentive Alignment Network for Multispectral Pedestrian Detection, ACM MM 2023, Nuo Chen et al. [[PDF](https://dl.acm.org/doi/10.1145/3581783.3613444)]
7. Towards Versatile Pedestrian Detector with Multisensory-Matching and Multispectral Recalling Memory, AAAI2022, Jung Uk Kim et al. [[PDF](https://www.aaai.org/AAAI22Papers/AAAI-8768.KimJ.pdf)]
8. Mlpd: Multi-label pedestrian detector in multispectral domain, RAL 2021, Jiwon Kim et al. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9496129)][[Code](https://github.com/sejong-rcv/MLPD-Multi-Label-Pedestrian-Detection)]
9. Weakly Aligned Feature Fusion for Multimodal Object Detection, TNNLS 2021, Lu Zhang et al. [[PDF](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5962385)]
10. Improving Multispectral Pedestrian Detection by Addressing Modality Imbalance Problems, ECCV 2020, Kailai Zhou et al. [[PDF](https://arxiv.org/pdf/2008.03043.pdf)][[Code](https://github.com/CalayZhou/MBNet)]
11. Weakly Aligned Cross-Modal Learning for Multispectral Pedestrian Detection, ICCV 2019, Lu Zhang et al.[[PDF](https://arxiv.org/abs/1901.02645)][[Code](https://github.com/luzhang16/AR-CNN)]
12. Multispectral Pedestrian Detection via Simultaneous Detection and Segmentation, BMVC 2018, Chengyang Li et al.[[PDF](https://arxiv.org/abs/1808.04818)][[Code](https://github.com/Li-Chengyang/MSDS-RCNN)]

### Modality Translation and  Knowledge Distillation 
1. SAM-Guided Semantic Knowledge Fusion for Visible-Infrared Object Detection, ACM MM 2025,  Ting Li et al., [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3755718)][[Code]( https://github.com/liting1018/SemFusion)]
2. Multimodal Decomposed Distillation with Instance Alignment and Uncertainty Compensation for Thermal Object Detection, ACM MM 2025, Yanfeng Liu et al. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3755841)][[Code](https://github.com/lyf0801/DecomKD)]
3. Rethinking Multi-modal Object Detection from the Perspective of Mono-Modality Feature Learning, ICCV 2025, Tianyi Zhao et al. [[PDF](https://arxiv.org/abs/2503.11780)][[Code](https://github.com/Zhao-Tian-yi/M2D-LIF)]
4. Pseudo Visible Feature Fine-Grained Fusion for Thermal Object Detection, CVPR 2025, Ting Li et al. [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_Pseudo_Visible_Feature_Fine-Grained_Fusion_for_Thermal_Object_Detection_CVPR_2025_paper.pdf][[Code](https://github.com/liting1018/PFGF)]
5. Modality Translation for Object Detection Adaptation Without Forgetting Prior Knowledge, ECCV 2024, Heitor R. Medeiros et al.,[[PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/12401.pdf)][[Code](https://github.com/heitorrapela/ModTr)]
6. TIRDet: Mono-Modality Thermal InfraRed Object Detection Based on Prior Thermal-To-Visible Translation, ACM MM 2023, Zeyu Wang et al. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3581783.3613849)][[Code](https://github.com/zeyuwang-zju/TIRDet)]
7. Towards Versatile Pedestrian Detector with Multisensory-Matching and Multispectral Recalling Memory, AAAI 2022, Kim et al. [[PDF](https://www.aaai.org/AAAI22Papers/AAAI-8768.KimJ.pdf)]
8. Robust Thermal Infrared Pedestrian Detection By Associating Visible Pedestrian Knowledge, ICASSP 2022, Sungjune Park et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/9746886)]
9. Low-cost Multispectral Scene Analysis with Modality Distillation, Zhang Heng et al. [[PDF](https://openaccess.thecvf.com/content/WACV2022/papers/Zhang_Low-Cost_Multispectral_Scene_Analysis_With_Modality_Distillation_WACV_2022_paper.pdf)]
10. Task-conditioned Domain Adaptation for Pedestrian Detection in Thermal Imagery, ECCV 2020, My Kieu et al. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670545.pdf)][[Code](https://github.com/mrkieumy/task-conditioned)]
11. Deep Cross-modal Representation Learning and Distillation for Illumination-invariant Pedestrian Detection, TCSCT 2021, T. Liu et al. [[PDF](https://ieeexplore.ieee.org/document/9357413/)]


### Adversarial Attack and Defense
1. CDUPatch: Color-Driven Universal Adversarial Patch Attack for Dual-Modal Visible-Infrared Detectors,  Jiahuan Long et al., ACM MM 2025, [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3755188)]
2. PAIF: Perception-Aware Infrared-Visible Image Fusion for Attack-Tolerant Semantic Segmentation, ACM MM 2023, [[PDF](https://dl.acm.org/doi/abs/10.1145/3581783.3611928)][[Code](https://github.com/LiuZhu-CV/PAIF)]

### Fusion Architecture
1. Multispectral State-Space Feature Fusion: Bridging Shared and Cross-Parametric Interactions for Object Detection, Jifeng Shen et al. Information Fusion 2026, [[PDF](https://www.sciencedirect.com/science/article/pii/S1566253525009571)][[Code](https://github.com/61s61min/MS2Fusion.git)]
2. IRDFusion: Iterative relation-map difference guided feature fusion for multispectral object detection, Jifeng Shen et al. Pattern Recognition 2026 [[PDF](https://www.sciencedirect.com/science/article/pii/S0031320326001548)][[Code](https://github.com/61s61min/IRDFusion)]
3. Removal Then Selection: A Coarse-to-Fine Fusion Perspective for RGB-Infrared Object Detection, TITS 2025, Tianyi Zhao et al. [[PDF](https://ieeexplore.ieee.org/document/11278552)][[Code]( https://github.com/Zhao-Tian-yi/RSDet.git)][[知乎](https://zhuanlan.zhihu.com/p/679289837)]
4. WaveMamba: Wavelet-Driven Mamba Fusion for RGB-Infrared Object Detection, ICCV 2025,  Haodong Zhu et al., [[PDF](https://openaccess.thecvf.com/content/ICCV2025/papers/Zhu_WaveMamba_Wavelet-Driven_Mamba_Fusion_for_RGB-Infrared_Object_Detection_ICCV_2025_paper.pdf)][[Code](https://github.com/EhanDong/WaveMamba)]
5. Rethinking Early-Fusion Strategies for Improved Multispectral Object Detection, TIV 2025, Xue Zhang et al., [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10681477)][[Code](https://github.com/XueZ-phd/Efficient-RGB-T-Early-Fusion-Detection)]
6. Specificity-Guided Cross-Modal Feature Reconstruction for RGB-Infrared Object Detection, TITS 2024,  Xiaoyu Sun et al., [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10759534)][[Code](https://github.com/SXYSUOSUO/SCFR)]
7. DAMSDet: Dynamic Adaptive Multispectral Detection Transformer with Competitive Query Selection and Adaptive Feature Fusion, ECCV 2024, Junjie Guo et al., [[PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03984.pdf)][[Code](https://github.com/gjj45/DAMSDet)]
8. TFDet: Target-Aware Fusion for RGB-T Pedestrian Detection, TNNLS 2024, Xue Zhang et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10645696)][[Code](https://github.com/XueZ-phd/TFDet.git)]
9. Frequency Mining and Complementary Fusion Network for RGB-Infrared Object Detection, GRSL 2024, Yangfeixiao Liu et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10644032)]
10. M2FNet: Mask-guided Multi-level Fusion for RGB-T Pedestrian Detection, TMM 2024, Xiangyang Li et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10478590)]
11. ICAFusion: Iterative cross-attention guided feature fusion for multispectral object detection, Pattern Recognition 2024, Shen Jifeng et al. [[PDF](https://www.sciencedirect.com/science/article/pii/S0031320323006118)][[Code](https://github.com/chanchanchan97/ICAFusion)]
12. Improving RGB-infrared object detection with cascade alignment-guided transformer, Information Fusion 2024, Maoxun Yuan et al. [[PDF](https://www.sciencedirect.com/science/article/pii/S1566253524000241)]
13. Multispectral Object Detection via Cross-Modal Conflict-Aware Learning, ACM MM 2023, Xiao He et al. [[PDF](https://dl.acm.org/doi/10.1145/3581783.3612651)][[Code](https://github.com/hexiao0275/CALNet-Dronevehicle)]
14. Stabilizing Multispectral Pedestrian Detection with Evidential Hybrid Fusion, TCSVT 2023, Li Qing et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/10225383)]
15. Multimodal Object Detection by Channel Switching and Spatial Attention, CVPRW 2023, Yue Cao et al. [[PDF](https://openaccess.thecvf.com/content/CVPR2023W/PBVS/papers/Cao_Multimodal_Object_Detection_by_Channel_Switching_and_Spatial_Attention_CVPRW_2023_paper.pdf)]
16. Multi-Modal Feature Pyramid Transformer for RGB-Infrared Object Detection, TITS 2023, Yaohui Zhu et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/10105844)]
17. Multiscale Cross-modal Homogeneity Enhancement and Confidence-aware Fusion for Multispectral Pedestrian Detection, TMM 2023, Ruimin Li et al. [[PDF](https://ieeexplore.ieee.org/document/10114594)][[Code](https://github.com/RimXidian/MCHE-CF-for-Multispectral-Pedestrian-Detection)]
18. HAFNet: Hierarchical Attentive Fusion Network for Multispectral Pedestrian Detection, Remote Sensing 2023, Peiran Peng et al. [[PDF](https://www.mdpi.com/2072-4292/15/8/2041)]
19. Multimodal Object Detection via Probabilistic Ensembling, ECCV2022, Yi-Ting Chen et al. [[PDF](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136690139.pdf)][[Code](https://github.com/Jamie725/Multimodal-Object-Detection-via-Probabilistic-Ensembling)]
20. Learning a Dynamic Cross-Modal Network for Multispectral Pedestrian Detection, ACM Multimedia 2022, Jin Xie et al. [[PDF](https://dl.acm.org/doi/abs/10.1145/3503161.3547895)]
21. Confidence-aware Fusion using Dempster-Shafer Theory for Multispectral Pedestrian Detection, TMM 2022, Qing Li et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/9739079)]
22. Attention-Guided Multi-modal and Multi-scale Fusion for Multispectral Pedestrian Detection, PRCV 2022, Wei Bao et al. [[PDF](https://link.springer.com/chapter/10.1007/978-3-031-18907-4_30)]
23. Improving RGB-Infrared Pedestrian Detection by Reducing Cross-Modality Redundancy, ICIP2022, Qingwang Wang et al.  [[PDF](https://www.mdpi.com/2072-4292/14/9/2020)]
24. Spatio-contextual deep network-based multimodal pedestrian detection for autonomous driving, IEEE Transactions on Intelligent Transportation Systems, Kinjal Dasgupta et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/9706418)]
25. Adopting the YOLOv4 Architecture for Low-LatencyMultispectral Pedestrian Detection in Autonomous Driving, Sensors 2022, Kamil Roszyk et al. [[PDF](https://www.mdpi.com/1424-8220/22/3/1082)]
26. Deep Active Learning from Multispectral Data Through Cross-Modality Prediction Inconsistency, ICIP2021, Heng Zhang et al.[[PDF](https://ieeexplore.ieee.org/document/9506322)]
27. Attention Fusion for One-Stage Multispectral Pedestrian Detection, Sensors 2021, Zhiwei Cao et al. [[PDF](https://www.mdpi.com/1424-8220/21/12/4184)]
28. Uncertainty-Guided Cross-Modal Learning for Robust Multispectral Pedestrian Detection, IEEE Transactions on Circuits and Systems for Video Technology 2021, Jung Uk Kim et al. [[PDF](https://ieeexplore.ieee.org/document/9419080)]
29. Deep Cross-modal Representation Learning and Distillation for Illumination-invariant Pedestrian Detection, IEEE Transactions on Circuits and Systems for Video Technology 2021, T. Liu et al. [[PDF](https://ieeexplore.ieee.org/document/9357413/)]
30. Guided Attentive Feature Fusion for Multispectral Pedestrian Detection, WACV 2021, Heng Zhang et al. [[PDF](https://openaccess.thecvf.com/content/WACV2021/papers/Zhang_Guided_Attentive_Feature_Fusion_for_Multispectral_Pedestrian_Detection_WACV_2021_paper.pdf)]
31. Anchor-free Small-scale Multispectral Pedestrian Detection, BMVC 2020, Alexander Wolpert et al. [[PDF](https://arxiv.org/abs/2008.08418)][[Code](https://github.com/HensoldtOptronicsCV/MultispectralPedestrianDetection)]
32. Multispectral Fusion for Object Detection with Cyclic Fuse-and-Refine Blocks, ICIP 2020, Heng Zhang et al. [[PDF](https://hal.archives-ouvertes.fr/hal-02872132/file/icip2020.pdf)]
33. Improving Multispectral Pedestrian Detection by Addressing Modality Imbalance Problems, ECCV 2020, Kailai Zhou et al. [[PDF](https://arxiv.org/pdf/2008.03043.pdf)][[Code](https://github.com/CalayZhou/MBNet)]
34. Anchor-free Small-scale Multispectral Pedestrian Detection, BMVC 2020, Alexander Wolpert et al. [[PDF](https://arxiv.org/abs/2008.08418)][[Code](https://github.com/HensoldtOptronicsCV/MultispectralPedestrianDetection)]
35. Weakly Aligned Cross-Modal Learning for Multispectral Pedestrian Detection, ICCV 2019, Lu Zhang et al. [[PDF](https://arxiv.org/abs/1901.02645)][[Code](https://github.com/luzhang16/AR-CNN)]
36. Box-level Segmentation Supervised Deep Neural Networks for Accurate and Real-time Multispectral Pesdestrian Detecion, ISPRS Journal of Photogrammetry and Remote Sensing 2019, Yanpeng Cao et al.[[PDF](https://arxiv.org/abs/1902.05291)][[Code](https://github.com/dayanguan/realtime_multispectral_pedestrian_detection)]
37. Cross-modality interactive attention network for multispectral pedestrian detection, Information Fusion 2019, Lu Zhang et al.[[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1566253518304111)][[Code](https://github.com/luzhang16/CIAN)]
38. Pedestrian detection with unsupervised multispectral feature learning using deep neural networks, Information Fusion 2019,  Cao, Yanpeng et al.[[PDF](https://www.sciencedirect.com/science/article/pii/S1566253517305948)]
39. Multispectral Pedestrian Detection via Simultaneous Detection and Segmentation, BMVC 2018, Chengyang Li et al.[[PDF](https://arxiv.org/abs/1808.04818)][[Code](https://github.com/Li-Chengyang/MSDS-RCNN)][[Project Link](https://li-chengyang.github.io/home/MSDS-RCNN/)]
40. Unified Multi-spectral Pedestrian Detection Based on Probabilistic Fusion Networks, Pattern Recognition 2018, Kihong Park et al.[[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0031320318300906)]
41. Multispectral Deep Neural Networks for Pedestrian Detection, BMVC 2016, Jingjing Liu et al.[[PDF](https://arxiv.org/abs/1611.02644)][[Code](https://github.com/denny1108/multispectral-pedestrian-py-faster-rcnn)]
42. Multispectral Pedestrian Detection Benchmark Dataset and Baseline, 2015, Soonmin Hwang et al.[[PDF](https://soonminhwang.github.io/rgbt-ped-detection/misc/CVPR15_Pedestrian_Benchmark.pdf)][[Code](https://github.com/SoonminHwang/rgbt-ped-detection)]

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
2. SM3Det: A Unified Model for Multi-Modal Remote Sensing Object Detection, AAAI 2026, Yuxuan Li et al., [[PDF](https://arxiv.org/pdf/2412.20665)][[Code](https://github.com/zcablii/SM3Det)]
3. IGIANet: Illumination Guided Implicit Alignment Network for Infrared–Visible
UAVDetection, AAAI 2026, Xiangqi Chen et al., [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/37298)]
4. Contextually-Guided State Space Fusion for Misaligned Multi-Spectral Object Detection, ACMMM 2025, Guyue Jin et al., [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3754550)]
5. Fusion Meets Diverse Conditions: A High-diversity Benchmark and Baseline for UAV-based Multimodal Object Detection with Condition Cues, ICCV 2025, Chen Chen et al., [[PDF](https://openaccess.thecvf.com/content/ICCV2025/papers/Chen_Fusion_Meets_Diverse_Conditions_A_High-diversity_Benchmark_and_Baseline_for_ICCV_2025_paper.pdf)]
6. Rethinking Multi-modal Object Detection from the Perspective of Mono-Modality Feature Learning, ICCV 2025, Tianyi Zhao et al., [[PDF](https://arxiv.org/abs/2503.11780)][[Code](https://github.com/Zhao-Tian-yi/M2D-LIF)]
7.  Detection-Friendly Nonuniformity Correction: A Union Framework for Infrared UAV Target Detection, CVPR 2025, Houzhang Fang et al. [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Fang_Detection-Friendly_Nonuniformity_Correction_A_Union_Framework_for_Infrared_UAV_Target_CVPR_2025_paper.pdf)][[Code](https://github.com/IVPLaboratory/UniCD)]
8. SFFR: Spatial-Frequency Feature Reconstruction for Multispectral Aerial Object Detection, TGRS 2025, Xin Zuo et al. [[PDF](https://ieeexplore.ieee.org/document/11240218/)][[Code](https://github.com/qchenyu1027/SFFR)]
9. Reflectance-Guided Progressive Feature Alignment Network for All-Day UAV Object Detection, TGRS 2025, Zhicheng Zhao et al., [[PDF](https://ieeexplore.ieee.org/document/11017749)][[Code](https://github.com/uavdet/RGFNet)]
10. Visible-Infrared Image Alignment For Unmanned Aerial Vehicles: Benchmark and New Baseline, TGRS 2025, Zhinan Gao et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10854690)][[Code](https://github.com/gaozhinanjiu/UAVmatch)]
11. LAST-Net: Local Adaptivity Spatial Transformer Network for Multiobject Detection in UAV Remote Sensing Thermal Infrared Imagery, TGRS 2025, Min Li et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10972092)]
12. Visible-Thermal Tiny Object Detection: A Benchmark Dataset and Baselines, TPAMI 2025, Xinyi Ying et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10914515)][[Code](https://github.com/XinyiYing/RGBT-Tiny)]
13. Aerial image object detection based on RGB-Infrared multi-branch progressive fusion, TGRS 2025, Kewei Liu et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10933976)]
14. Dual Dynamic Cross-modal Interaction Network for Multimodal Remote Sensing Object Detection, TGRS 2025, Wei Bao et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10843244)][[Code](https://github.com/Drew-bw/DDCINet)]
15. Unified multimodal fusion transformer for few shot object detection for remote sensing images, Information Fusion 2024, Abdullah Azeem et al., [[PDF](https://www.sciencedirect.com/science/article/pii/S1566253524002860)]
16. SM3Det: A Unified Model for Multi-Modal Remote Sensing Object Detection, Yuxuan Li et al., Arxiv 2025, [[PDF](https://arxiv.org/pdf/2412.20665)][[Code](https://github.com/zcablii/SM3Det)]
17. CCLDet: A Cross-Modality and Cross-Domain Low-Light Detector, Xiping Shang et al., TITS 2025, [[PDF](https://ieeexplore.ieee.org/abstract/document/10844996)]
18. Dual-Dynamic Cross-Modal Interaction Network for Multimodal Remote Sensing Object Detection, TGRS 2025, Wei Bao et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10843244)][[Code](https://github.com/Drew-bw/DDCINet)]
19. DAMSDet: Dynamic Adaptive Multispectral Detection Transformer with Competitive Query Selection and Adaptive Feature Fusion, ECCV 2024, Junjie Guo et al., [[PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03984.pdf)][[Code](https://github.com/gjj45/DAMSDet)]
20. Cross Teaching-Enhanced Multi-spectral Remote Sensing Object Detection with Transformer, TGRS 2024, Jiahe Zhu et al., [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10770223)]
21. Cross-Modal Oriented Object Detection of UAV Aerial Images Based on Image Feature, TGRS 2024, Huiying Wang et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10440361)]
22. CMDistill: Cross-modal Distillation Framework for UAV Image Object Detection, JSTAR 2024, Xiaozhong Tong et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10715640)]
23. Multimodal Feature-Guided Pretraining for RGB-T Perception, JSTAR 2024, Junlin Ouyang et al., [[PDF](https://ieeexplore.ieee.org/document/10663834)]
24. Mask-Guided Mamba Fusion for Drone-based Visible-Infrared Vehicle Detection, TGRS 2024, Simiao Wang et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10659747)]
25. Low-rank Multimodal Remote Sensing Object Detection with Frequency Filtering Experts, TGRS 2024, Xu Sun et al., [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10643097)][[Code](https://github.com/cq100/LF-MDet)]
26. Weakly Misalignment-free Adaptive Feature Alignment for UAVs-based Multimodal Object Detection, CVPR 2024, Chen Chen et al., [[PDF](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_Weakly_Misalignment-free_Adaptive_Feature_Alignment_for_UAVs-based_Multimodal_Object_Detection_CVPR_2024_paper.pdf)]
27. Misaligned Visible-Thermal Object Detection: A Drone-based Benchmark and Baseline, TIV 2024, Kechen Song, [[PDF](https://ieeexplore.ieee.org/abstract/document/10522939/authors)][[Code](https://github.com/VDT-2048/DVTOD)]
28. C<sup>2</sup>Former: Calibrated and Complementary Transformer for RGB-Infrared Object Detection, TGRS 2024, Maoxun Yuan et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/10472947)][[Code](https://github.com/yuanmaoxun/C2Former)]
29. ICAFusion: Iterative cross-attention guided feature fusion for multispectral object detection, Pattern Recognition 2024, Shen Jifeng et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/10225383)][[Code](https://github.com/chanchanchan97/ICAFusion)]
30. Improving RGB-infrared object detection with cascade alignment-guided transformer, Information Fusion 2024, Maoxun Yuan et al. [[PDF](https://www.sciencedirect.com/science/article/pii/S1566253524000241)]
31. Multispectral Object Detection via Cross-Modal Conflict-Aware Learning, ACM MM 2023, Xiao He et al. [[PDF](https://dl.acm.org/doi/10.1145/3581783.3612651)][[Code](https://github.com/hexiao-cs/CALNet-Dronevehicle)]
32. LRAF-Net: Long-Range Attention Fusion Network for Visible–Infrared Object Detection, TNNLS 2023, Haolong Fu et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/10144688)]
33. Modality Balancing Mechanism for RGB-Infrared Object Detection in Aerial Image, PRCV 2023, Weibo Cai er al., [[PDF](https://link.springer.com/chapter/10.1007/978-981-99-8555-5_7)]
34. RGB-Infrared Multi-Modal Remote Sensing Object Detection Using CNN and Transformer Based Feature Fusion, IGARSS 2023, Tao Tian et al., [[PDF](https://ieeexplore.ieee.org/document/10282173)]
35. GF-Detection: Fusion with GAN of Infrared and Visible Images for Vehicle Detection at Nighttime, Remote Sensing 2022, Peng Gao et al. [[PDF](https://www.mdpi.com/2072-4292/14/12/2771)]
36. Cross-modality attentive feature fusion for object detection in multispectral remote sensing imagery, Pattern Recognition, Qingyun Fang et al. [[PDF](https://www.sciencedirect.com/science/article/pii/S0031320322002679)]
37. Translation, Scale and Rotation: Cross-Modal Alignment Meets RGB-Infrared Vehicle Detection, ECCV 2022, Maoxun Yuan et al. [[PDF](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136690501.pdf)]
38. Drone-based RGB-Infrared Cross-Modality Vehicle Detection via Uncertainty-Aware Learning, TCSVT 2022, Yiming Sun [[PDF](https://ieeexplore.ieee.org/abstract/document/9759286)][[Code](https://github.com/SunYM2020/UA-CMDet)]
39. Improving RGB-Infrared Object Detection by Reducing Cross-Modality Redundancy, Remote Sensing 2022, Qingwang Wang et al. [[PDF](https://www.mdpi.com/2072-4292/14/9/2020)]

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
2.  StitchFusion: Weaving Any Visual Modalities to Enhance Multimodal Semantic Segmentation, ACMMM 2025, Bingyu Li et al., [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3755110)][[Code](https://github.com/LiBingyu01/StitchFusion)]
3.  AMDANet: Attention-Driven Multi-Perspective Discrepancy Alignment for RGB-Infrared Image Fusion and Segmentation, ICCV 2025,  Haifeng Zhong et al., [[PDF](https://openaccess.thecvf.com/content/ICCV2025/papers/Zhong_AMDANet_Attention-Driven_Multi-Perspective_Discrepancy_Alignment_for_RGB-Infrared_Image_Fusion_and_ICCV_2025_paper.pdf)][[Code](https://github.com/Zhonghaifeng6/AMDANet)]
4. Every SAMDrop Counts: Embracing Semantic Priors for Multi-Modality Image Fusion and Beyond, CVPR 2025, Guanyao Wu et al., [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Wu_Every_SAM_Drop_Counts_Embracing_Semantic_Priors_for_Multi-Modality_Image_CVPR_2025_paper.pdf)][[Code](https://github.com/RollingPlain/SAGE_IVIF)]
5. Task-driven Image Fusion with Learnable Fusion Loss, CVPR 2025, Haowen Bai et al., [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Bai_Task-driven_Image_Fusion_with_Learnable_Fusion_Loss_CVPR_2025_paper.pdf)][[Code](https://github.com/HaowenBai/TDFusion)]
6. Knowledge Distillation SegFormer-Based Network  for RGB-T Semantic Segmentation, TCYB 2024, Wujie Zhou et al,. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10817074)][[Code](https://github.com/purple-ting/KDSNet)]
7. Caltech Aerial RGB-Thermal Dataset in the Wild, ECCV 2024, Connor Lee et al,. [[PDF](extension://ngbkcglbmlglgldjfcnhaijeecaccgfi/https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08026.pdf)][[Code](https://github.com/aerorobotics/caltech-aerial-rgbt-dataset)]
8. Context-Aware Interaction Network for RGB-T Semantic Segmentation, TMM 2024, Ying Lv et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/10379106)][[Code](https://github.com/YingLv1106/CAINet)]
9. Multi-interactive Feature Learning and a Full-time Multi-modality Benchmark for Image Fusion and Segmentation, Jinyuan Liu et al., [[PDF](https://arxiv.org/pdf/2308.02097)][[Code](https://github.com/JinyuanLiu-CV/SegMiF)]
10. CACFNet: Cross-Modal Attention Cascaded Fusion Network for RGB-T Urban Scene Parsing, TIV 2023, Wujie Zhou et al., [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10251592)]
11. On Exploring Shape and Semantic Enhancements for RGB-X Semantic Segmentation, TIV 2023, Yuanjian Yang et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10185113)][[Code](https://github.com/HenonBamboo/SASEM)]
12. Complementarity-aware cross-modal feature fusion network for RGB-T semantic segmentation, PR 2023, Wei Wu et al.,  [[PDF](https://www.sciencedirect.com/science/article/pii/S0031320322003624)]
13. MMSMCNet: Modal Memory Sharing and Morphological Complementary Networks for RGB-T Urban Scene Semantic Segmentation, TCSVT 2023, Wujie Zhou et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/10123009)][[Code](https://github.com/2021nihao/MMSMCNet)]
14. SGFNet: Semantic-Guided Fusion Network for RGB-Thermal Semantic Segmentation, TCSVT 2023, Yike Wang et al., [[PDF](https://ieeexplore.ieee.org/document/10138593)][[Code](https://github.com/kw717/SGFNet)]
15. DBCNet: Dynamic Bilateral Cross-Fusion Network for RGB-T Urban Scene Understanding in Intelligent Vehicles, TCYB 2023, Wujie Zhou et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10217340)]
16. Explicit Attention-Enhanced Fusion for RGB-Thermal Perception Tasks, RAL 2023, Mingjian Liang et al., [[PDF](https://ieeexplore.ieee.org/document/10113725)][[Code](https://github.com/freeformrobotics/eaefnet)]
17. Embedded Control Gate Fusion and Attention Residual Learning for RGB–Thermal Urban Scene Parsing, TITS 2023, Wujie Zhou et al., [[PDF](https://ieeexplore.ieee.org/document/10041960)]
18. UTFNet: Uncertainty-Guided Trustworthy Fusion Network for RGB-Thermal Semantic Segmentation, GRSL 2023, Qingwang Wang et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10273407)][[Code](https://github.com/KustTeamWQW/UTFNet)]
19. Efficient Multimodal Semantic Segmentation via Dual-Prompt Learning, arxiv 2023, Shaohua Dong et al., [[PDF](https://arxiv.org/pdf/2312.00360.pdf)][[Code](https://github.com/shaohuadong2021/dplnet?tab=readme-ov-file)]
20. A RGB-Thermal Image Segmentation Method Based on Parameter Sharing and Attention Fusion for Safe Autonomous Driving, TITS 2023, Guofa Li et al., [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10337777)]
21. SFAF-MA: Spatial Feature Aggregation and Fusion With Modality Adaptation for RGB-Thermal Semantic Segmentation, TIM 2023, Xunjie He et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10103760)][[Code](https://github.com/hexunjie/SFAF-MA)]
22. Edge-aware guidance fusion network for RGB–thermal scene parsing, AAAI 2022, Wujie Zhou et al., [[PDF](https://arxiv.org/abs/2112.05144)][[Code](https://github.com/ShaohuaDong2021/EGFNet)]
23. CMX: Cross-Modal Fusion for RGB-X Semantic Segmentation with Transformers, TITS 2022, Jiaming Zhang et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/10231003)][[Code](https://github.com/huaaaliu/RGBX_Semantic_Segmentation)]
24. RGB-T Semantic Segmentation with Location, Activation, and Sharpening, TCSVT 2022, Gongyang Li et al., [[PDF](https://ieeexplore.ieee.org/document/9749834)][[Code](https://github.com/MathLee/LASNet)]
25. A Feature Divide-and-Conquer Network for RGB-T Semantic Segmentation, TCSVT 2022, Shenlu Zhao et al., [[PDF](https://ieeexplore.ieee.org/document/9987529)]
26. CCAFFMNet: Dual-spectral semantic segmentation network with channel-coordinate attention feature fusion module, Neurocomputing 2022, [[PDF](https://www.sciencedirect.com/science/article/pii/S0925231221017331)]
27. CGFNet: cross-guided fusion network for RGB-thermal semantic segmentation, The Visual Computer 2022, Yanping Fu et al., [[PDF](https://link.springer.com/article/10.1007/s00371-022-02559-2)]
28. MTANet: Multitask-Aware Network with Hierarchical Multimodal Fusion for RGB-T Urban Scene Understanding, TIV 2022, Wujie Zhou et al., [[PDF](https://ieeexplore.ieee.org/document/9900351)][[Code](https://github.com/ShaohuaDong2021/MTANet)]
29. GCNet: Grid-Like Context-Aware Network for RGB-Thermal Semantic Segmentation, Neurocomputing 2022, Jinfu Liu et al., [[PDF](https://www.sciencedirect.com/science/article/pii/S0925231222009006)]
30. ABMDRNet: Adaptive-weighted Bi-directional Modality Difference Reduction Network for RGB-T Semantic Segmentation, CVPR 2021, Qiang Zhang et al., [[PDF](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_ABMDRNet_Adaptive-Weighted_Bi-Directional_Modality_Difference_Reduction_Network_for_RGB-T_Semantic_CVPR_2021_paper.pdf)]
31. GMNet: Graded-Feature Multilabel-Learning Network for RGB-Thermal Urban Scene Semantic Segmentation, TIP 2021, Wujie Zhou et al., [[PDF](https://ieeexplore.ieee.org/document/9531449)][[Code](https://github.com/Jinfu0913/GMNet)]
32. MFFENet: Multiscale Feature Fusion and Enhancement Network for RGBThermal Urban Road Scene Parsing, TMM 2021, Wujie Zhou et al., [[PDF](https://ieeexplore.ieee.org/document/9447924)]
33. FEANet: Feature-Enhanced Attention Network for RGB-Thermal Real-time Semantic Segmentation, IROS 2021, Fuqin Deng et al., [[PDF](https://arxiv.org/pdf/2110.08988.pdf)][[Code](https://github.com/matrixgame2018/FEANet)]
34. HeatNet: Bridging the Day-Night Domain Gap in Semantic Segmentation with Thermal Images, IROS 2021, Johan Vertens et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/9341192)]
35. Robust semantic segmentation based on RGB-thermal in variable lighting scenes, Measurement 2021, Zhifeng Guo et al., [[PDF](https://www.sciencedirect.com/science/article/pii/S0263224121010903)]
36. FuseSeg: Semantic segmentation of urban scenes based on RGB and thermal data fusion, TASE 2020, Yuxiang Sun et al., [[PDF](https://ieeexplore.ieee.org/abstract/document/9108585/)]
37. PST900: RGB-Thermal Calibration, Dataset and Segmentation Network, ICRA 2020, Shreyas S. Shivakumar et al., [[PDF](https://ieeexplore.ieee.org/document/9196831)][[Code](https://github.com/ShreyasSkandanS/pst900_thermal_rgb)]
38. RTFNet: RGB-Thermal Fusion Network for Semantic Segmentation of Urban Scenes, RAL 2019, Yuxiang Sun et al., [[PDF](https://ieeexplore.ieee.org/document/8666745)][[Code](https://github.com/yuxiangsun/RTFNet)]
39. MFNet: Towards Real-Time Semantic Segmentation for Autonomous Vehicles with Multi-Spectral Scenes, IROS 2019, Qishen Ha et al., [[PDF](https://ieeexplore.ieee.org/document/8206396)][[Code](https://github.com/haqishen/MFNet-pytorch)]

--------------------------------------------------------------------------------------

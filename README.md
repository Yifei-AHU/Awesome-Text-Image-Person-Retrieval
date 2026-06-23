# Awesome-Text-Image Person Retrieval ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
A collection of deep learning based Text-Image Person Retrieval methods, codes and datasets.

## 🙏 Acknowledgments
- Thanks to Dr. **[Yang Bai (白杨)](https://scholar.google.com/citations?hl=zh-CN&user=oRTnolQAAAAJ)** from Wuhan University for his efforts in organizing works related to dialogue-based person retrieval.
- Thanks to Associate Professor **[Shuanglin Yan (严双林)](https://it.njfu.edu.cn/szll/fjs/20260108/i351842.html)** from Nanjing Forestry University for his efforts in organizing works related to text-image person retrieval.
- Thanks to Mr. **[Yong Wu (伍永)](https://scholar.google.com/citations?hl=zh-CN&user=3TKkLTUAAAAJ)** from Anhui Normal University for his efforts in organizing works related to text-image person retrieval.
- Thanks to Dr. **[Xiaowei Zhao (赵小卫)](https://scholar.google.com/citations?hl=zh-CN&user=jC3r2ncAAAAJ)** from Anhui University for his efforts in organizing works related to semi-supervised text-image person retrieval.

## 🤝 Contributing

Welcome to [pull requests](https://github.com/Yifei-AHU/Awesome-Text-Image-Person-Retrieval/pulls) to add papers, feel free to star and contact me. Keep updating....🚀

Markdown format:

```markdown
- `[Author Journal/Booktitle Year]` Title. Journal/Booktitle, Year. [[paper]](link) [[code]](link) [[homepage]](link)
```

## 🧭 Contents  

1. [Text-Image Person Retrieval](#-text-image-person-retrieval)
2. [Text-Aerial Person Retrieval](#text-aerial-person-retrieval)
3. [Semi/Weakly supervised Text-Image Person Retrieval](#-semiweakly-supervised-text-image-person-retrieval)
4. [Unsupervised Text-Image Person Retrieval](#-Unsupervised-Text-Image-Person-Retrieval)
5. [Dialogue-based Person Retrieval](#-Dialogue-based-Person-Retrieval)
6. [Text-to-Video Person Retrieval](#-text-to-video-person-retrieval)

## 🚶 Text-Image Person Retrieval
## 📊 Datasets
|Dataset                        | Years |    Images   |Captions|   IDs  |
|-------------------------------|-------|-------------|------  |--------|
|[CUHK-PEDES](https://github.com/ShuangLI59/Person-Search-with-Natural-Language-Description)|2017|40,206|80,412|13,003|
|[RSTPReid](https://github.com/NjtechCVLab/RSTPReid-Dataset)|2021|20,505|41010|4,101|
|[ICFG-PEDES](https://github.com/zifyloo/SSAN)|2021|54,522|54,522|4,102|
[UFineBench](https://github.com/Zplusdragon/UFineBench)|2024|26,206|52,412|6,926|

## 📄 Papers

### 2026
- `[Zou et al. CVPR26]` Tackling Alignment Ambiguity in Person Retrieval through Conversational Attribute Mining, CVPR 2026. [[PDF](https://openaccess.thecvf.com/content/CVPR2026/papers/Zou_Tackling_Alignment_Ambiguity_in_Person_Retrieval_through_Conversational_Attribute_Mining_CVPR_2026_paper.pdf)]
  
- `[Li et al. CVPR26]` Quota-Calibrated Fine-Grained Alignment with Context-Aware Marginals for Text-based Person Retrieval, CVPR 2026. [[PDF](https://openaccess.thecvf.com/content/CVPR2026/papers/Li_Quota-Calibrated_Fine-Grained_Alignment_with_Context-Aware_Marginals_for_Text-based_Person_Retrieval_CVPR_2026_paper.pdf)]
  
- `[Yuan et al. AAAI26]` Geometry-Aware Noisy Correspondence Mitigation for Cross-Modal Text-Based Person Retrieval, AAAI 2026. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/38218)]
  
- `[You et al. AAAI26]` KPDM: Key Phrase Dynamic Masking for Robust Text-to-Image Person Retrieval, AAAI 2026. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/38199)]
  
- `[Zhou et al. AAAI26]` Hierarchical Prompt Learning for Image- and Text-Based Person Re-Identification, AAAI 2026.  [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/38380)]
  
- `[Liang et al. WWW26]` Pedestrian-Centric Discriminative and Fine-grained Semantic Mining for Text-based Person Retrieval, WWW 2026. [[PDF](https://dl.acm.org/doi/abs/10.1145/3774904.3792134)]
  
- `[Deng et al. TIFS26]` Cross-modal Person Retrieval with One-to-Many Relation Modeling, TIFS 2026.  [[PDF](https://ieeexplore.ieee.org/abstract/document/11503671)]
  
- `[Dong et al. TIP26]` Taking Astray Domain Back Home for Single-Source Domain Generalizable Text-to-Image Person Retrieval, TIP 2026. [[PDF](https://ieeexplore.ieee.org/abstract/document/11433531)]
  
- `[Yang et al. TCSVT26]` Probabilistic Distribution Alignment for Text-Based Person Retrieval, TCSVT 2026. [[PDF](https://ieeexplore.ieee.org/abstract/document/11433531)]
  
- `[Yang et al. PR26]` Minimizing the pretraining gap: Domain-aligned text-based person retrieval, PR 2026. [[PDF](https://ieeexplore.ieee.org/abstract/document/11386968)]
  
- `[Yang et al. PR26]` A training-free framework for text-to-image person re-identification via query-prototype matching, PR 2026. [[PDF](https://www.sciencedirect.com/science/article/pii/S0031320326006709)]

### 2025
* `[Qin et al. CVPR26]` Human-centered Interactive Learning via MLLMs for Text-to-Image Person Re-identification, CVPR 2025. [[PDF](https://openaccess.thecvf.com/content/CVPR2025/html/Qin_Human-centered_Interactive_Learning_via_MLLMs_for_Text-to-Image_Person_Re-identification_CVPR_2025_paper.html)]

* `[Jiang et al. CVPR25]` Modeling Thousands of Human Annotators for Generalizable Text-to-Image Person Re-identification, CVPR 2025. [[PDF](https://openaccess.thecvf.com/content/CVPR2025/html/Jiang_Modeling_Thousands_of_Human_Annotators_for_Generalizable_Text-to-Image_Person_Re-identification_CVPR_2025_paper.html)]

* `[Yang et al. ICCV25]` Beyond Walking: A Large-Scale Image-Text Benchmark for Text-based Person Anomaly Search, ICCV 2025. [[PDF](https://openaccess.thecvf.com/content/ICCV2025/papers/Yang_Beyond_Walking_A_Large-Scale_Image-Text_Benchmark_for_Text-based_Person_Anomaly_ICCV_2025_paper.pdf)]

* `[Zheng et al. MM25]` Dual Uncertainty-Guided Feature Alignment Learning for Text-Based Person Retrieval, ACM MM 2025. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3755063)]

* `[Deng et al. MM25]` Learning Hierarchical Cross-modal Association with Intra-modal Context for Text-Image Person Retrieval, ACM MM 2025. [[PDF](https://dl.acm.org/doi/epdf/10.1145/3746027.3754721)]

* `[Wang et al. MM25]` GPT-ReID: Learning Fine-grained Representation with GPT for Text-based Person Retrieval, ACM MM 2025. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3755123)]

* `[Zhang et al. AAAI25]` Visual perturbation for text-based person search, AAAI 2025. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/33091)]

* `[Liu et al. AAAI25]` DM-Adapter: Domain-Aware Mixture-of-Adapters for Text-Based Person Retrieval, AAAI 2025. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/32608)]

* `[Niu et al. AAAI25]` Test-Time Adaptation for Text-Based Person Search, AAAI 2025. [[PDF](https://dl.acm.org/doi/abs/10.1145/3746027.3754946)]

* `[Luo et al. AAAI25]` Graph-based cross-domain knowledge distillation for cross-dataset text-to-image person retrieval, AAAI 2025. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/32037)]

* `[Sun et al. WWW25]` From Data Deluge to Data Curation: A Filtering-WoRA Paradigm for Efficient Text-based Person Search, WWW 2025. [[PDF](https://dl.acm.org/doi/abs/10.1145/3696410.3714788)]

* `[Zheng et al. EMNLP25]` Gradient-Attention Guided Dual-Masking Synergetic Framework for Robust Text-based Person Retrieval, EMNLP 2025. [[PDF](https://aclanthology.org/2025.emnlp-main.14/)]

* `[Yan et al. IJCAI25]` Cross-modal collaborative representation learning for text-to-image person retrieval, IJCAI 2025. [[PDF](https://www.ijcai.org/proceedings/2025/0240.pdf)]

* `[Cao et al. TPAMI25]` Multilingual Text-to-Image Person Retrieval via Bidirectional Relation Reasoning and Aligning, TPAMI 2025. [[PDF](https://ieeexplore.ieee.org/abstract/document/11199360)]


### 2024
* `[Qin et al. CVPR24]` Noisy-Correspondence Learning for Text-to-Image Person Re-identification, CVPR 2024. [[PDF](https://openaccess.thecvf.com/content/CVPR2024/papers/Qin_Noisy-Correspondence_Learning_for_Text-to-Image_Person_Re-identification_CVPR_2024_paper.pdf)]

* `[Tan et al. CVPR24]` Harnessing the Power of MLLMs for Transferable Text-to-Image Person ReID, CVPR 2024. [[PDF](https://openaccess.thecvf.com/content/CVPR2024/papers/Tan_Harnessing_the_Power_of_MLLMs_for_Transferable_Text-to-Image_Person_ReID_CVPR_2024_paper.pdf)]

* `[Zuo et al. CVPR24]` UFineBench: Towards Text-based Person Retrieval with Ultra-fine Granularity, CVPR 2024. [[PDF](https://openaccess.thecvf.com/content/CVPR2024/papers/Zuo_UFineBench_Towards_Text-based_Person_Retrieval_with_Ultra-fine_Granularity_CVPR_2024_paper.pdf)]

* `[Zuo et al. NeurIPS24]` PLIP: Language-Image Pre-training for Person Representation Learning, NeurIPS 2024. [[PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/510ad3018bbdc5b6e3b10646e2e35771-Paper-Conference.pdf)]

* `[Park et al. ECCV24]` PLOT: Text-Based Person Search with Part Slot Attention for Corresponding Part Discovery, ECCV 2024. [[PDF](https://arxiv.org/pdf/2409.13475?)]

* `[Cao et al. AAAI24]` An Empirical Study of CLIP for Text-Based Person Search, AAAI 2024. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/27801)]

* `[Song et al. AAAI24]` Diverse Person: Customize Your Own Dataset for Text-Based Person Search, AAAI 2024. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/28298)]

* `[Liu et al. AAAI24]` Causality-Inspired Invariant Representation Learning for Text-Based Person Retrieval, AAAI 2024. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/29314)]

* `[Li et al. AAAI24]` Adaptive Uncertainty-Based Learning for Text-Based Person Retrieval, AAAI 2024. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/28101)]

* `[Zhao et al. AAAI24]` Unifying Multi-Modal Uncertainty Modeling and Semantic Alignment for Text-to-Image Person Re-identification, AAAI 2024. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/28585)]

* `[Wang et al. MM24]` Fine-grained Semantic Alignment with Transferred Person-SAM for Text-based Person Retrieval, ACM MM 2024. [[PDF](https://dl.acm.org/doi/epdf/10.1145/3664647.3681553)]

* `[Yan et al. MM24]` Prototypical Prompting for Text-to-Image Person Re-identification, ACM MM 2024. [[PDF](https://dl.acm.org/doi/epdf/10.1145/3664647.3681165)]

* `[Wang et al. MM24]` Fine-grained Semantics-aware Representation Learning for Text-based Person Retrieval, ACM MM 2024. [[PDF](https://dl.acm.org/doi/epdf/10.1145/3652583.3658054)]

* `[Su et al. SIGIR24]` MACA: Memory-aided Coarse-to-fine Alignment for Text-based Person Search, SIGIR 2024. [[PDF](https://dl.acm.org/doi/epdf/10.1145/3626772.3657915)]

* `[Sun et al. IJCV24]` An Adaptive Correlation Filtering Method for Text-Based Person Search, IJCV 2024. [[PDF](https://link.springer.com/article/10.1007/s11263-024-02094-8)]


### 2023
* `[Shao et al. ICCV23]` Unified Pre-training with Pseudo Texts for Text-To-Image Person Re-identification, ICCV 2023. [[PDF](https://openaccess.thecvf.com/content/ICCV2023/papers/Shao_Unified_Pre-Training_with_Pseudo_Texts_for_Text-To-Image_Person_Re-Identification_ICCV_2023_paper.pdf)]

* `[Jiang et al. CVPR23]` Cross-modal Implicit Relation Reasoning and Aligning for Text-to-Image Person Retrieval, CVPR 2023. [[PDF](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiang_Cross-Modal_Implicit_Relation_Reasoning_and_Aligning_for_Text-to-Image_Person_Retrieval_CVPR_2023_paper.pdf)]

* `[Yang et al. MM23]` Towards Unified Text-based Person Retrieval: A Large-scale Multi-Attribute and Language Search Benchmark, ACM MM 2023. [[PDF](https://dl.acm.org/doi/epdf/10.1145/3581783.3611709)]

* `[Bai et al. IJCAI23]` RaSa: Relation and Sensitivity Aware Representation Learning for Text-based Person Search, IJCAI 2023. [[PDF](https://arxiv.org/pdf/2305.13653)]

* `[Yan et al. MM23]` Learning Comprehensive Representations with Richer Self for Text-to-Image Person Re-Identification, ACM MM 2023. [[PDF](https://dl.acm.org/doi/epdf/10.1145/3581783.3611832)]

* `[Shen et al. MM23]` Pedestrian-specific Bipartite-aware Similarity Learning for Text-based Person Retrieval, ACM MM 2023. [[PDF](https://dl.acm.org/doi/epdf/10.1145/3581783.3612009)]

* `[Ma et al. MM23]` BEAT: Bi-directional One-to-Many Embedding Alignment for Text-based Person Retrieval, ACM MM 2023. [[PDF](https://dl.acm.org/doi/epdf/10.1145/3581783.3611768)]

* `[Li et al. MM23]` DCEL: Deep Cross-modal Evidential Learning for Text-based Person Retrieval, ACM MM 2023. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3581783.3612244)]

* `[Zang et al. MM23]` A Baseline Investigation: Transformer-based Cross-view Baseline for Text-based Person Search, ACM MM 2023. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3581783.3611916)]

* `[Yan et al. TIP23]` CLIP-driven Fine-grained Text-Image Person Re-identification, TIP 2023. [[PDF](https://ieeexplore.ieee.org/abstract/document/10304579)]

--------------------------------------------------------------------------------------
<a id="text-aerial-person-retrieval"></a>
## 🛰️ Text-Aerial Person Retrieval
## 📊 Datasets
|Dataset                        | Years |    Images   |  IDs  |
|-------------------------------|-------|-------------|-------|
|[AERI-PEDES](https://github.com/Yifei-AHU/AERI-PEDES)|2026|144,548|4,659|
|[TBAPR](https://github.com/xbdxwyh/AEA-FIRM-main)|2025|65,880|1,709|
|[TAG-PEDES](https://github.com/Flame-Chasers/TAG-PR)|2025|28,206|6,840|

## 📄 Papers
* `[Deng et al. CVPR26]` Cross-modal Fuzzy Alignment Network for Text-Aerial Person Retrieval and A Large-scale Benchmark, CVPR 2026. [[PDF](https://openaccess.thecvf.com/content/CVPR2026/html/Deng_Cross-modal_Fuzzy_Alignment_Network_for_Text-Aerial_Person_Retrieval_and_A_CVPR_2026_paper.html)] [[Code](https://github.com/Yifei-AHU/AERI-PEDES)]

* `[Wang et al. TCSVT25]` AEA-FIRM: Adaptive Elastic Alignment with Fine-Grained Representation Mining for Text-based Aerial-Ground Pedestrian Retrieval, TCSVT 2025. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11072214)] [[Code](https://github.com/xbdxwyh/AEA-FIRM-main)]

* `[Zhou et al. AAAI26]` Text-based Aerial-Ground Person Retrieval, AAAI 2026. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/40140)] [[Code](https://github.com/Flame-Chasers/TAG-PR)]

--------------------------------------------------------------------------------------

## 🧪 Semi/Weakly supervised Text-Image Person Retrieval

## 📄 Papers
* `[Zhao et al. ICCV21]` Weakly Supervised Text-based Person Re-Identification, ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhao_Weakly_Supervised_Text-Based_Person_Re-Identification_ICCV_2021_paper.pdf)]

* `[Gao et al. TIP25]` Semi-supervised Text-based Person Search, TIP 2025. [[PDF](https://ieeexplore.ieee.org/abstract/document/11165023/)]

* `[Zhang et al. MM25]` Dual-Granularity Cross-Modal Identity Association for Weakly-Supervised Text-to-Person Image Matching, ACM MM 2025. [[PDF](https://arxiv.org/pdf/2507.06744)]

* `[Bai et al. MM23]` Text-based Person Search without Parallel Image-Text Data, ACM MM 2023. [[PDF](https://arxiv.org/pdf/2305.12964)]

* `[Xu et al. TMM25]` Attribute-Centric Cross-Modal Alignment for Weakly Supervised Text-Based Person Re-ID, TMM 2025. [[PDF](https://ieeexplore.ieee.org/abstract/document/11159251)]

--------------------------------------------------------------------------------------

## 🔓 Unsupervised Text-Image Person Retrieval

## 📄 Papers
* `[Niu et al. TIP26]` Pseudo Sentences Evaluation and Quality-Aware Robust Learning for Unsupervised Text-Based Person Search, TIP 2026. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11534391)]

* `[Li et al. AAAI25]` Exploring the Potential of Large Vision-Language Models for Unsupervised Text-based Person Retrieval, AAAI 2025. [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/32543)]

* `[Chen et al. MM25]` Unsupervised Cross-Modal Person Search via Progressive Diverse Text Generation, ACM MM 2025. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3755171)]

* `[Mu et al. MM25]` FACE: A Dual-Template and Adaptive Curriculum Framework for Unsupervised Text-Based Person Search, ACM MM 2025. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3755315)]

* `[Shao et al. TCSVT25]` Dependability Feature Learning based on Sample Generation for Unsupervised Text-to-Image Person Re-identification, TCSVT 2025. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11131229)]

* `[Gong et al. IJCAI24]` Enhancing Cross-modal Completion and Alignment for Unsupervised Incomplete Text-to-Image Person Retrieval, IJCAI 2024. [[PDF](https://www.ijcai.org/proceedings/2024/0088.pdf)]

* `[Sun et al. PR26]` Unsupervised Text-based Person Retrieval via Adaptive Uncertainty-Aware Cross-Modal Learning, PR 2026. [[PDF](https://www.sciencedirect.com/science/article/pii/S0031320326005935)]

* `[Li et al. KBS25]` Multi-granularity Confidence Learning for Unsupervised Text-to-Image Person Re-identification with Incomplete Modality, KBS 2025. [[PDF](https://www.sciencedirect.com/science/article/pii/S095070512500351X)]

* `[Niu et al. PR26]` Cache-aided Cross-modal Correlation Correction for Unsupervised Cross-domain Text-based Person Search, PR 2026. [[PDF](https://www.sciencedirect.com/science/article/pii/S0031320325011847)]

--------------------------------------------------------------------------------------

## 💬 Dialogue-based Person Retrieval
## 📊 Datasets
|Dataset                        | Years |    Images   |  IDs  |
|-------------------------------|-------|-------------|-------|
|[ChatPedes](https://github.com/Flame-Chasers/DiaNA)|2025|37,128|12,003|
|[Interactive-PEDES](https://github.com/XLearning-SCU/LLaVA-ReID)|2025|54,749|13,051|

## 📄 Papers
* `[Bai et al. CVPR25]` Chat-based Person Retrieval via Dialogue-Refined Cross-Modal Alignment, CVPR 2025. [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Bai_Chat-based_Person_Retrieval_via_Dialogue-Refined_Cross-Modal_Alignment_CVPR_2025_paper.pdf)] [[Code](https://github.com/Flame-Chasers/DiaNA)]

* `[Xie et al. EMNLP25]` Chat-Driven Text Generation and Interaction for Person Retrieval, EMNLP 2025. [[PDF](https://aclanthology.org/2025.emnlp-main.266.pdf)]

* `[Liu et al. MM25]` Dialogue-Driven Interactive Dynamic Learning for Text-to-Image Person Retrieval, ACM MM 2025. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3746027.3754583)]

* `[Lu et al. ICML25]` LLaVA-ReID: Selective Multi-image Questioner for Interactive Person Re-Identification, ICML 2025. [[PDF](https://arxiv.org/pdf/2504.10174?)] [[Code](https://github.com/XLearning-SCU/LLaVA-ReID)]

--------------------------------------------------------------------------------------

## 🎬 Text-to-Video Person Retrieval
## 📊 Datasets
|Dataset                        | Years |    Videos   |  Sentences  |
|-------------------------------|-------|-------------|-------|
|[TVPReid](https://github.com/NjtechCVLab/TVPReid-Dataset)|2024|6,559|13,118|
|T-MARS|2026|20,472|-|
|TV-MARS|2026|16,360|16,360|

## 📄 Papers
* `[Zhang et al. MM24]` TVPR: Text-to-Video Person Retrieval and a New Benchmark, ACM MM 2024. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3664647.3681715)] 

* `[Meng et al. Information Sciences26]` Spatio-temporal semantic alignment leveraging human structural priors for text-to-video person retrieval, Information Sciences 2026. [[PDF](https://www.sciencedirect.com/science/article/pii/S0020025526003452)]

* `[Su et al. Neurocomputing26]` Text-to-video person re-identification benchmark: Dataset and dual-modal contextual alignment, Neurocomputing 2026. [[PDF](https://www.sciencedirect.com/science/article/pii/S0925231225032680)]

--------------------------------------------------------------------------------------

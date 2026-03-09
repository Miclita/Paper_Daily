# AI 医疗与运动领域顶刊追踪报告

**日期**: 2026-03-09  
**范围**: 最近 7 天 (从 2026/03/02)  
**期刊**: 17 本国际顶尖综合与医学期刊  

## 1. 统计概览

| 类别 | 数量 |
| :--- | :--- |
| 医学影像 AI | 3 篇 |
| **总计** | **3 篇** |

## 2. 文献概览

| # | 类别 | 相关性 | 中文标题 | 期刊 | 链接 |
| :--- | :--- | :---: | :--- | :--- | :--- |
| 1 | 医学影像 AI | 9/10 | （翻译不可用：HTTP Error 401: Unauthorized） | Nature | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41781626/) |
| 2 | 医学影像 AI | 9/10 | （翻译不可用：HTTP Error 401: Unauthorized） | Radiology. Cardiothoracic imaging | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41784492/) |
| 3 | 医学影像 AI | 9/10 | （翻译不可用：HTTP Error 401: Unauthorized） | Nature communications | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41776178/) |

---

## 3. 文献详情

### 1. （翻译不可用：HTTP Error 401: Unauthorized）

- **英文标题**: Merlin: a computed tomography vision-language foundation model and dataset.
- **期刊**: Nature (2026)
- **作者**: Louis Blankemeier, Ashwin Kumar, Joseph Paul Cohen
- **类别**: 医学影像 AI
- **相关性**: 9/10 — 医学影像AI，使用视觉-语言模型进行CT分析，直接服务于临床诊断，AI是核心贡献。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41781626/

**中文摘要**: （翻译不可用：HTTP Error 401: Unauthorized）

**英文摘要**: The large volume of abdominal computed tomography (CT) scans 1,2 coupled with the shortage of radiologists 3-6 have intensified the need for automated medical image analysis tools. Previous state-of-the-art approaches for automated analysis leverage vision-language models (VLMs) that jointly model images and radiology reports 7-12 . However, current medical VLMs are generally limited to 2D images and short reports. Here to overcome these shortcomings for abdominal CT interpretation, we introduce Merlin, a 3D VLM that learns from volumetric CT scans, electronic health record data and radiology reports. This approach is enabled by a multistage pretraining framework that does not require additional manual annotations. We trained Merlin using a high-quality clinical dataset of paired CT scans (>6 million images from 15,331 CT scans), diagnosis codes (>1.8 million codes) and radiology reports (>6 million tokens). We comprehensively evaluated Merlin on 6 task types and 752 individual tasks that covered diagnostic, prognostic and quality-related tasks. The non-adapted (off-the-shelf) tasks included zero-shot classification of findings (30 findings), phenotype classification (692 phenotypes) and zero-shot cross-modal retrieval (image-to-findings and image-to-impression). The model-adapted tasks included 5-year chronic disease prediction (6 diseases), radiology report generation and 3D semantic segmentation (20 organs). We validated Merlin at scale, with internal testing on 5,137 CT scans and external testing on 44,098 CT scans from 3 independent sites and 2 public datasets. The results demonstrated high generalization across institutions and anatomies. Merlin outperformed 2D VLMs, CT foundation models and off-the-shelf radiology models. We also computed scaling laws and conducted ablation studies to identify optimal training strategies. We release our trained models, code and dataset for 25,494 pairs of abdominal CT scans and radiology reports. Our results demonstrate how Merlin may assist in the interpretation of abdominal CT scans and mitigate the burden on radiologists while simultaneously adding value for future biomarker discovery and disease risk stratification.

---

### 2. （翻译不可用：HTTP Error 401: Unauthorized）

- **英文标题**: Deep Learning Segmentation of Pectoralis Muscle Volume at CT and Comparison with Pectoralis Muscle Area in COPD.
- **期刊**: Radiology. Cardiothoracic imaging (2026)
- **作者**: Daniel Genkin, Mustansir Verdawala, Sophie &#xc9; Collins
- **类别**: 医学影像 AI
- **相关性**: 9/10 — 深度学习用于医学影像（CT）的肌肉分割，并与临床相关结局（COPD）相关联，AI是核心贡献。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41784492/

**中文摘要**: （翻译不可用：HTTP Error 401: Unauthorized）

**英文摘要**: Purpose To develop a deep learning model for segmenting pectoralis muscle volume (PMV) at CT and evaluate the reproducibility, group differences, and associations of pectoralis muscle area (PMA) and PMV with chronic obstructive pulmonary disease (COPD)-related outcomes. Materials and Methods This study was a secondary analysis of the prospective Canadian Cohort Obstructive Lung Disease study (CanCOLD, data collected from November 2009 to July 2015). Randomly sampled CT scans from CanCOLD were used for model training, validation, and internal testing ( n = 96, 16, and 32, respectively) and an external dataset for external testing ( n = 32). A U-Net model was trained for PMV segmentation, and performance was assessed using the Dice similarity coefficient (DSC). PMA and PMV values were extracted from paired inspiration and expiration scans to assess segmentation reproducibility. Differences between individuals with or without COPD and associations with forced expiratory volume in 1 second (FEV 1 ), diffusing capacity of the lungs for carbon monoxide (Dlco), and peak oxygen uptake during exercise (VO 2 ) were reported. Results Individuals included those with ( n = 634; mean age, 67.3 years ± 10.1 [SD]; 394 male participants) and without ( n = 601; mean age, 65.8 years ± 9.6; 327 male participants) COPD. The model yielded DSCs of 0.94 ± 0.04, 0.93 ± 0.03, and 0.92 ± 0.04 in the training and validation, internal testing, and external testing datasets, respectively. Contrary to PMV (bias, 0.1 cm 3 ; P = .77), PMA showed bias between inspiration and expiration (bias, -2.7 cm 2 ; P < .001). Both PMA and PMV were reduced in patients with COPD ( P < .05), but PMV was more strongly associated with FEV 1 (adjusted R 2 [ R adj 2 ], 0.609/0.598), Dlco ( R adj 2 , 0.645/0.627), and VO 2 ( R adj 2 , 0.680/0.666). Conclusion An accurate and generalizable CT-based deep learning model for pectoralis muscle segmentation was developed. Compared with PMA, PMV showed better reproducibility and stronger associations with COPD outcomes. Keywords: CT, Thorax, Lung, Volume Analysis, Chronic Obstructive Pulmonary Disease, Segmentation ClinicalTrials.gov identifier no. NCT00920348 © RSNA, 2026 Supplemental material is available for this article.

---

### 3. （翻译不可用：HTTP Error 401: Unauthorized）

- **英文标题**: Contrast-free identification of glioma blood-brain barrier status via generative diffusion AI and non-contrast MRI.
- **期刊**: Nature communications (2026)
- **作者**: Kaiyi Zheng, Yiwen Zhang, Hai Shu
- **类别**: 医学影像 AI
- **相关性**: 9/10 — 生成对抗网络结合非对比MRI用于脑胶质瘤血脑屏障状态的无创评估，属于医学影像AI的核心应用。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41776178/

**中文摘要**: （翻译不可用：HTTP Error 401: Unauthorized）

**英文摘要**: Non-contrast MRI, routinely used for the preoperative diagnosis of glioma tumors and establishing treatment strategies, provides the potential for assessing blood-brain barrier (BBB) status without using gadolinium-based contrast agents (GBCA) which could cause adverse events. Additionally, generative artificial intelligence (AI) models enable the synthesis of contrast-enhanced images from non-contrast images. Despite this potential, the heterogeneity of GBCA-induced features in tumor areas and error accumulation from inaccurate synthesis largely limit the efficacy of conventional generative models. To address these limitations, we introduce a contrast-free BBB status identification model (CBSI) that can identify BBB status with high accuracy using non-contrast MR images and generative diffusion AI networks. Trained and validated on a multi-center dataset of 1,535 patients, CBSI achieves an area under the curve (AUC) of 81.31%, surpassing the performance of the model using only non-contrast MR (AUC = 72.76%) and demonstrating comparable performance to the T1Gd MR model (AUC = 88.68%) in an external test set. Furthermore, validation on two public datasets (BraTS-Africa and BraTS-GLI) supports the generalizability of CBSI in BBB status identification. Notably, with accurate BBB status of synthetic T1Gd, the performance of glioma segmentation and grading is improved significantly compared to existing methods. Generalizability analysis indicates that CBSI can facilitate BBB status identification using synthetic T1Gd findings, avoiding GBCA adverse effects and streamlining clinical workflows.

---


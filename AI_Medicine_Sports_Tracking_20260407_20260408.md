# AI 医疗与运动领域顶刊追踪报告

**日期**: 2026-04-08  
**范围**: 最近 1 天 (从 2026/04/07)  
**期刊**: 17 本国际顶尖综合与医学期刊  

## 1. 统计概览

| 类别 | 数量 |
| :--- | :--- |
| 医学影像 AI | 2 篇 |
| **总计** | **2 篇** |

## 2. 文献概览

| # | 类别 | 相关性 | 中文标题 | 期刊 | 链接 |
| :--- | :--- | :---: | :--- | :--- | :--- |
| 1 | 医学影像 AI | 8/10 | 基于深度学习的儿童胸部X线片预测骨密度：一项多中心可行性研究。 | Radiology | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41944722/) |
| 2 | 医学影像 AI | 8/10 | 通过可解释的对抗性分解学习提高临床相关性，解耦阿尔茨海默病的PET病理异常。 | Radiology | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41944723/) |

---

## 3. 文献详情

### 1. 基于深度学习的儿童胸部X线片预测骨密度：一项多中心可行性研究。

- **英文标题**: Deep Learning-based Bone Mineral Density Prediction Using Pediatric Chest Radiographs: A Multicenter Feasibility Study.
- **期刊**: Radiology (2026)
- **作者**: Jae Won Choi, Young Jin Ryu, Jung-Eun Cheon
- **类别**: 医学影像 AI
- **相关性**: 8/10 — AI用于医学影像（X光）的临床预测任务（BMD预测），直接服务于儿科骨健康评估，AI是核心贡献。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41944722/

**中文摘要**: 背景：测量骨密度（BMD）对于儿童骨骼健康评估至关重要。双能X线吸收测定法（DXA）是参考标准，但其可及性有限。目的：开发并评估一种人工智能模型，用于从儿童胸部X光片预测BMD。材料与方法：本回顾性研究纳入了在两家三级医院于3个月内接受DXA和胸部X光检查且年龄小于18岁的患者（内部测试）。

**英文摘要**: Background Measuring bone mineral density (BMD) is essential for pediatric bone health assessment. Dual-energy x-ray absorptiometry (DXA) is the reference standard but has limited accessibility. Purpose To develop and evaluate an artificial intelligence model for predicting BMD from pediatric chest radiography. Materials and Methods This retrospective study included patients aged younger than 18 years who underwent DXA and chest radiography within 3 months at two tertiary hospitals (internal test, 2014-2023; external test, 2022-2023). The internal dataset was temporally split into development (fivefold cross-validation) and test sets. The model combined chest radiographs and clinical variables (age, sex, height, and weight) to predict the lumbar spine (L1 through L4) areal BMD, with Z scores calculated from Korean pediatric reference. Performance was evaluated using the Pearson correlation coefficient (r) for regression and the area under the receiver operating characteristic curve (AUC) for detecting low BMD ( Z score ≤ -2.0). Results A total of 1464 radiograph-DXA pairs (median age, 13 years [IQR, 11-16 years]; 824 boys) were included: 774 in the development set, 376 in the internal test set, and 314 in the external test set. The predicted BMD Z scores were strongly correlated with the DXA scores in both the internal ( r = 0.85 [95% CI: 0.82, 0.88]; P < .001) and external ( r = 0.76 [95% CI: 0.71, 0.81]; P < .001) test sets. For detecting low BMD, the internal test set had an AUC of 0.92 (95% CI: 0.89, 0.95), a sensitivity of 60% (50 of 84 scans; 95% CI: 48, 70), and a specificity of 95% (276 of 292 scans; 95% CI: 91, 97). The external test set achieved an AUC of 0.90 (95% CI: 0.87, 0.94), a sensitivity of 82% (54 of 66 scans; 95% CI: 70, 90), and a specificity of 85% (210 of 248 scans; 95% CI: 80, 89). Conclusion A chest radiograph-based artificial intelligence model accurately predicted pediatric BMD Z scores and identified low BMD. © RSNA, 2026 Supplemental material is available for this article.

---

### 2. 通过可解释的对抗性分解学习提高临床相关性，解耦阿尔茨海默病的PET病理异常。

- **英文标题**: Decoupling Alzheimer Disease Pathologic Abnormalities at PET with Improved Clinical Relevance by Interpretable Adversarial Decomposition Learning.
- **期刊**: Radiology (2026)
- **作者**: Cheng Tang, Xun Sun, Anqi Tang
- **类别**: 医学影像 AI
- **相关性**: 8/10 — AI用于阿尔茨海默病PET影像分析，提升临床相关性，具有直接应用价值。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41944723/

**中文摘要**: 背景 基于模板的PET指标可以量化阿尔茨海默病（AD）的β淀粉样蛋白（Aβ）和tau蛋白负担，但将全脑数据压缩为一个标量值，忽略了疾病的异质性，有时会导致影像与临床结果的不一致。人工智能（AI）方法能够捕捉更丰富的模式，但通常缺乏生物学可解释性。目的 本研究旨在开发并验证一种可解释的深度学习框架，该框架能够通过病理生理学机制将AD特异性异常与生理性摄取区分开来。

**英文摘要**: Background Template-based PET metrics quantify Alzheimer disease (AD) amyloid-β (Aβ) and tau burden but compress whole-brain data into a single scalar, overlooking disease heterogeneity and sometimes causing imaging-clinical discordance. Artificial intelligence (AI) approaches capture richer patterns but often lack biologic interpretability. Purpose To develop and validate an interpretable deep-learning framework that separates AD-specific abnormalities from physiologic uptake using pathophysiologic constraints, generating a clinically meaningful AI biomarker. Materials and Methods In this retrospective study, Aβ and tau PET scans from the Alzheimer's Disease Neuroimaging Initiative, Australian Imaging Biomarkers and Lifestyle study, Global Alzheimer's Association Interactive Network, and the authors' center were analyzed. An adversarial decomposition learning (ADL) network generated voxel-level pathologic maps and an AD adversarial decomposition (ADAD) score. Discriminatory performance for clinical AD versus cognitively normal individuals was evaluated using the area under the curve (AUC). Clinical relevance was assessed with cognitive, hippocampal volume, cerebrospinal fluid (CSF), and neuropathologic measures using longitudinal mixed-effects models and Spearman correlations. Results The study included 7457 Aβ PET scans from 3595 patients (median age, 71.4 years; IQR, 65.7-77.0 years; 1637 female patients) and 1894 tau PET scans from 1127 patients (median age, 72.0 years; IQR, 66.9-78.5 years; 545 female patients). External testing AUCs were 0.94 (95% CI: 0.89, 0.98) for Aβ and 0.98 (95% CI: 0.95, 1.00) for tau. ADL generated interpretable pathologic attribution maps that correlated with expert rankings (Aβ and tau, Spearman ρ = 0.79 and 0.63, respectively). Although Centiloid and CenTauRz showed numerically higher correlations with postmortem neuropathologic structure and stronger associations with CSF biomarkers, the ADAD score demonstrated independent baseline and longitudinal associations with cognitive outcomes and hippocampal atrophy after adjustment. Conclusion Pathophysiologic-constrained ADL provided interpretable, personalized pathologic maps and an AI-derived ADAD score that more closely linked PET pathologic abnormalities with multimodal clinical measures. © RSNA, 2026 Supplemental material is available for this article.

---


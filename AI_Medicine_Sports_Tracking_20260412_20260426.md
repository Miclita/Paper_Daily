# AI 医疗与运动领域顶刊追踪报告

**日期**: 2026-04-26  
**范围**: 最近 14 天 (从 2026/04/12)  
**期刊**: 17 本国际顶尖综合与医学期刊  

## 1. 统计概览

| 类别 | 数量 |
| :--- | :--- |
| 临床决策/预测 AI | 4 篇 |
| 医学影像 AI | 8 篇 |
| 运动 AI | 1 篇 |
| 可穿戴/传感器 AI | 1 篇 |
| **总计** | **14 篇** |

## 2. 文献概览

| # | 类别 | 相关性 | 中文标题 | 期刊 | 链接 |
| :--- | :--- | :---: | :--- | :--- | :--- |
| 1 | 临床决策/预测 AI | 9/10 | DxDirector：一个驱动全流程临床诊断的代理型大型语言模型 | Nature communications | [PubMed](https://pubmed.ncbi.nlm.nih.gov/42026083/) |
| 2 | 医学影像 AI | 9/10 | 基于肿瘤和内脏脂肪组织CT特征的深度学习模型预测浆膜浸润型胃癌根治术后腹膜转移风... | Radiology. Imaging cancer | [PubMed](https://pubmed.ncbi.nlm.nih.gov/42029163/) |
| 3 | 医学影像 AI | 9/10 | 一种用于冠状动脉CT血管成像中量化冠状动脉斑块的全自动深度学习模型。 | Radiology | [PubMed](https://pubmed.ncbi.nlm.nih.gov/42012347/) |
| 4 | 医学影像 AI | 9/10 | 无COPD个体中CT肺气肿与基于深度学习的椎体骨丢失：MESA研究结果。 | Radiology | [PubMed](https://pubmed.ncbi.nlm.nih.gov/42012343/) |
| 5 | 医学影像 AI | 9/10 | 用于自动放射学印象生成的微调大语言模型：一项多中心评估。 | Radiology. Artificial intelligence | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41983921/) |
| 6 | 运动 AI | 8/10 | 以自主机器人击败精英乒乓球运动员 | Nature | [PubMed](https://pubmed.ncbi.nlm.nih.gov/42020866/) |
| 7 | 医学影像 AI | 8/10 | 元编码器：一种用于癌症检测中多种病理基础模型的统一集成框架。 | Nature communications | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41986341/) |
| 8 | 医学影像 AI | 8/10 | ****  
ONCO-RADS引导的大型语言模型用于全身影像报告中偶然发现的提... | Radiology. Imaging cancer | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41995468/) |
| 9 | 医学影像 AI | 8/10 | 认知偏倚提示效应对大型语言模型在放射学委员会风格考试题目中准确性的影响 | Radiology. Artificial intelligence | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41983923/) |
| 10 | 可穿戴/传感器 AI | 7/10 | 基于自监督学习的可穿戴拇指套：利用少量可拉伸传感器和小样本数据实现可切换手指任务... | Science advances | [PubMed](https://pubmed.ncbi.nlm.nih.gov/42018630/) |
| 11 | 临床决策/预测 AI | 7/10 | 作者更正：PanMETAI——一种基于核磁共振代谢组学准确诊断胰腺癌的高性能表格... | Nature communications | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41997919/) |
| 12 | 临床决策/预测 AI | 6/10 | 使用全科医学基准评估大型语言模型的临床能力。 | Nature communications | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41991515/) |
| 13 | 临床决策/预测 AI | 6/10 | 卷积神经网络以诊断级精度量化结核分枝杆菌的抗生素耐药性并预测治疗反应。 | Nature communications | [PubMed](https://pubmed.ncbi.nlm.nih.gov/42031767/) |
| 14 | 医学影像 AI | 6/10 | 通过自监督正交学习增强生物医学光学体积成像。 | Science advances | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41984965/) |

---

## 3. 文献详情

### 1. DxDirector：一个驱动全流程临床诊断的代理型大型语言模型

- **英文标题**: DxDirector: an agentic large language model driving the full-process clinical diagnosis.
- **期刊**: Nature communications (2026)
- **作者**: Shicheng Xu, Xin Huang, Zihao Wei
- **类别**: 临床决策/预测 AI
- **相关性**: 9/10 — LLM自主驱动全流程临床诊断，直接服务于临床决策，AI是核心贡献。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/42026083/

**中文摘要**: 真实世界的临床诊断通常始于患者模糊的主诉，需要经过反复推理和检测才能明确。尽管大语言模型在特定医学查询中日益发挥作用，但目前仍缺乏自主驱动整个诊断流程的能力，这限制了其显著减轻医生工作负荷的潜力。本文提出DxDirector-7B——一种具备高级慢速思考能力的智能体大语言模型，能够自主导航完整的诊断过程。与现有辅助系统不同，该模型可自主确定最优诊断策略，仅在必要时请求医生参与临床操作。在涵盖罕见病和复杂真实病例的评估中，DxDirector-7B相较于参数规模显著更大的先进医学及通用大语言模型，实现了更优的诊断准确率。关键的是，该模型在维持高风险场景的稳健安全与问责框架的同时，大幅减少了医生参与度。这些结果表明了一种范式转变：人工智能能够有效主导临床推理，为提升诊断效率和可及性提供可扩展的解决方案。

**英文摘要**: Clinical diagnosis in the real world often begins with ambiguous patient complaints that require iterative reasoning and testing. While large language models (LLMs) increasingly assist with specific medical queries, they currently lack the ability to autonomously drive this entire diagnostic workflow, limiting their potential to significantly alleviate physician workload. Here we present DxDirector-7B, an agentic LLM designed to navigate the full diagnostic process through advanced slow thinking capabilities. Unlike existing assistants, our model autonomously determines optimal diagnostic strategies, requesting physician intervention only for necessary clinical operations. In evaluations spanning rare diseases and complex real-world cases, DxDirector-7B achieves superior diagnostic accuracy compared to state-of-the-art medical and general-purpose LLMs with significantly larger parameters. Crucially, it drastically reduces physician involvement while maintaining a robust safety and accountability framework for high-risk conditions. These results demonstrate a paradigm shift where AI effectively leads clinical reasoning, offering a scalable solution to enhance diagnostic efficiency and accessibility.

---

### 2. 基于肿瘤和内脏脂肪组织CT特征的深度学习模型预测浆膜浸润型胃癌根治术后腹膜转移风险

- **英文标题**: Deep Learning Model Based on Tumor and Visceral Adipose Tissue CT Features for Predicting Peritoneal Metastasis Risk after Radical Gastrectomy in Serosa-Invasive Gastric Cancer.
- **期刊**: Radiology. Imaging cancer (2026)
- **作者**: Yueyue Li, Ximiao Wang, Qiuying Chen
- **类别**: 医学影像 AI
- **相关性**: 9/10 — 深度学习结合CT影像特征构建临床预测模型，直接用于胃癌术后腹膜转移风险预测，AI是核心贡献且临床价值明确。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/42029163/

**中文摘要**: **目的**  
开发并验证一种整合肿瘤与内脏脂肪组织（VAT）CT扫描特征及临床指标的深度学习模型，用于预测浆膜浸润型胃癌术后腹膜转移。  

**材料与方法**  
本多中心回顾性研究纳入2008年4月至2018年1月期间经病理确诊的浆膜浸润型胃癌患者。患者被分为训练集、内部测试集和独立外部测试集。在术前CT图像上分割肿瘤区域及VAT区域。采用ResNet18网络提取深度特征。通过融合肿瘤与VAT的深度学习特征生成联合深度学习特征（F-DLS），并基于稀疏贝叶斯极限学习机将临床变量整合至多模态深度学习影像组学模型（MDLR）中。通过受试者工作特征曲线、综合判别改善指数、校准曲线、决策曲线分析及无复发生存期评估模型性能。  

**结果**  
共纳入416例患者（平均年龄56.6岁±11.6岁，男性占66.1%）。F-DLS在内部测试集和外部测试集中的受试者工作特征曲线下面积（AUC）分别为0.81（95%CI: 0.73, 0.88）和0.79（95%CI: 0.71, 0.86）。与肿瘤组织DLS及VAT-DLS相比，F-DLS的AUC数值更高但无统计学差异。MDLR表现出最强的预测性能，在内部测试集和外部测试集中的AUC分别为0.86（95%CI: 0.79, 0.92）和0.86（95%CI: 0.78, 0.92）。MDLR显著优于纯临床模型及纯深度学习模型（综合判别改善指数，P < .001），校准曲线显示良好一致性，决策曲线分析表明其具有较高的净获益。MDLR识别的高风险患者无复发生存期显著缩短（log-rank检验，P < .001）。  

**结论**  
整合CT扫描特征与临床指标的MDLR能够非侵入性地预测浆膜浸润型胃癌的腹膜转移风险，并可能有助于术后风险分层。  

**关键词**  
胃癌，腹膜转移，CT，内脏脂肪组织，深度学习  

本文提供在线补充材料。© RSNA, 2026。

**英文摘要**: Purpose To develop and validate a deep learning model integrating tumor and visceral adipose tissue (VAT) CT scan features with clinical indicators to predict postoperative peritoneal metastasis in serosa-invasive gastric cancer. Materials and Methods This multicenter, retrospective study between April 2008 and January 2018 included patients with pathologically confirmed serosa-invasive gastric cancer. Patients were divided into training, internal test, and independent external test sets. Tumor and VAT regions were segmented at preoperative CT. Deep features were extracted using a ResNet18 network. A fused tumor-VAT deep learning signature (F-DLS) was generated, incorporating clinical variables into a multimodal deep learning radiomics model (MDLR) using a sparse Bayesian extreme learning machine. Model performance was assessed using receiver operating characteristic curve, integrated discrimination improvement, calibration, decision curve analysis, and recurrence-free survival. Results Among 416 patients (mean age, 56.6 years ± 11.6; 66.1% male patients), the F-DLS achieved area under the receiver operating characteristic curve (AUC) values of 0.81 (95% CI: 0.73, 0.88) in the internal test set and 0.79 (95% CI: 0.71, 0.86) in the external test set. Compared with the tumor tissue DLS and VAT-DLS, the F-DLS showed numerically higher AUCs without statistical significance. The MDLR achieved the strongest predictive performance, with AUCs of 0.86 (95% CI: 0.79, 0.92) in the internal test set and 0.86 (95% CI: 0.78, 0.92) in the external test set. The MDLR statistically significantly outperformed clinical and deep learning-only models (integrated discrimination improvement, P < .001), showed good calibration, and provided favorable net benefit on decision curve analysis. High-risk patients identified by the MDLR had significantly shorter recurrence-free survival (log-rank P < .001). Conclusion The MDLR integrating CT scan features and clinical indicators enabled noninvasive prediction of peritoneal metastasis risk in serosa-invasive gastric cancer and may facilitate postoperative risk stratification. Keywords: Gastric Cancer, Peritoneal Metastasis, CT, Visceral Adipose Tissue, Deep Learning Supplemental material is available for this article. © RSNA, 2026.

---

### 3. 一种用于冠状动脉CT血管成像中量化冠状动脉斑块的全自动深度学习模型。

- **英文标题**: A Fully Automated Deep Learning Model for Quantifying Coronary Plaque at Coronary CT Angiography.
- **期刊**: Radiology (2026)
- **作者**: Qian Chen, Fan Zhou, Wei Xing
- **类别**: 医学影像 AI
- **相关性**: 9/10 — 深度学习全自动量化冠脉斑块，直接用于CT血管造影影像诊断并评估预后，AI为核心贡献，符合医学影像AI及临床预测模型方向。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/42012347/

**中文摘要**: **背景** 用于冠状动脉CT血管成像（CCTA）斑块量化的深度学习（DL）模型在常规临床实践中鲜少应用。

**目的** 开发一种全自动的深度学习模型用于冠状动脉斑块量化，并评估其预后价值。

**材料与方法** 回顾性纳入2009年6月至2024年5月期间来自中国17家医院并接受CCTA检查的患者。将这些患者的影像数据按7:3比例随机分为训练集和验证集，以开发一种用于量化斑块体积（PV）的全自动深度学习模型——PlaqueSegNet。随后，该模型在四个独立数据集中接受外部测试：配对CCTA和血管内超声（IVUS）数据集、采用不同CT扫描仪采集的中国CT衍生的血流储备分数（CT-FFR）研究3子数据集、间隔3个月内的系列CCTA数据集以及光子计数CT数据集。使用哈雷尔C指数在中国CT-FFR研究2、中国CT-FFR研究1.1及一个系列CCTA队列这三个队列中评估PlaqueSegNet的预后价值。

**结果** 训练数据集包含1409例患者（平均年龄63岁±10 [标准差]；男性795例），内部验证数据集包含604例患者（平均年龄63岁±10；男性329例）。在四个外部数据集中，PlaqueSegNet在量化斑块体积方面与IVUS及专家阅片者显示出极佳的一致性和可重复性（所有组内相关系数均>0.90），尽管Bland-Altman分析中一致性界限较宽。PlaqueSegNet预测主要不良心脏事件（MACE）的C指数为：中国CT-FFR研究2（中位随访2.3年）中为0.64（95% CI：0.62, 0.67），中国CT-FFR研究1.1（中位随访5.3年）中为0.65（95% CI：0.60, 0.69），系列CCTA队列（中位随访3.6年）中为0.74（95% CI：0.66, 0.84）。

**结论** PlaqueSegNet能够从CCTA图像中实现全自动的斑块体积测量，其结果与专家阅片者和IVUS高度一致，并对未来MACE具有预后价值。

**临床试验注册号** NCT06025305 © RSNA, 2026

**补充材料** 可在线获取本文补充材料。另见本期Williams的述评。

**英文摘要**: Background Deep learning (DL) models for quantifying plaques at coronary CT angiography (CCTA) are rarely used in routine clinical care. Purpose To develop a fully automated DL model for coronary plaque quantification and to evaluate its prognostic value. Materials and Methods Patients who underwent CCTA were retrospectively enrolled from 17 Chinese hospitals between June 2009 and May 2024. The imaging data of these patients were randomly split into training and validation sets at a 7:3 ratio to develop a fully automated DL model for quantifying plaque volume (PV), PlaqueSegNet, which was subsequently externally tested with four independent datasets: a paired CCTA and intravascular US (IVUS) dataset, a subset of the China CT-derived fractional flow reserve (CT-FFR) study 3 dataset collected with different CT scanners, a serial CCTA dataset within a 3-month interval, and a photon-counting CT dataset. The prognostic value of PlaqueSegNet was evaluated using the Harrell C-index in three cohorts: China CT-FFR study 2, China CT-FFR study 1.1, and a serial CCTA cohort. Results The training dataset included 1409 patients (mean age, 63 years ± 10 [SD]; 795 male), and the internal validation dataset included 604 patients (mean age, 63 years ± 10; 329 male). PlaqueSegNet demonstrated excellent agreement and reproducibility for quantifying PV against IVUS and expert readers across the four external datasets (all intraclass correlation coefficients, >0.90), albeit with wide limits of agreement in Bland-Altman analysis. The C-index of PlaqueSegNet for predicting major adverse cardiac events (MACEs) was 0.64 (95% CI: 0.62, 0.67) in the China CT-FFR study 2 (median follow-up, 2.3 years), 0.65 (95% CI: 0.60, 0.69) in the China CT-FFR study 1.1 (median follow-up, 5.3 years), and 0.74 (95% CI: 0.66, 0.84) in the serial CCTA cohort (median follow-up, 3.6 years). Conclusion PlaqueSegNet provided fully automated measurements of PV from CCTA that closely agreed with expert readers and IVUS and carried prognostic value for future MACEs. Clinical trial registration no. NCT06025305 © RSNA, 2026 Supplemental material is available for this article. See also the editorial by Williams in this issue.

---

### 4. 无COPD个体中CT肺气肿与基于深度学习的椎体骨丢失：MESA研究结果。

- **英文标题**: CT Emphysema and Deep Learning-derived Vertebral Bone Loss in Individuals without COPD: Findings from MESA.
- **期刊**: Radiology (2026)
- **作者**: Elena Ghotbi, Quincy A Hathaway, Payam Jannatdoust
- **类别**: 医学影像 AI
- **相关性**: 9/10 — 深度学习用于CT影像骨流失与肺气肿分析，直接关联临床早期标志物识别，属于医学影像AI核心应用
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/42012343/

**中文摘要**: 背景： 在无临床慢性阻塞性肺疾病（COPD）的个体中，基于胸部CT量化的亚临床肺气肿样改变是否与骨密度（BMD）下降相关尚不明确。  
目的： 通过基于深度学习的大样本多民族队列影像分析，识别肺与骨骼健康的早期影像标志物。  
材料与方法： 对前瞻性动脉粥样硬化多民族研究（MESA）第5次及第6次随访期间（2010年4月至2018年3月）采用COPD亚人群与中间结局指标研究（SPIROMICS）方案获取的胸部CT扫描进行二次分析。在每次随访时量化肺气肿百分比，并使用经验证的深度学习分割模型评估胸椎BMD。排除基于肺功能检查或自我报告确诊为临床COPD的参与者。构建线性混合效应模型，调整人口学特征及协变量（包括吸烟状况、体力活动、扫描机型），并分析性别的交互效应。  
结果： 横断面分析纳入2312名参与者（中位年龄67岁[IQR，61-75岁]；1285名女性），纵向研究纳入1109名有可用随访CT数据的参与者（中位年龄65岁[IQR，60-72岁]；614名女性）。较高的肺气肿样改变百分比与较低的BMD横断面相关（β = -1.14 mg/cm³ [95% CI: -1.76, -0.53]），并与更大的年均BMD丢失量纵向相关（β = -0.07 mg/cm³/年 [95% CI: -0.13, -0.01]）。性别（P < .001）及种族/民族（P = .049）的交互效应显著。分层模型中，男性（β = -0.38 mg/cm³/年 [95% CI: -0.48, -0.28]）及黑人/非裔美国人参与者（β = -0.24 mg/cm³/年 [95% CI: -0.39, -0.09]）中关联显著。Johnson-Neyman法显示男性肺气肿阈值>2.7%时BMD开始下降，对应39%的男性参与者。调整肺功能及慢性呼吸系统症状后结果仍稳健。  
结论： 在无COPD的个体中，较高的肺气肿样改变百分比与更快的椎体骨丢失独立相关，尤其在男性中更为显著，提示亚临床肺气肿可能是系统性骨骼衰退的新型影像标志物。  
临床试验注册号：NCT0000548  
© RSNA, 2026  
本文附有补充材料。同时见本期Fukuda的述评。

**英文摘要**: Background It is unknown whether subclinical emphysema-like changes, quantified at chest CT, are associated with loss of bone mineral density (BMD) in individuals without clinical chronic obstructive pulmonary disease (COPD). Purpose To identify early imaging markers of lung and bone health using deep learning-based imaging analysis in a large multiethnic cohort. Materials and Methods Chest CT scans obtained using the SubPopulations and InteRmediate Outcome Measures in COPD Study (SPIROMICS) protocol during examination 5 and 6 of the prospective Multi-Ethnic Study of Atherosclerosis (MESA) were secondarily analyzed (April 2010-March 2018). Percentage emphysema was quantified at examination, and thoracic vertebral BMD was assessed at both examinations using a validated deep learning-based segmentation model. Participants with clinical COPD as determined on the basis of spirometry or self-reports were excluded. Linear mixed-effects models were constructed and adjusted for demographic characteristics and covariates, including smoking status, physical activity, and scanner type, and the interaction effect of sex was analyzed. Results The cross-sectional analysis included 2312 participants (median age, 67 years [IQR, 61-75 years]; 1285 female participants), and the longitudinal study included 1109 participants (median age, 65 years [IQR, 60-72 years]; 614 female participants) with available follow-up CT data. A greater percentage of emphysema-like changes was associated with lower BMD (β = -1.14 mg/cm 3 [95% CI: -1.76, -0.53]) cross-sectionally and with greater annual BMD loss (β = -0.07 mg/cm 3 per year [95% CI: -0.13, -0.01]) longitudinally. Interaction effects were identified for sex ( P < .001) and race or ethnicity ( P = .049). In stratified models, the associations were significant for men (β = -0.38 mg/cm 3 per year [95% CI: -0.48, -0.28]) and Black/African American participants (β = -0.24 mg/cm 3 per year [95% CI: -0.39, -0.09]). The Johnson-Neyman method revealed more than 2.7% emphysema as a threshold for a decrease in BMD among men, which corresponded to 39% of the male participants. The results remained robust after adjustment for pulmonary function and chronic respiratory symptoms. Conclusion In individuals without COPD, a greater percentage of emphysema-like changes was independently associated with faster vertebral bone loss, particularly in men, suggesting that subclinical emphysema may be a novel imaging marker of systemic skeletal decline. Clinical trial registration no. NCT0000548 © RSNA, 2026 Supplemental material is available for this article. See also the editorial by Fukuda in this issue.

---

### 5. 用于自动放射学印象生成的微调大语言模型：一项多中心评估。

- **英文标题**: Fine-Tuned Large Language Models for Automated Radiology Impression Generation: A Multicenter Evaluation.
- **期刊**: Radiology. Artificial intelligence (2026)
- **作者**: Mingyang Li, Yaning Wang, Zheng Miao
- **类别**: 医学影像 AI
- **相关性**: 9/10 — LLM微调用于放射学印象自动生成，直接服务医学影像临床报告，AI为核心贡献
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41983921/

**中文摘要**: **目的**  
开发一个经过微调的大型语言模型（医学影像报告助手，MIRA），并评估其在基于多中心数据生成放射学印象方面的准确性、报告效率和临床适用性。  

**材料与方法**  
回顾性收集一个多中心数据集，包含来自中国22个省份42家医院（2019年1月至2024年8月）的187万份放射学报告（包括CT、MRI和数字X线摄影数据）。该数据集用于通过基于提示的策略对大型语言模型进行微调。评估框架包含自动化评估和人工评估指标。放射科医生对内部数据集、外部数据集以及三个开源数据集进行评估，以比较微调后的LLM与GPT-4o生成的印象。来自六个中心的24名放射科医生对MIRA生成的印象与参考印象进行盲法比较，以评估评估者间的一致性和草拟效率。数据分析采用适当的参数/非参数检验和χ²检验，多重比较采用Holm-Bonferroni校正。  

**结果**  
内部测试集包含78,544份报告的数据（中位年龄52岁[IQR, 35-65]，39,351名男性），外部测试集包含27,471份报告的数据（中位年龄53岁[IQR, 37-66]，13,955名男性）。基于部位/模态的提示策略提高了相似性（P < .001）：在最优设置下，内部BERTScore-F/句子相似性分别为0.92/0.92，外部为0.82/0.80；人工评估（n = 2,327）显示，MIRA在相似性和F1分数上均优于GPT-4o（P < .001）。在69.0%（1,657/2,400）的盲法比较中，MIRA生成的印象评分至少与参考印象相当，每份报告草拟时间减少0.46分钟，并提高了放射科医生间的一致性（P < .001）。  

**结论**  
MIRA作为一种采用基于提示策略进行微调的大型语言模型，能够在多中心环境中生成与临床对齐的放射学印象，提高了准确性、效率和报告一致性。© Authors 2026. 由北美放射学会根据CC BY 4.0许可发布。

**英文摘要**: Purpose To develop a fine-tuned large language model (Medical Imaging Report Assistant, MIRA) and evaluate its performance in generating radiology impressions from multicenter data with respect to accuracy, reporting efficiency, and clinical applicability. Materials and Methods A retrospective multicenter dataset comprising 1.87 million radiology reports (including CT, MRI, and digital radiography data) from 42 hospitals across 22 provinces in China (January 2019 to August 2024) was compiled. The dataset was used to fine-tune an LLM via a prompt-based strategy. The evaluation framework incorporated both automated and human evaluation metrics. Radiologists evaluated internal and external datasets and three open-source datasets to compare impressions generated by the fine-tuned LLM and GPT-4o. Twenty-four radiologists from six centers performed blinded comparisons of MIRA generated and reference impressions to assess interrater consistency and drafting efficiency. Data were analyzed using appropriate parametric/nonparametric tests and χ 2 tests, with Holm-Bonferroni correction for multiple comparisons. Results The internal test set included data for 78,544 reports, median age, 52 years [IQR, 35-65], 39,351 males) and the external test set included data for (27,471 reports, median age, 53 years [IQR, 37-66], 13,955 males). Site/modality-aware prompting improved similarity ( P < .001): internal BERTScore-F/Sentence Similarity 0.92/0.92, external 0.82/0.80 under optimal settings; human evaluation ( n = 2,327) showed MIRA beat GPT-4o on both similarity and F1 score ( P < .001). MIRA-generated impressions were rated as at least as good as the reference impressions in 69.0% of blinded comparisons (1,657/2,400), reduced draft time by 0.46 min per report, and increased interradiologist agreement ( P < .001). Conclusion MIRA, a fine-tuned LLM using a prompt-based strategy, generated clinically aligned radiology impressions in multicenter settings, improving accuracy, efficiency, and reporting consistency. © The Authors 2026. Published by the Radiological Society of North America under a CC BY 4.0 license.

---

### 6. 以自主机器人击败精英乒乓球运动员

- **英文标题**: Outplaying elite table tennis players with an autonomous robot.
- **期刊**: Nature (2026)
- **作者**: Peter D&#xfc;rr, Mireille El Gheche, Guilherme Jorge Maeda
- **类别**: 运动 AI
- **相关性**: 8/10 — 运动AI核心应用：自主机器人击败顶尖乒乓球运动员，AI驱动实时对抗决策与物理交互，高影响力。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/42020866/

**中文摘要**: 人工智能系统如今在许多电脑游戏中已能挑战甚至超越人类专家¹²。然而，乒乓球等实体实时运动仍是一项重大开放挑战，因其要求在障碍物附近及人类反应时间极限内进行快速、精准且具有对抗性的交互³。在此，我们介绍Ace——据我们所知，这是首个能与精英人类乒乓球选手匹敌的实体自主系统。Ace通过采用基于事件的视觉传感器⁴的新型高速感知系统、基于无模型强化学习的新型控制系统，以及最先进的高速机器人硬件，应对实体实时交互的挑战。在官方比赛规则下，Ace在与精英及职业选手的对战中取得数次胜利，并展现出对高速、高旋转球持续回击的能力。这些结果凸显了物理AI智能体执行复杂实时交互任务的潜力，预示着在需要快速精准人机交互的领域具有更广泛的应用前景。

**英文摘要**: Artificial intelligence (AI) systems now challenge or surpass human experts in many computer games 1,2 . Physical and real-time sports such as table tennis, however, remain a major open challenge because of their requirements for fast, precise and adversarial interactions near obstacles and at the edge of human reaction time 3 . Here we present Ace, to our knowledge the first real-world autonomous system competitive with elite human table tennis players. Ace addresses the challenges of physical real-time interaction through a new, high-speed perception system using event-based vision sensors 4 , and a new control system based on model-free reinforcement learning, as well as state-of-the-art high-speed robot hardware. Evaluated in matches against elite and professional players under official competition rules, Ace achieved several victories and demonstrated consistent returns of high-speed, high-spin shots. These results highlight the potential of physical AI agents to perform complex, real-time interactive tasks, suggesting broader applications in domains requiring fast, precise human-robot interaction.

---

### 7. 元编码器：一种用于癌症检测中多种病理基础模型的统一集成框架。

- **英文标题**: Meta-encoder: a unified integration framework for multiple pathological foundation models in cancer detection.
- **期刊**: Nature communications (2026)
- **作者**: Ruitian Gao, Zhaochang Yang, Xin Yuan
- **类别**: 医学影像 AI
- **相关性**: 8/10 — 病理影像基础模型集成框架，直接用于癌症检测的临床AI应用，AI为核心贡献。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41986341/

**中文摘要**: 多种病理学基础模型的涌现，使肿瘤学领域的计算病理学任务得以发展，包括肿瘤分型、癌症预后、生物标志物预测、基因表达预测等。然而，模型架构和数据源的差异阻碍了下游任务性能的一致性，并使得集中式训练复杂化。具体而言，数据共享的缺乏使得利用合并数据重新训练基础模型不可行。为此，我们提出了元编码器（Meta-Encoder）——一个统一框架，能够整合多种病理学基础模型的特征以生成综合表征，在癌症检测的下游任务中展现出优于单一基础模型的性能。尽管单一模型足以应对低复杂度的单变量任务（如癌症诊断和预后），但元编码器始终能与表现最佳的单一模型相媲美，从而缓解了模型选择的困扰。对于肿瘤组织内多重蛋白与基因表达预测等高维任务，我们元编码器框架中基于注意力的策略相比单一模型展现出显著优势，在性能与效率之间实现了最优平衡。通过利用多种基础模型的互补优势，元编码器增强了病理图像的分子表征能力，从而推动精准肿瘤学的发展。

**英文摘要**: The emergence of diverse pathological foundation models has empowered computational pathology tasks within the field of oncology, including tumor subtyping, cancer prognosis, biomarker prediction, gene expression prediction, and so on. However, variations in model architecture and data sources hinder consistent downstream performance and complicate centralized training. Specifically, the lack of data sharing makes retraining foundation models with pooled data infeasible. Here, we propose the Meta-Encoder, a unified framework that integrates features from multiple pathological foundation models to generate a comprehensive representation, achieving superior performance in downstream cancer detection tasks compared to single foundation models. While single models suffice for low-complexity univariate tasks such as cancer diagnosis and prognosis, the Meta-Encoder consistently rivals the best-performing single model, alleviating concerns over model selection. For high-dimensional tasks such as multiplex protein and gene expression prediction within tumor tissues, the attention-based strategies of our Meta-Encoder framework demonstrate substantial advantages over single models, offering an optimal balance of performance and efficiency. By harnessing the complementary strengths of multiple foundation models, the Meta-Encoder enhance the molecular characterization of pathology images, thereby advancing precision oncology.

---

### 8. ****  
ONCO-RADS引导的大型语言模型用于全身影像报告中偶然发现的提取与分类。

- **英文标题**: ONCO-RADS-guided Large Language Models for Extraction and Classification of Incidental Findings on Whole-Body Imaging Reports.
- **期刊**: Radiology. Imaging cancer (2026)
- **作者**: Mickael Tordjman, Murat Yuce, Zelong Liu
- **类别**: 医学影像 AI
- **相关性**: 8/10 — LLM结合ONCO-RADS系统用于提取和分类全身影像报告中的偶然发现，直接服务于临床决策，AI是核心应用。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41995468/

**中文摘要**: **目的** 评估基于大语言模型（LLM）的策略在全身（WB）影像报告中提取与分类偶然发现方面的性能，特别是结合肿瘤相关发现报告与数据系统（ONCO-RADS）的策略。

**材料与方法** 在这项回顾性双中心研究中，作者纳入了2016年1月至2023年12月期间一家转诊中心（内部数据集）的所有全身MRI报告。两名观察者提取了所有偶然发现，并使用患者记录确认最终诊断。首先，作者评估了ONCO-RADS的性能以及六名放射科医生对其偶然发现分类的可重复性。然后，作者评估了三种基于LLM的策略的准确性：（a）微调的DeBERTa/医学命名实体识别（NER）模型；（b）零样本LLM（ChatGPT-o1 [OpenAI]、Gemini-2.5-Pro [Google]）；以及（c）使用ONCO-RADS对这些LLM进行参考引导提示。随后，作者将这些策略扩展到一个包含605份报告的外部数据集，这些报告涉及多种影像技术（405份全身MRI；100份氟脱氧葡萄糖PET/CT；100份胸腹盆腔CT扫描），时间跨度为2022年1月至2025年1月。

**结果** 内部数据集包含823名患者（平均年龄63.7岁±11.7 [标准差]；457名男性），共1488份全身MRI报告。ONCO-RADS偶然发现分类的观察者间平均可重复性极佳（Cohen κ=0.87）。每份报告的准确率方面，ONCO-RADS引导的LLM（ChatGPT-o1为95.6% [158份中的151份]，Gemini-2.5-Pro为86.7% [158份中的137份]）高于医学NER模型（69.0% [158份中的109份]）和零样本LLM（ChatGPT-o1为57.0% [158份中的90份]，Gemini-2.5-Pro为70.9% [158份中的112份]）（P < .001）。在外部测试集（平均年龄60.6岁±12.9；330名男性）中，ONCO-RADS引导的ChatGPT-o1（83.5% [605份中的505份]）和Gemini-2.5-Pro（82.0% [605份中的496份]）每份报告的准确率高于无ONCO-RADS提示的模型（分别为63.1% [605份中的382份]和61.2% [605份中的370份]）以及医学NER模型（55.7% [605份中的337份]）（P < .001）。

**结论** 与零样本提示和医学NER相比，使用ONCO-RADS对LLM（ChatGPT-o1和Gemini-2.5-Pro）进行参考引导提示，改善了它们在全身影像报告中提取和分类偶然发现的性能。

**关键词**：大语言模型，偶然发现，全身MRI

本文可获取补充材料。© RSNA, 2026。

**英文摘要**: Purpose To evaluate large language model (LLM)-based strategy performance for extraction and classification of incidental findings from whole-body (WB) imaging reports, particularly strategies incorporating Oncologically Relevant Findings Reporting and Data System (ONCO-RADS). Materials and Methods In this retrospective bicenter study, authors included all WB MRI reports from January 2016 to December 2023 at a referral center (internal dataset). Two observers extracted all incidental findings, and patient records were used to confirm final diagnoses. First, authors evaluated ONCO-RADS performance and the reproducibility of its incidental finding classifications by six radiologists. Then, authors evaluated the accuracy of three LLM-based strategies: (a) a fine-tuned DeBERTa/medical named entity recognition (NER) model; (b) zero-shot LLMs (ChatGPT-o1 [OpenAI], Gemini-2.5-Pro [Google]); and (c) reference-guided prompting of these LLMs using ONCO-RADS. Authors then expanded these strategies to an external dataset of 605 reports with multiple imaging techniques (405 WB MRI; 100 fluorodeoxyglucose PET/CT; and 100 chest-abdomen-pelvis CT acquisitions) from January 2022 to January 2025. Results The internal dataset included 823 patients (mean age, 63.7 years ± 11.7 [SD]; 457 male patients) with 1488 WB MRI reports. The average interobserver reproducibility of ONCO-RADS incidental finding classifications was excellent (Cohen κ, 0.87). The per-report accuracies of ONCO-RADS-guided LLMs (95.6% [151 of 158] and 86.7% [137 of 158] for ChatGPT-o1 and Gemini-2.5-Pro, respectively) were higher than those of the medical NER (69.0% [109 of 158]) and zero-shot LLMs (57.0% [90 of 158] and 70.9% [112 of 158] for ChatGPT-o1 and Gemini-2.5-Pro, respectively) ( P < .001). In the external test set (mean age, 60.6 years ± 12.9; 330 male patients), the per-report accuracies of ONCO-RADS-guided ChatGPT-o1 (83.5% [505 of 605]) and Gemini-2.5-Pro (82.0% [496 of 605]) were higher than those of the models without ONCO-RADS prompting (63.1% [382 of 605] and 61.2% [370 of 605], respectively) and the medical NER (55.7% [337 of 605]) ( P < .001). Conclusion Reference-guided prompting of the LLMs ChatGPT-o1 and Gemini-2.5-Pro with ONCO-RADS improved their performance in extracting and classifying incidental findings on WB imaging reports compared with zero-shot prompting and medical NER. Keywords: Large Language Models, Incidental Findings, Whole-Body MRI Supplemental material is available for this article. © RSNA, 2026.

---

### 9. 认知偏倚提示效应对大型语言模型在放射学委员会风格考试题目中准确性的影响

- **英文标题**: Cognitively Biased Prompt Effects on Large Language Model Accuracy for Radiology Board-Style Examination Questions.
- **期刊**: Radiology. Artificial intelligence (2026)
- **作者**: Nicholas T Dietrich, Dhruv Patel, Joseph Bellissimo
- **类别**: 医学影像 AI
- **相关性**: 8/10 — 大语言模型用于放射学考试问题，评估认知偏见的影响，属于LLM临床决策支持方向，具有直接应用价值。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41983923/

**中文摘要**: 大型语言模型（LLMs）在放射学相关应用中的探索日益增多，但其对认知偏差的脆弱性仍未被充分揭示。本研究旨在探讨利用认知偏差的针对性提示是否会影响LLM在放射学委员会式题目中的准确性。研究对10种当代LLM进行了评估，测试条件包括基线状态及三种认知偏差提示（权威偏差提示、复杂性偏差提示和锚定偏差提示）下的200道文本题和200道多模态美国放射学委员会考试风格题目。此外，还评估了两种缓解策略：提示偏差审计和一次性缓解策略。在基线提示下，模型在文本题中的平均准确率为84.8%±5.5%（200题中答对154-186题），在多模态题中为59.5%±7.7%（200题中答对101-143题）。所有模型在受到认知偏差提示时准确率均下降：对于文本题，权威偏差提示、复杂性偏差提示和锚定偏差提示分别导致绝对下降21.1%、10.1%和4.4%（各P<0.001）；对于多模态题，分别下降44.9%、44.4%和39.6%（各P<0.001）。提示偏差审计使文本题准确率提升5.6%，多模态题提升15.8%；而一次性缓解策略使文本题准确率提升4.0%，多模态题提升24.9%。这些发现表明，LLM易受认知偏差输入的影响。©RSNA, 2026。

**英文摘要**: Large language models (LLMs) are increasingly explored for radiology-related applications, yet their vulnerability to cognitive biases remains undercharacterized. The aim of this study was to investigate whether targeted prompts exploiting cognitive biases degrade LLM accuracy on radiology board-style questions. Ten contemporary LLMs were evaluated on 200 text-based and 200 multimodal American Board of Radiology examination-style questions under baseline and three cognitive bias prompts: authority bias prompts (ABPs), complexity bias prompts (CBPs), and anchoring bias prompts (AnBPs). Two mitigation approaches, a prompt bias audit and a one-shot mitigation strategy, were also evaluated. Under baseline prompts, models achieved a mean accuracy of 84.8 ± 5.5% (154-186 of 200) for text-based and 59.5 ± 7.7% (101-143 of 200) for multimodal questions. All models showed reduced accuracy to cognitively biased prompts, with ABP, CBP, and AnBP yielding absolute declines of 21.1%, 10.1%, and 4.4%, respectively, for text questions ( P < .001 for each), and 44.9%, 44.4%, 39.6%, respectively, for multimodal questions ( P < .001 for each). The prompt bias audit increased accuracy by 5.6% for text-based and 15.8% for multimodal questions, while the one-shot mitigation yielded gains of 4.0% for text questions and 24.9% for multimodal questions. These findings demonstrate that LLMs are susceptible to cognitively biased inputs. ©RSNA, 2026.

---

### 10. 基于自监督学习的可穿戴拇指套：利用少量可拉伸传感器和小样本数据实现可切换手指任务。

- **英文标题**: Wearable thumb sleeves enabled by self-supervised learning with few stretchable sensors and few-shot data for switchable finger tasks.
- **期刊**: Science advances (2026)
- **作者**: Kunpeng Li, Wei Yue, Yunjian Guo
- **类别**: 可穿戴/传感器 AI
- **相关性**: 7/10 — 可穿戴智能传感器结合自监督学习实现手指任务识别，属于可穿戴设备AI领域，有运动/康复应用潜力，但未明确临床诊断场景，与标准中高分示例相比略弱。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/42018630/

**中文摘要**: 人类手指展现出卓越的灵巧性，是实现自然人机交互的理想媒介。传统方法要求每根手指配备至少一个设备，且依赖大量标注数据，往往将模型局限于单一用户和任务场景。本文提出一种结合自监督学习的可穿戴拇指套，该装置展现用户独立性与数据高效性，可识别多种与手指相关的任务。拇指套仅在拇指关节处配备两个可拉伸传感器，通过从无标注的随机拇指运动数据中学习潜在特征，并借助五样本标注数据进行微调，即可快速适配新用户与新任务，包括八方向指令输入和十指关节按键输入。该系统无需重建或重新训练模型，即可实现任务间的自由切换。本研究提出的方法在现实应用中展现出巨大潜力，可作为鼠标和键盘的替代方案，支持在线购物等任务操作。

**英文摘要**: Human fingers exhibiting remarkable dexterity are ideal for natural human-machine interaction. Traditional methods require at least one device per finger and extensive labeled data, often limiting models to a single user and task. Here, we propose a wearable thumb sleeve integrated with self-supervised learning, which exhibits user independence and data efficiency, enabling recognition of various finger-related tasks. The thumb sleeve is equipped with only two stretchable sensors at the thumb joints and learns latent features from unlabeled random thumb movement data. By using fine-tuning with five-shot labeled data, it can rapidly adapt to new users and tasks, including eight directional commands and 10 knuckle key inputs. It allows free switching between tasks without the need to reconstruct or retrain the model. The proposed approach demonstrates strong potential for real-world applications, serving as a substitute for a mouse and keyboard to enable tasks such as online shopping.

---

### 11. 作者更正：PanMETAI——一种基于核磁共振代谢组学准确诊断胰腺癌的高性能表格基础模型

- **英文标题**: Author Correction: PanMETAI - a high performance tabular foundation model for accurate pancreatic cancer diagnosis via NMR metabolomics.
- **期刊**: Nature communications (2026)
- **作者**: Dan-Ni Wu, Joey Jen, Erickson Fajiculay
- **类别**: 临床决策/预测 AI
- **相关性**: 7/10 — AI结合NMR代谢组学用于胰腺癌诊断，属于临床预测任务，有直接应用价值，但为作者更正版本，非原始研究。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41997919/

**中文摘要**: N/A

**英文摘要**: N/A

---

### 12. 使用全科医学基准评估大型语言模型的临床能力。

- **英文标题**: Evaluating clinical competencies of large language models with a general practice benchmark.
- **期刊**: Nature communications (2026)
- **作者**: Zheqing Li, Yiying Yang, Jiping Lang
- **类别**: 临床决策/预测 AI
- **相关性**: 6/10 — 评分失败，默认保留
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41991515/

**中文摘要**: 大语言模型（LLMs）在全科医学领域展现出巨大潜力。然而，现有的基准测试和评估框架主要依赖于考试型或简化的问答格式，缺乏与全科医学实际临床职责相对应的能力导向结构。因此，LLMs 在多大程度上能够可靠地履行全科医生（GPs）的职责仍不确定。本研究提出了一种新型评估框架，用于评估 LLMs 作为全科医生的能力。基于该框架，我们推出了一个全科医学基准（GPBench），其数据由领域专家根据常规临床实践标准精心标注。我们评估了十种最先进的 LLMs，并分析了它们的能力。研究结果表明，当前 LLMs 尚不适合在全科临床中自主部署，所有实际应用均需持续的人类监督；针对全科医生日常工作职责的进一步优化依然至关重要。

**英文摘要**: Large Language Models (LLMs) have demonstrated considerable potential in general practice. However, existing benchmarks and evaluation frameworks primarily depend on exam-style or simplified question-answer formats, lacking a competency-based structure aligned with the real-world clinical responsibilities encountered in general practice. Consequently, the extent to which LLMs can reliably fulfill the duties of general practitioners (GPs) remains uncertain. In this work, we propose a novel evaluation framework to assess the capability of LLMs to function as GPs. Based on this framework, we introduce a general practice benchmark (GPBench), whose data are meticulously annotated by domain experts in accordance with routine clinical practice standards. We evaluate ten state-of-the-art LLMs and analyze their competencies. Our findings indicate that current LLMs are not suitable for autonomous deployment in clinical general practice and that all realistic applications require continuous human oversight; further optimization specifically tailored to the daily responsibilities of GPs remains essential.

---

### 13. 卷积神经网络以诊断级精度量化结核分枝杆菌的抗生素耐药性并预测治疗反应。

- **英文标题**: Convolutional neural networks quantify antibiotic resistance in Mycobacterium tuberculosis with diagnostic grade accuracy and predict treatment response.
- **期刊**: Nature communications (2026)
- **作者**: Sanjana G Kulkarni, Anna G Green, Brendon C Mann
- **类别**: 临床决策/预测 AI
- **相关性**: 6/10 — 评分失败，默认保留
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/42031767/

**中文摘要**: 在基因组数据上训练机器学习（ML）模型以实现临床级诊断准确性，引起了广泛关注。许多成功的ML模型均在二分类任务上经过训练和验证，这是因为预测生物医学相关的连续变量难以优化。在本研究中，我们提出了卷积神经网络（CNN），用于根据结核分枝杆菌复合群（MTBC）基因序列预测八种抗生素的最低抑菌浓度（MIC）。通过纳入进化信息、蛋白质生化特性以及对罕见变异进行数据增强，我们构建的模型能够在一次药物浓度倍增范围内预测89%的MIC值。尽管模型仅基于世界卫生组织（WHO）MTBC耐药突变目录中≤52%的数据进行训练，但CNN却能准确预测该目录中97%分级突变的影响。在一组由373名利福平敏感结核分枝杆菌感染患者组成的队列中，CNN预测的利福平MIC值较高与不良治疗结果相关，这进一步证明了耐药阈值以下MIC的细微差异具有临床相关性。这些结果揭示了在多维生物数据编码的结核分枝杆菌耐药表型机器学习中蕴含的价值，并表明受领域知识启发的机器学习模型既能具有可解释性，也能达到临床级准确性。

**英文摘要**: There is considerable interest in training machine learning (ML) models on genomic data that achieve clinical grade diagnostic accuracy. Many successful ML models have been trained and validated on binary tasks because predicting biomedically relevant continuous variables is difficult to optimize. In this work, we present convolutional neural networks (CNNs) that predict minimum inhibitory concentrations (MICs) for eight antibiotics from Mycobacterium tuberculosis complex (MTBC) gene sequences. By including evolutionary information, protein biochemical properties, and data augmentation for rare variants, we build models that predict 89% of MICs within one drug concentration doubling. Although trained on ≤ 52% of the World Health Organization's (WHO) MTBC drug resistance mutation catalog data, the CNNs accurately predict the effects of 97% of the catalog's graded mutations. In a cohort of 373 patients with rifampicin-susceptible M. tuberculosis infections, higher CNN-predicted rifampicin MICs are associated with unfavorable treatment outcomes, providing additional evidence that subtle differences in MIC below the resistance threshold are clinically relevant. These results demonstrate the value of encoding multiple dimensions of biological data in machine learning of M. tuberculosis drug resistance phenotypes and that domain knowledge-inspired machine learning models can be both interpretable and reach clinical grade accuracy.

---

### 14. 通过自监督正交学习增强生物医学光学体积成像。

- **英文标题**: Enhancing biomedical optical volumetric imaging via self-supervised orthogonal learning.
- **期刊**: Science advances (2026)
- **作者**: Yuanjie Gu, Yiqun Wang, Ang Xuan
- **类别**: 医学影像 AI
- **相关性**: 6/10 — 文章涉及医学光学成像的深度学习降噪技术（AI核心贡献），但更偏向成像方法学改进而非直接临床诊断或预测任务，且未明确提及具体临床应用场景。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41984965/

**中文摘要**: 光学体积成像面临由光子预算限制、光散射和空间带宽积瓶颈引起的固有噪声问题，这些问题会降低结构保真度，且比平面成像中更为显著。虽然深度学习为降噪提供了潜力，但监督方法受限于配对数据集的不切实际性，而现有的自监督方法未能充分利用光学成像固有的体积结构冗余。在此，我们提出一种自监督体积生物医学成像降噪器（VALID），它利用内在的三维空间相干性，通过自监督正交学习框架实现高效体积降噪。VALID在多种成像模式中展现出稳健的降噪性能，包括双光子与三光子显微镜、光场显微镜和光学相干断层扫描，显著提升了深组织、多模态和动态成像场景中的结构保真度。通过结合计算效率与零样本适应性，VALID为体积图像增强建立了一种具有结构感知精度的变革性方法。

**英文摘要**: Optical volumetric imaging grapples with inherent noise problems arising from photon budget constraints, light scattering, and space-bandwidth product bottlenecks, all of which degrade structural fidelity and become even more pronounced than in planar imaging. While deep learning presents potential for denoising, supervised methods are hindered by the impracticality of paired datasets, and existing self-supervised approaches fail to fully exploit the intrinsic volumetric structural redundancy inherent to optical imaging. Here, we present a self-supervised volumetric biomedical imaging denoiser (VALID) that leverages intrinsic three-dimensional spatial coherence for highly efficient volumetric denoising through a self-supervised orthogonal learning framework. VALID demonstrates robust denoising performance across diverse imaging modalities, including two- and three-photon microscopy, light-field microscopy, and optical coherence tomography, substantially enhancing structural fidelity in deep-tissue, multimodal, and dynamic imaging scenarios. By combining computational efficiency with zero-shot adaptability, VALID establishes a transformative approach to volumetric image enhancement with structure-aware precision.

---


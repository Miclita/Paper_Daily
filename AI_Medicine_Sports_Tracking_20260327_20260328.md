# AI 医疗与运动领域顶刊追踪报告

**日期**: 2026-03-28  
**范围**: 最近 1 天 (从 2026/03/27)  
**期刊**: 17 本国际顶尖综合与医学期刊  

## 1. 统计概览

| 类别 | 数量 |
| :--- | :--- |
| 医学影像 AI | 2 篇 |
| **总计** | **2 篇** |

## 2. 文献概览

| # | 类别 | 相关性 | 中文标题 | 期刊 | 链接 |
| :--- | :--- | :---: | :--- | :--- | :--- |
| 1 | 医学影像 AI | 9/10 | 肿瘤合成：在任意分辨率和对比度的脑部MRI图像上进行整合的脑肿瘤与组织分割。 | Radiology. Imaging cancer | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41891822/) |
| 2 | 医学影像 AI | 9/10 | 生成式人工智能用于抗错配虚拟染色以加速组织病理学流程。 | Nature communications | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41888143/) |

---

## 3. 文献详情

### 1. 肿瘤合成：在任意分辨率和对比度的脑部MRI图像上进行整合的脑肿瘤与组织分割。

- **英文标题**: TumorSynth: Integrated Brain Tumor and Tissue Segmentation on Brain MRI Scans of Any Resolution and Contrast.
- **期刊**: Radiology. Imaging cancer (2026)
- **作者**: Jiaming Wu, Benjamin Billot, Fenqiang Zhao
- **类别**: 医学影像 AI
- **相关性**: 9/10 — 深度学习用于脑部MRI的肿瘤和组织分割，直接服务于医学影像诊断，AI是核心贡献。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41891822/

**中文摘要**: 目的 为了开发并验证一种深度神经网络，该网络能够同时分割脑肿瘤和解剖结构，无论输入扫描的对比度和分辨率如何，并且能够轻松适应未见过的模态。  
材料与方法 作者纳入了来自四个不同数据集的患者脑部MRI扫描，包括有脑肿瘤和无脑肿瘤的患者。患者数据被分为训练集和测试集。作者的方法 TumorSynth 结合了贝叶斯生成模型与……

**英文摘要**: Purpose To develop and validate a deep neural network that simultaneously segments brain tumors and anatomic structures, regardless of the contrast and resolution of the input scans, and can effortlessly adapt to unseen modalities. Materials and Methods The authors included various MRI scans from patients with and without brain tumors from four different datasets. Patient data were divided into a training set and a test set. The authors' method, TumorSynth, combines a Bayesian generative model and a deep learning segmentation model. The generative model creates paired synthetic labels and images with simulated tumors and brain tissues, providing a rich dataset for training the segmentation model. The authors quantitatively compared its performance with that of other widely used methods by calculating Dice similarity coefficients (DSCs). Results A total of 1971 patients with and without tumors were included in the study (training set, n = 351 patients; test set, n = 1620 patients). The median DSCs for segmentation (authors' method vs reference standard) were 0.89 (IQR, 0.83-0.95; P < .001) for the unaffected brain volume and 0.89 (IQR, 0.84-0.94; P < .001) for the tumor region. There were no differences in parcellation performance when an MRI sequence was missing ( P = .07). In cross-modality validation, the authors' method achieved DSC values of 0.88 for apparent diffusion coefficient, 0.85 for diffusion-weighted imaging, 0.80 for susceptibility-weighted imaging, and 0.79 for fractional anisotropy images. The authors observed a 4% false-positive rate when processing tumor-free MR images. Conclusion The authors developed a deep neural network for brain tumor and tissue segmentation, validated its performance across standard structural MRI sequences, and determined its generalizability to unseen data. Keywords: Segmentation, Neuro-Oncology, CNS, Deep Learning, Neurosurgery Supplemental material is available online for this article. © RSNA, 2026.

---

### 2. 生成式人工智能用于抗错配虚拟染色以加速组织病理学流程。

- **英文标题**: Generative AI for misalignment-resistant virtual staining to accelerate histopathology workflows.
- **期刊**: Nature communications (2026)
- **作者**: Jiabo Ma, Wenqiang Li, Jinbang Li
- **类别**: 医学影像 AI
- **相关性**: 9/10 — 生成式AI用于虚拟染色，直接优化病理诊断流程，属于医学影像AI的核心应用。
- **原文链接**: https://pubmed.ncbi.nlm.nih.gov/41888143/

**中文摘要**: 准确的组织病理学诊断通常依赖于多种化学染色，这一过程既耗时又消耗组织样本，并对环境造成负担。虽然虚拟染色提供了一种更快、更节省组织的替代方法，但其临床应用受到对完全对齐的配对数据需求的限制，而由于化学处理过程中组织的变形，这种数据难以获得。我们提出了一种稳健的虚拟染色框架，通过级联方式减轻空间错位问题。

**英文摘要**: Accurate histopathological diagnosis typically relies on multiple chemical stains, a process that is labor-intensive, tissue-consuming, and environmentally taxing. While virtual staining offers a faster, tissue-conserving alternative, its clinical adoption is hindered by the requirement for perfectly aligned paired data, which is difficult to obtain due to tissue distortion during chemical processing. We present a robust virtual staining framework that mitigates spatial mismatches through a cascaded registration mechanism. By decoupling image generation from spatial alignment, our method enables high-fidelity staining even from imperfectly paired or misaligned datasets without altering existing model architectures. Our approach significantly outperforms state-of-the-art models across five datasets, showing a remarkable 23.8% improvement in image quality for highly misaligned samples. In blinded evaluations, experienced pathologists achieved 52% accuracy in distinguishing virtual from chemical stains, indicating that the two were indistinguishable. This framework simplifies data acquisition and provides a scalable pathway for integrating virtual staining into routine clinical workflows.

---


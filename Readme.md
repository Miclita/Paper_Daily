# 参数配置表
## 使用 "Nature reviews*[Journal]" 覆盖所有 Nature 子刊评论
JOURNALS = [
    ("Nature", "Nature[Journal]"),
    ("Science", "Science[Journal]"),
    ("Cell", "Cell[Journal]"),
    ("Lancet", "Lancet[Journal]"),
    ("PNAS", "Proc Natl Acad Sci U S A[Journal]"),
    ("Nature Reviews", "Nature reviews*[Journal]"),
    ("Nature Communications", "Nat Commun[Journal]"),
    ("Science Advances", "Sci Adv[Journal]"),
    ("BMJ", "BMJ[Journal]"),
    ("JAMA", "JAMA[Journal]"),
    ("NEJM", "N Engl J Med[Journal]"),
    ("Current Biology", "Curr Biol[Journal]"),
    ("Radiology", "Radiology[Journal]"),
    ("PLoS Biology", "PLoS Biol[Journal]"),
    ("BMJ Global Health", "BMJ Glob Health[Journal]"),
    ("Nature Medicine", "Nat Med[Journal]"),
    ("PLOS Medicine", "PLoS Med[Journal]")
]

## 严格排除关键词 (用于减少噪音)
STRICT_EXCLUDE = [
    "archaeology", "ancient", "archaeological", "climate change", "global warming",
    "agriculture", "crop yield", "farming", "plant growth", "soil respiration",
    "finance", "economics", "stock market", "investment",
    "small molecule", "catalysis", "catalyst", "battery", "solar cell", "photovoltaic",
    "astronomical", "telescope", "galaxy", "cosmic", "rna sequencing", "dna computing",
    "materials science", "polymer", "semiconductor", "transistor", "circuit",
    "catalytic", "energy storage", "porous", "catalysis", "chemical synthesis",
    "climate", "meteorology", "geology",  "finance", "economics",
    "genomics", "biobank", "pharmacology", "nephrology",
    # 30天报告新增：基础生物与药研
    "genomics", "transcriptomics", "proteomics", "multi-omics", "CRISPR", 
    "drug target", "pharmacology", "drug discovery", "biomarker discovery",
    # 30天报告新增：纯临床与流行病
    "epidemiology", "public health", "health policy", "global burden", 
    "nephrology", "dialysis", "care bundles", "clinical management"
]

## 检索式
1. 核心视觉/多模态与 AI（必须与人体、姿态或医学影像相关）
vision_keywords = ["pose estimation", "human pose", "action recognition", "computer vision", "motion capture", "image segmentation", "foundation model", "multimodal", "visual-language", "vlm"]
    
2. 医疗关键词
medical_keywords = ["patient", "clinical", "hospital", "diagnosis", "therapy", "disease", "symptom", "prognosis", "outcome", "surgery", "oncology", "pathology", "radiology", "cardiology", "mri", "ct", "DR"]
    
3. 运动关键词
sports_keywords = ["exercise", "physical training", "athlete", "sports", "treadmill", "aerobic", "endurance", "muscle", "gait", "kinesiology", "biomechanics", "physical activity"]
    

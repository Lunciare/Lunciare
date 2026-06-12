## Hi, I'm Aleksandra Suvorova 👋

I'm a 3rd-year undergraduate at **HSE University** (Faculty of Computer Science, Moscow), specialising in Applied Data Analysis. My research sits at the intersection of **deep learning and medicine** — I care about building models that are not only accurate but clinically meaningful.

This summer I'm joining the **Shenzhen Loop Area Institute (SLAI)** at CUHK Shenzhen as a research intern, working on **speech-based biomarkers for cognitive decline and dementia detection**.

---

### Research Interests

- Speech & audio processing for clinical applications (dysarthria, dementia, atypical speech)
- Medical AI — from signal to clinical decision support
- Multimodal learning (audio + language + structured data)
- Interpretable and robust deep learning

---

### Tech Stack

**Languages & Core**
`Python` · `C++` · `SQL`

**ML / DL**
`PyTorch` · `PyTorch Geometric` · `scikit-learn` · `HuggingFace Transformers` · `segmentation_models_pytorch` · `Captum` · `Albumentations` · `Optuna` · `librosa` · `torchaudio`

**Data & Infra**
`NumPy` · `Pandas` · `FAISS` · `MLflow` · `Jupyter` · `Git`

---

### Featured Projects

| Project | Description | Stack |
|---|---|---|
| [multi-agent-medical-rag](https://github.com/Lunciare/multi-agent-medical-rag) | Multi-agent RAG system for clinical decision support. Routes queries to specialist agents over a FAISS-indexed medical knowledge base; intercepts emergency and prescription-sensitive queries. | Python · FAISS · LLMs |
| [genomic-variant-gnn](https://github.com/Lunciare/genomic-variant-gnn) | Pathogenic-vs-benign classification of ClinVar DNA variants from 2,048-bp of sequence context, using a GNN that treats fixed-length sequence windows as graph nodes (with a CNN baseline for an honest comparison). A deliberately modest, research-grade result — test ROC-AUC 0.673, essentially tied with the untuned baseline (0.665); interpretability surfaces CpG-rich motifs, consistent with methylation-hotspot biology. | PyTorch · PyTorch Geometric · Optuna · Captum |
| [skin-lesion-segmentation-unet](https://github.com/Lunciare/skin-lesion-segmentation-unet) | Per-pixel segmentation of skin lesions on ISIC 2018 dermoscopy. A from-scratch U-Net compared, on an identical pipeline, against an ImageNet-pretrained ResNet-34 encoder, with Integrated-Gradients maps to check the model keys on lesion tissue rather than on rulers and bubbles. Pretrained encoder reaches Dice 0.903 vs 0.877 from scratch, and gets there ~8× faster. | PyTorch · segmentation_models_pytorch · Captum |
| [dnabert-promoter-rl](https://github.com/Lunciare/dnabert-promoter-rl) | Fine-tunes DNABERT-2 into a promoter classifier (ROC-AUC 0.9946; LoRA matches it while training ~0.13 % of the parameters), then uses that classifier as a reward model for RL sequence design. The agent reached ~0.995 reward by exploiting the classifier rather than generating real promoters — reward hacking, diagnosed via GC-content analysis. | DNABERT-2 · LoRA · REINFORCE / PPO |
| [Music × Mental Health Clustering](https://github.com/Lunciare/Music_Mental_Health_Clustering_Interactive_Application) | Interactive application for clustering mental health survey respondents by music-listening behaviour. Built in collaboration with two co-authors. | C++ |
| [Neural Networks Course Project](https://github.com/Lunciare/Neural_Networks_Course_Project1) | Course project from HSE's Neural Networks curriculum. | C++ |

---

### Education & Affiliations

- **HSE University** — B.Sc. Applied Data Analysis, Faculty of Computer Science (2023–2027)
- **CUHK Shenzhen / SRIBD** — Incoming Research Intern (Summer 2026)
  - Lab: School of Life and Health Sciences AI Lab (SLAI)
  - Focus: Automatic speech analysis for dementia and cognitive impairment

---

### Currently Learning / Exploring

- Paralinguistic features in pathological speech (MFCCs, prosody, formants)
- Self-supervised speech representations: wav2vec 2.0, HuBERT
- Clinical NLP for medical records and discharge summaries

---

### Contact

- **Email:** avsuvorova_2@edu.hse.ru
- **Institution:** [cs.hse.ru](https://cs.hse.ru/en/)

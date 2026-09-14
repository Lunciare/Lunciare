## Hi, I'm Aleksandra Suvorova 👋

I'm a 4th-year undergraduate at **HSE University** (Faculty of Computer Science, Moscow), specialising in Data Analysis in Applied Research. My research sits at the intersection of **deep learning and medicine** — I care about building models that are not only accurate but clinically meaningful.

This summer I have joined the **Shenzhen Loop Area Institute (SLAI)** at CUHK Shenzhen as a research intern, working on **dysarthric speech**.

---

### Research Interests

- Speech & audio processing for clinical applications (dysarthria, dementia, atypical speech)
- Medical AI — from signal to clinical decision support
- Multimodal learning (audio + language + structured data)

---

### Tech Stack

**Languages & Core**
`Python` · `C++` · `SQL`

**ML / DL**
`PyTorch` · `scikit-learn` · `HuggingFace Transformers` · `segmentation_models_pytorch` · `Captum` · `Albumentations` · `Optuna` · `librosa` · `torchaudio`

---

### Featured Projects

| Project | Description | Stack |
|---|---|---|
| [multi-agent-medical-rag](https://github.com/Lunciare/multi-agent-medical-rag) | Multi-agent RAG system for clinical decision support. Routes queries to specialist agents over a FAISS-indexed medical knowledge base; intercepts emergency and prescription-sensitive queries. | Python · FAISS · LLMs |
| [genomic-variant-gnn](https://github.com/Lunciare/genomic-variant-gnn) | Pathogenic-vs-benign classification of ClinVar DNA variants from 2,048-bp of sequence context, using a GNN that treats fixed-length sequence windows as graph nodes (with a CNN baseline for an honest comparison). A deliberately modest, research-grade result — test ROC-AUC 0.673, essentially tied with the untuned baseline (0.665); interpretability surfaces CpG-rich motifs, consistent with methylation-hotspot biology. | PyTorch · PyTorch Geometric · Optuna · Captum |
| [skin-lesion-segmentation-unet](https://github.com/Lunciare/skin-lesion-segmentation-unet) | Per-pixel segmentation of skin lesions on ISIC 2018 dermoscopy. A from-scratch U-Net compared, on an identical pipeline, against an ImageNet-pretrained ResNet-34 encoder, with Integrated-Gradients maps to check the model keys on lesion tissue rather than on rulers and bubbles. Pretrained encoder reaches Dice 0.903 vs 0.877 from scratch, and gets there ~8× faster. | PyTorch · segmentation_models_pytorch · Captum |
| [dnabert-promoter-rl](https://github.com/Lunciare/dnabert-promoter-rl) | Fine-tunes DNABERT-2 into a promoter classifier (ROC-AUC 0.9946; LoRA matches it while training ~0.13 % of the parameters), then uses that classifier as a reward model for RL sequence design. The agent reached ~0.995 reward by exploiting the classifier rather than generating real promoters — reward hacking, diagnosed via GC-content analysis. | DNABERT-2 · LoRA · REINFORCE / PPO |
| [Prompt Sensitivity in Pathology Vision-Language Models](https://github.com/Lunciare/plip-prompt-sensitivity) | PLIP paper analysis, prompt sensitivity study, prompt ensemble ablation, linear probing, comparison of different models | PyTorch · ViT · Transformer|
| [dimenetpp-breakdown](https://github.com/Lunciare/dimenetpp-breakdown) | Breakdown and partial reproduction of DimeNet++ (directional message-passing GNN for molecular energies), structured as four experiments that each stress-test one claim. Reproduces QM9 accuracy from the authors' pretrained checkpoints (U₀ MAE 6.15 meV vs paper 6.32) and the 5.94× speedup over DimeNet at 30 atoms, then shows the model breaks off-equilibrium — 1.32 eV MAE on COLL, ~214× its in-distribution error — isolating training data, not architecture, as the cause. Closes on uncertainty: an ensemble's force spread tracks its error (Spearman 0.85) while energy uncertainty and MVE do not. Every result reported with its caveats. | PyTorch · PyTorch Geometric · TensorFlow · Colab T4 |

---

### Education & Affiliations

- **HSE University** — B.Sc. Applied Data Analysis, Faculty of Computer Science (2023–2027)
- **CUHK Shenzhen / SRIBD** — Research Intern (Summer 2026)
  - Lab: Centre for Language and Machines

---

### Contact

- **Email:** avsuvorova_2@edu.hse.ru
- **Institution:** [cs.hse.ru](https://cs.hse.ru/en/)

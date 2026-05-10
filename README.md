# 📚 Short Story Assignment — Multimodal Generative Models Survey

> **Course Assignment | Due: May 9, 2026**  
> **Author:** Dhadu  
> **Topic:** A Survey of Generative Categories and Techniques in Multimodal Generative Models

---

## 📄 Paper Details

| Field | Details |
|-------|---------|
| **Title** | A Survey of Generative Categories and Techniques in Multimodal Generative Models |
| **ArXiv Link** | [https://arxiv.org/abs/2506.10016](https://arxiv.org/abs/2506.10016) |
| **PDF** | [https://arxiv.org/pdf/2506.10016v1](https://arxiv.org/pdf/2506.10016v1) |
| **Published** | June 2026 |
| **Type** | Survey Paper |

### 🔍 Paper Summary
This survey covers the rapid evolution of **Multimodal Generative Models (MGMs)** across six primary output modalities: **images, music, video, human motion, 3D objects, and text**. It examines how foundational techniques — Self-Supervised Learning (SSL), Mixture of Experts (MoE), Reinforcement Learning from Human Feedback (RLHF), and Chain-of-Thought (CoT) prompting — enable cross-modal capabilities. The paper also proposes a unified evaluation framework centred on **faithfulness, compositionality, and robustness**, and analyses trustworthiness, safety, and ethical risks including deepfakes, bias, and privacy.

---

## 🔗 Deliverables

### 📝 Medium Article
**Link:** [A Survey of Generative Categories and Techniques in Multimodal Generative Models](https://medium.com/p/7cd748c26c99?postPublishedType=initial)

A full review of the paper written in my own words, covering:
- Architecture of multimodal generative models
- Six generative modalities explained
- Core training techniques (SSL, MoE, RLHF, CoT)
- Unified evaluation framework
- Safety, ethics, and deepfake risks
- Key benchmarks and results

---

**Notebook:** [`autoresearch/multimodal_survey_reproduction.ipynb`](./autoresearch/)

Reproduces key evaluation concepts from the paper using the **autoresearch template**:
- CLIP-based cross-modal similarity scoring (faithfulness metric)
- Text-to-image alignment benchmarking
- Multimodal evaluation pipeline
- Results visualization across modalities

**How to run:**
1. Open `autoresearch/multimodal_survey_reproduction.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run all cells (Runtime → Run All)
3. No local GPU required — uses free Colab resources

---

## 📁 Repository Structure

```
short-story-assignment/
│
├── README.md                          ← You are here
│
├── autoresearch/
│   └── multimodal_survey_reproduction.ipynb  ← Colab notebook
│
├── slides/
│   └── short_story_slides.pdf         ← Presentation slides
│
├── video/
│   └── short_story_presentation.mp4   ← 15-25 min recorded video
│
└── paper/
    └── 2506.10016v1.pdf               ← Original survey paper
```

---

## 🧠 Key Concepts Covered

### Six Generative Modalities
| Modality | Example Models |
|----------|---------------|
| 🖼️ Image | DALL-E, Stable Diffusion, Imagen |
| 🎵 Music | MusicGen, AudioLM |
| 🎬 Video | Sora, VideoLDM, Gen-2 |
| 🏃 Human Motion | MDM, MotionDiffuse |
| 🧊 3D Objects | Point-E, Shap-E, DreamFusion |
| 📝 Text | GPT-4, Gemini, LLaMA |

### Core Training Techniques
- **SSL (Self-Supervised Learning)** — Pretraining without labels using contrastive objectives (e.g., CLIP)
- **MoE (Mixture of Experts)** — Sparse gating for efficient cross-modal scaling
- **RLHF** — Aligning generation to human preferences
- **CoT (Chain-of-Thought)** — Structured reasoning for complex multimodal prompts


## 📖 References

1. **Primary Paper:** *A Survey of Generative Categories and Techniques in Multimodal Generative Models* — ArXiv 2506.10016 (2026). [https://arxiv.org/abs/2506.10016](https://arxiv.org/abs/2506.10016)
2. Radford et al. — *CLIP: Learning Transferable Visual Models From Natural Language Supervision* (2021)
3. Ho et al. — *Denoising Diffusion Probabilistic Models* (NeurIPS 2020)
4. Ouyang et al. — *Training language models to follow instructions with human feedback* (NeurIPS 2022)
5. Copet et al. — *Simple and Controllable Music Generation* (NeurIPS 2023)

---

## 👤 Author

**Name:** Dhaduk Deep  
**Assignment:** Short Story (Individual)  
**Course:** CMPE-258 Sec-49 Deep Learning  
**Medium:** [Article Link](https://medium.com/p/7cd748c26c99?postPublishedType=initial)

---

*This repository contains all deliverables for the Short Story Assignment including a Medium article, slide deck, presentation video, and code reproduction of key concepts from the survey paper.*

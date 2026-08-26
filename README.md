# Hi, I'm Federico Carollo 👋
### **Applied Scientist & AI Researcher** | *Distributed Systems, Generative AI & Uncertainty Quantification*

📍 **Torino, Italy** · 🌍 **Open to Relocation (Paris / EU)**  
🎓 **M.Sc. in AI & Data Analytics (Top 1% / 4.0 GPA, 110L)** @ *Politecnico di Torino*  
📫 `posta.fedcar@gmail.com` · [LinkedIn](https://linkedin.com/in/federico-carollo) · [GitHub](https://github.com/FedeCarollo)

---

### 🔬 Research & Engineering Focus

I bridge the gap between **rigorous mathematical theory** (Distribution-Free Uncertainty, Conformal Risk Control) and **high-performance systems** (Distributed Multi-GPU Training, MoE Architectures, Custom Low-Level Inference Engines).

┌─────────────────────────────────────────┐
│              CORE PILLARS               │
├────────────────────┬────────────────────┤
│ 🚀 Distributed ML  │ 🎯 Uncertainty &   │
│   & Systems        │   Calibration      │
│ (DiTs, MoE, HPC)   │ (Conformal Pred.)  │
├────────────────────┼────────────────────┤
│ ⚡ Low-Level & Edge│ 📈 Time Series &   │
│ (Rust, Candle, C++)│   Forecasting      │
└────────────────────┴────────────────────┘

---

### 🚀 Key Projects & Selected Research

#### 🧬 **Distributed Generative Models & HPC**
* **Histomorph — WSI Virtual Staining with DiTs** `PyTorch` `HuggingFace Accelerate` `HPC Cluster`
  * Scaled distributed training of Diffusion Transformers (DiTs) conditioned on histopathology ViT foundation models across a multi-GPU HPC cluster.
  * Optimized custom large-scale dataloaders and cross-node gradient synchronization across 100k+ pathology tiles.
  * *(Manuscript in preparation · Code & Private Draft available upon request)*

#### ⚡ **Efficient LLM Inference & Systems**
* **Speculative Decoding on MoE** `Mistral-7B` `Mixtral-8x7B MoE` `QLoRA`
  * Implemented speculative sampling coupling Mistral-7B (Draft) with Mixtral-8x7B (Target) using a custom cross-entropy + KL divergence objective.
  * Achieved **1.45x wall-clock speedup** on GSM8K and HumanEval while profiling memory bandwidth bottlenecks and MoE routing overhead.
* **Edge LLM Inference Engine from Scratch** `Rust` `Candle` `SIMD`
  * Built a standalone LLaMA/Transformer inference engine in pure Rust from scratch (RoPE attention, RMSNorm, SwiGLU) running on constrained edge devices (<4GB VRAM).

#### 🎯 **Statistical Rigor & Conformal Prediction**
* **Causal Horizon-Specific Conformal Calibration** `PyTorch` `Darts` `Time-Series`
  * Formulated an asynchronous queue framework for multi-step conformal prediction with horizon-specific coverage guarantees under concept drift (addressing an open NeurIPS challenge).
  * Extended Reservoir Conformal Prediction (ResCP) with dynamic ESS-based temperature blending to eliminate interval collapse (+15.4% IWS improvement).
  * *(Manuscript in preparation · Available upon request)*
* **Huawei European AI Challenge** `Time Series Risk Detection` `WIP`
  * Designing a streaming risk/anomaly detection pipeline on non-stationary multi-variate series under severe temporal shifts.

---

### 🏆 Selected Achievements
* 🥇 **Global Winner — GitHub "For the Love of Code" Hackathon (2025):** Built *Jukebox CLI*, a high-performance audio engine written entirely in Rust.
* 🎓 **Academic Excellence:** Double 110/110 Cum Laude (B.Sc. in Computer Engineering & M.Sc. in AI), 4.0/4.0 GPA (29.9/30 avg).

---

### 🛠️ Tech Stack & Tooling

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/CUDA%20%2F%20HPC-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/Distributed%20Training-FSDP%20%2F%20Accelerate-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Linux%20%2F%20Slurm-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

---
<sub>*Note: Selected research manuscripts, benchmarks, and private implementations are available upon request for interview and evaluation purposes.*</sub>

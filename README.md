# Hi, I'm Federico Carollo 👋
### **Applied Scientist & AI Researcher** | *Distributed Systems, Generative AI & Uncertainty Quantification*

📍 **Torino, Italy** · 🌍 **Open to Relocation (Paris / EU)**  
🎓 **M.Sc. in AI & Data Analytics (Top 1% / 4.0 GPA, 110L)** @ *Politecnico di Torino*  
📫 `posta.fedcar@gmail.com` · [LinkedIn](https://linkedin.com/in/federico-carollo) · [GitHub](https://github.com/FedeCarollo)

---

### 🔬 Core Pillars

| 🚀 Distributed ML & Systems | 🎯 Uncertainty & Calibration |
| :--- | :--- |
| **Diffusion Transformers (DiTs)**, **MoE**, Multi-GPU HPC scaling, FSDP & Accelerate | **Conformal Prediction**, Conformal Risk Control, Distribution-free guarantees |
| **⚡ Low-Level & Edge Engineering** | **📈 Time Series & Forecasting** |
| Custom Inference Engines in **Rust**, **Candle**, Memory bandwidth & RoPE optimization | Multi-step causal calibration, SOTA architectures (iTransformer, TSMixer) |

---

### 🚀 Key Projects & Selected Research

#### 🎯 **Statistical Rigor & Conformal Calibration**
* [**doraemon_calibration**](https://github.com/FedeCarollo/doraemon_calibration) `PyTorch` `Conformal Prediction` `Paper Included`
  * Complete framework for distribution-free uncertainty estimation and predictive calibration. Includes the full academic paper, rigorous benchmarking suite, and reproducible evaluation pipelines.
* **Causal Horizon-Specific Conformal Calibration** `PyTorch` `Darts` `Time-Series`
  * Formulated an asynchronous queue framework for multi-step conformal prediction with horizon-specific coverage guarantees under concept drift (addressing an open NeurIPS challenge).
  * Extended Reservoir Conformal Prediction (ResCP) with dynamic ESS-based temperature blending (+15.4% IWS improvement).
  * *(Manuscript in preparation · Available upon request)*
* **Huawei European AI Challenge** `Time Series Risk Detection` `WIP`
  * Developing a streaming risk and anomaly detection framework for high-dimensional non-stationary series under severe temporal shifts.

#### 🧬 **Distributed Generative Models & HPC**
* **Histomorph — WSI Virtual Staining with DiTs** `PyTorch` `Accelerate` `HPC Multi-GPU`
  * Scaled distributed training of Diffusion Transformers conditioned on histopathology ViT foundation models across an HPC cluster.
  * Optimized custom dataloaders and cross-node synchronization across 100k+ gigapixel pathology tiles.
  * *(Manuscript in preparation · Code & Private Draft available upon request)*

#### ⚡ **Efficient LLM Inference & Systems**
* **Speculative Decoding on MoE** `Mistral-7B` `Mixtral-8x7B MoE` `QLoRA`
  * Paired Mistral-7B (Draft) with Mixtral-8x7B (Target) using a custom CE + KL divergence loss.
  * Achieved **1.45x wall-clock speedup** on GSM8K and HumanEval while profiling memory bandwidth bottlenecks and MoE routing overhead.
* **Edge LLM Inference Engine from Scratch** `Rust` `Candle` `SIMD`
  * Built an end-to-end LLaMA inference engine in pure Rust from scratch (RoPE attention, RMSNorm, SwiGLU) running on constrained edge devices (<4GB VRAM).

---

### 🏆 Selected Achievements
* 🥇 **Global Winner — GitHub "For the Love of Code" Hackathon (2025):** Built *Jukebox CLI*, a high-performance terminal audio engine in Rust.
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
<sub>*Note: Manuscripts under review and private experimental implementations are available upon request for evaluation purposes.*</sub>

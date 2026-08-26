# Hi, I'm Federico Carollo 👋
### **Applied Scientist & AI Researcher** | *Distributed Systems, Generative AI & Uncertainty Quantification*

📍 **Torino, Italy** · 🌍 **Open to Relocation (Paris / EU)**  
🎓 **M.Sc. in AI & Data Analytics (Top 1% / 4.0 GPA, 110L)** @ *Politecnico di Torino*  
📫 `posta.fedcar@gmail.com` · [LinkedIn](https://linkedin.com/in/federico-carollo) · [GitHub](https://github.com/FedeCarollo)

---

### 🚀 Key Projects & Selected Research

#### 🧬 **Distributed Generative Models & HPC**
* **Histomorph — WSI Virtual Staining with DiTs** `PyTorch` `Accelerate` `HPC Multi-GPU` `Work in Progress`
  * Scaled distributed training of Diffusion Transformers (DiTs) conditioned on histopathology ViT foundation models across a multi-GPU HPC cluster.
  * Commissioned by academic faculty to extend previous coursework into an end-to-end WSI-to-WSI translation framework targeting formal publication.
  * Scaled data pipelines to 100k+ pathology tiles, optimizing custom high-throughput dataloaders and cross-node gradient synchronization.
  * *(Manuscript in preparation for venue submission · Private draft & architecture available upon request)*

#### ⚡ **Efficient LLM Inference & Systems**
* [**Speculative Decoding on MoE**](https://github.com/FedeCarollo/mistral_experiments/tree/main/speculative_decoding) `Mistral-7B` `Mixtral-8x7B MoE` `QLoRA`
  * Implemented speculative sampling pairing Mistral-7B (Draft) with Mixtral-8x7B (Target) using a custom CE + KL divergence objective.
  * Achieved **1.45x wall-clock speedup** on GSM8K and HumanEval while profiling memory bandwidth bottlenecks and MoE routing overhead.
* **Edge LLM Inference Engine from Scratch** `Rust` `Candle` `Inference`
  * Built an end-to-end LLaMA inference engine in pure Rust from scratch (RoPE attention, RMSNorm, SwiGLU) running on constrained edge devices.
  * 
#### 🎯 **Statistical Rigor & Conformal Calibration**
* **Resolving Observation Lag in Multi-Step Conformal Prediction** `PyTorch` `NexCP` `Manuscript in Review`
  * Formalized a causal calibration framework for online multi-step ($H$-step ahead) forecasting using an asynchronous Matrix-Based Pending Queue with In-Place Buffer Propagation, eliminating lookahead bias.
  * Derived explicit horizon-specific marginal coverage bounds grounded in the Non-Exchangeable Conformal Prediction (NexCP) theorem under temporal non-stationarity and observation lag.
  * Extended Reservoir Conformal Prediction (ResCP) with ESS-based adaptive blending and safety floors, achieving a +15.4% average IWS improvement across hundreds of dataset-model settings
  * *(Manuscript in preparation · Full thesis & draft available upon request)*

#### 📈 **Resilience AI, Forecasting & Statistical Modeling**
* **GridShift — Huawei Tech Arena** `PyTorch` `Darts` `Optuna` `uv` `Private Repo`
  * Engineering an end-to-end multi-horizon risk forecasting pipeline ($P \in [0, 1]$) for AI Data Centers (AIDC) under extreme weather events and 3 incoming-feeder topologies.
  * Formulated custom Compound Poisson-Gamma **Tweedie NLL objectives** ($p \in (1,2)$) and fault-window chunking to solve severe zero-inflation on regional outage spikes.
* [**doraemon_calibration**](https://github.com/FedeCarollo/doraemon_calibration) `PyTorch` `Conformal Prediction` `Paper Included`
  * Complete framework for distribution-free uncertainty estimation and predictive calibration. Includes the full academic paper and related code.

---

### 🏆 Selected Achievements
* 🥇 **Global Winner — GitHub "For the Love of Code" Hackathon (2025):** Built *Jukebox CLI*, a high-performance terminal audio engine written in Rust.
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
<sub>*Note: Manuscripts under review, competition repositories, and private implementations are available upon request for interview and evaluation purposes.*</sub>

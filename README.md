# Hi, I'm Federico Carollo 👋
### **Applied Scientist & AI Researcher** | *Distributed Systems, Generative AI & Uncertainty Quantification*

📍 **Torino, Italy** · 🌍 **Open to Relocation (EU)**  
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
* [**Edge LLM Inference Engine from Scratch**](https://github.com/FedeCarollo/RustLLM_serve) `Rust` `Candle` `Inference`
  * Built an end-to-end LLaMA inference engine in pure Rust from scratch (RoPE attention, RMSNorm, SwiGLU) running on constrained edge devices.ù


#### 🎯 **Statistical Rigor & Conformal Calibration (Thesis)**

* **Resolving Observation Lag in Multi-Step Conformal Prediction** `PyTorch` `NexCP` `Theory & Systems` `Manuscript in Review`
  * Formulated an online, asynchronous calibration framework using a **Matrix-Based Pending Queue with In-Place Buffer Propagation** to resolve the multi-step ($H$-step ahead) observation lag without lookahead bias.
  * Derived explicit finite-sample per-step marginal coverage guarantees grounded in the **Non-Exchangeable Conformal Prediction (NexCP)** theorem under temporal non-stationarity.
  * Demonstrated consistent marginal coverage stability across classical CQR, time-decay NexCP, and state-dependent ResCQR over standard time-series benchmarks (ETTh1/2, Traffic, Weather).
  * *(Manuscript under review · Full paper draft available upon request)*

* **Adaptive Conformal Calibration for Non-Stationary Multi-Step Forecasting** `M.Sc. Thesis` `Darts` `PyTorch`
  * Comprehensive extension of Reservoir Conformal Prediction (**ResCP**) integrating topological ESN memories, dynamic ESS-based adaptive blending, and structural safety floors against interval collapse.
  * Developed a streaming **post-hoc risk controller** (inspired by CRC and ACI feedback loops) that dynamically adjusts quantiles to satisfy asymmetric business cost targets during extreme concept drift (COVID-19 shock).
  * Scaled benchmark across 26 real-world energy datasets and deep backbones (iTransformer, TSMixer, TiDE), achieving a **+15.4% mean IWS improvement** over uncalibrated baselines and outperforming standard CQR in 51/78 configurations.
  * *(Full thesis text & experimental codebase available upon request)*

#### 📈 **Resilience AI, Forecasting & Statistical Modeling**
* **GridShift — Huawei Tech Arena** `PyTorch` `Tree Models` `Optuna` `Competition`
  * Engineering an end-to-end multi-horizon risk forecasting pipeline ($P \in [0, 1]$) for AI Data Centers (AIDC) under extreme weather events and 3 incoming-feeder topologies.
  * Formulated custom Compound Poisson-Gamma **Tweedie NLL objectives** ($p \in (1,2)$) and fault-window chunking to solve severe zero-inflation on regional outage spikes.
* [**doraemon_calibration**](https://github.com/FedeCarollo/doraemon_calibration) `PyTorch` `Conformal Prediction` `Paper Included`
  * Complete framework for distribution-free uncertainty estimation and predictive calibration in Sim-To-Real RL settings. Includes the full academic paper and related code.

---

### 🏆 Selected Achievements
* 🥇 **Global Winner — GitHub "For the Love of Code" Hackathon (2025):** Built [**Jukebox CLI**](https://github.com/FedeCarollo/jukebox-cli), a high-performance terminal audio engine written in Rust.
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

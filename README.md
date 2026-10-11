# Hi, I’m Federico Carollo 👋

### AI Engineer | Distributed ML Systems, Generative AI & Uncertainty Quantification

I build reliable, scalable machine-learning systems—from distributed generative models and LLM inference to uncertainty-aware forecasting under distribution shift.

📍 **Torino, Italy** · 🌍 Open to relocation across the EU  
🎓 **M.Sc. AI & Data Analytics**, Politecnico di Torino — **110/110 cum laude** · 4.0/4.0 GPA  
📫 [Email](mailto:posta.fedcar@gmail.com) · [LinkedIn](https://linkedin.com/in/federico-carollo) · [GitHub](https://github.com/FedeCarollo)


---

## Selected Research & Engineering

### ⚡ Efficient LLM Inference & Systems

[**Speculative Decoding on MoE**](https://github.com/FedeCarollo/speculative_decoding) · `Mistral-7B` `Mixtral-8×7B MoE` `QLoRA`  
- Implemented speculative decoding with Mistral-7B as draft model and Mixtral-8×7B as target, using a custom cross-entropy + KL-divergence objective.
- Achieved **1.45× end-to-end wall-clock speedup** at \(k = 2\) on GSM8K and HumanEval; profiled memory-bandwidth bottlenecks and MoE routing overhead.
- See the repository for benchmark configuration, hardware context, and limitations.

[**Custom LLM Inference Engine**](https://github.com/FedeCarollo/RustLLM_serve) · `Rust` `Candle` `CUDA`  
- Implemented the LLaMA forward pass in Rust—including RoPE, RMSNorm, attention, and concurrent REST serving—without high-level LLM-inference wrappers.
- Designed a thread-safe, preallocated KV cache with in-place updates to remove decode-time allocation overhead.
- Achieved up to **14× decoding improvement** under documented CUDA benchmark settings.

### 🎯 Reliable ML Under Distribution Shift

**Resolving Observation Lag in Multi-Step Conformal Prediction** · `PyTorch` `NexCP` `Theory & Systems`  
- Designed an online asynchronous calibration framework that handles delayed \(H\)-step-ahead observations without look-ahead bias.
- Derived finite-sample, horizon-specific marginal-coverage guarantees grounded in Non-Exchangeable Conformal Prediction under temporal non-stationarity.
- Evaluated coverage stability against CQR, time-decay NexCP, and state-dependent ResCQR on ETTh1/2, Traffic, and Weather benchmarks.
- **Completed research manuscript; preparing public preprint and venue submission.** Technical materials available upon request where permitted.

**Adaptive Conformal Calibration for Non-Stationary Multi-Step Forecasting** · `M.Sc. Thesis` `Darts` `PyTorch`  
- Extended Reservoir Conformal Prediction with topological ESN memory, effective-sample-size-based adaptive blending, and safeguards against interval collapse.
- Built a streaming post-hoc risk controller, inspired by CRC and ACI feedback loops, for asymmetric business costs during extreme concept drift.
- Evaluated 26 real-world energy datasets with TiDE, TSMixer, and iTransformer backbones; achieved **+15.4% mean IWS** over uncalibrated baselines and outperformed standard CQR in **51/78 configurations**.
- **Completed thesis research; manuscript preparation in progress.**

### 🧬 Distributed Generative Models & HPC

**Histomorph — Whole-Slide-Image Virtual Staining with DiTs** · `PyTorch` `Accelerate` `ViT` `HPC`  
- Developed an end-to-end WSI-to-WSI virtual-staining research pipeline using Diffusion Transformers conditioned on histopathology ViT foundation models.
- Scaled training across a multi-GPU HPC cluster and built high-throughput data pipelines for **100k+ pathology tiles**, including custom loaders and distributed synchronization.
- Built an out-of-core pathology preprocessing workflow and released a [PyPI package](https://github.com/FedeCarollo/wsi-tile-processor) for WSI tile processing.
- **Core system complete; manuscript and public release preparation in progress.** Architecture and permitted materials available upon request.

### 🔓 Open Source

**Nixtla / NeuralForecast Contributor** · `PyTorch` `Time-Series` `Foundation Models`  
- Extended the upstream iTransformer implementation with native support for future exogenous covariates in [PR #1607](https://github.com/Nixtla/neuralforecast/pull/1607).
- Delivered production-grade PyTorch code and unit tests through the project’s upstream review process.

### 🧠 Ongoing LLM Research

**GRPO Alignment Pipeline for LLM Reasoning** · `PyTorch` `vLLM` `DeepSpeed` `Accelerate` `SLURM`  
- Developing a config-driven distributed GRPO pipeline for Qwen2.5 models on mathematical-reasoning tasks.
- Integrating high-throughput co-located rollout generation through vLLM with multi-GPU training via Accelerate, DeepSpeed ZeRO-2, and DDP.
- Building automated reasoning evaluation with unbiased pass@k estimators on MATH-500, OlympiadBench, and Minerva.
- Research implementation is ongoing; technical materials available upon request.

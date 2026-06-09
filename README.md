# Hi, I'm Ronika 👋

CS student at Georgia Tech (AI + Cybersecurity/Privacy threads, BME minor) interested in the intersection of **machine learning systems and security** — training models from scratch, squeezing them onto constrained hardware, and breaking things safely in sandboxes.

Currently doing applied ML research in the [Graham Lab @ GT](https://example.com), forecasting *Legionella pneumophila* concentrations in building water networks with XGBoost. Previously co-authored a [peer-reviewed bibliometric study](https://pubmed.ncbi.nlm.nih.gov/40991854/) in the *Journal of Strength & Conditioning Research*.

## 🔭 What I've built

**[Wallpaper Diffusion](https://github.com/rmedagam06/wallpaper-diffusion)** — A text-to-image latent diffusion model implemented from scratch in PyTorch: ~25M-parameter U-Net with cross-attention to frozen CLIP embeddings, DDIM sampling with classifier-free guidance (1,000 → 50 inference steps), and rank-16 LoRA fine-tuning. Trained 200K steps on a 4GB GPU using fp16 + gradient checkpointing.

**[LLM Benchmark](https://github.com/rmedagam06/llm-benchmark)** — An automated optimization pipeline for open-source LLMs: MMLU benchmarking, QLoRA fine-tuning sweeps, GGUF quantization comparison (Q4/Q5/Q8), and a composite scoring function that trades accuracy against TTFT and VRAM to pick the best deployment config. FastAPI backend with SSE streaming.

**[Degree Planner](https://github.com/rmedagam06/course-planner)** — A prerequisite-aware course scheduler built with Next.js + TypeScript. Kahn's topological sort + wave-based greedy packing to generate minimum-semester graduation plans, with AND/OR prerequisite parsing, elective-pool optimization, and critical-path analysis.

**Malware Analysis Sandbox** — An isolated multi-VM environment (REMnux + FlareVM) for safely executing live PE binaries, with an automated pipeline capturing memory dumps, registry changes, and network beacons, and a stix2-based parser generating STIX/TAXII threat-intel reports.

## 🌱 Currently

- Building a legal document simplifier and evaluating it against LegalBench and LexGLUE
- Learning: JAX/Flax, RAGAS for RAG evaluation

## 🛠 Tools I actually use

`Python` `PyTorch` `Hugging Face Transformers` `PEFT/TRL` `llama.cpp` `scikit-learn` `XGBoost` `TypeScript` `Next.js` `React` `FastAPI` `SQLite` `Docker` `AWS`

## 📫 Reach me

[LinkedIn](https://linkedin.com/in/YOUR-HANDLE) · ronika05m@gmail.com

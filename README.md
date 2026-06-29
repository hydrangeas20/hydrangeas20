# Hi, I'm Hamda 👋

I'm an empirical AI safety researcher and ML systems engineer. I build benchmarks and evaluation pipelines that test how robust, interpretable, and reliable language models actually are — fine-tuning attack resistance, mechanistic interpretability, scaling laws, and adversarial robustness — and I publish what I find, including the results that don't confirm my hypotheses.

I'm the founder of [Plum AI Labs](https://github.com/Plum-AI-Labs), where this research lives alongside two first-author publications. I also write about LLM evaluation and AI safety at [Applied Alignment](https://appliedalignment.substack.com).

## What I work on

- **Fine-tuning attack resistance & safety evaluation** — does alignment hold up under adversarial fine-tuning, and do our evaluations actually measure what we think they measure?
- **Mechanistic interpretability** — logit lens, activation patching, sparse autoencoders on transformers built from scratch
- **Scaling laws & GPU systems** — recovering empirical scaling relationships, benchmarking `torch.compile` and Triton kernels against eager PyTorch
- **Production ML systems** — pipelines, monitoring, and infrastructure that actually ship

## Featured work

| Project | What it does |
|---|---|
| [SafetyLens](https://github.com/hydrangeas20/safetylens) | Measures divergence between eval-framed and deployment-framed model behaviour across model scale |
| [AudioGuard](https://github.com/hydrangeas20/audioguard) | Adversarial robustness evaluation for audio classifiers — FGSM, PGD, adversarial training |
| [JAX Interpretability](https://github.com/hydrangeas20/jax-interpretability) | Mechanistic interpretability on a transformer built from scratch — logit lens, activation patching, SAEs |
| [ScaleTrace](https://github.com/hydrangeas20/scaletrace) | Empirically recovers Chinchilla-style scaling laws from a small training grid |
| [KernelBench](https://github.com/hydrangeas20/kernelbench) | GPU kernel benchmarking — PyTorch eager vs. `torch.compile` vs. Triton |
| [e2e-ml-pipeline](https://github.com/hydrangeas20/e2e-ml-pipeline) | Production-grade ML pipeline with DVC, MLflow, and Dockerized FastAPI deployment |

## Background

Infrastructure & AI Systems Engineer by day, independent researcher the rest of the time. My engineering background (Python, PyTorch, JAX, Docker, Kubernetes, AWS, distributed data systems) is what lets me build and run the experiments behind the research, not just theorize about them.

## Let's talk

If you're working on AI safety evaluation, interpretability, or adversarial robustness — or just want to talk shop about empirical ML research — I'd love to connect.

- 🔬 [Plum AI Labs](https://github.com/Plum-AI-Labs)
- ✍️ [Applied Alignment](https://appliedalignment.substack.com)
- 💼 [LinkedIn](https://linkedin.com/in/hamda-aden)
<!--
**hydrangeas20/hydrangeas20** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


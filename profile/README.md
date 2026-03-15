# AtomGradient ⚡

> **Bringing AI to the Edge** — We build open research and products for on-device AI inference on Apple Silicon and consumer hardware.

We believe powerful AI should be **private**, **fast**, and **free from cloud dependency**. All our research is open-source.

🌐 [atomgradient.com](https://atomgradient.com) · 🚀 [EchoStream AI](https://www.echostream-ai.com/)

---

## Research

| Project | Description | Highlights |
|---------|-------------|------------|
| [**speculative-moe-research**](https://github.com/AtomGradient/speculative-moe-research) | Does speculative decoding help Mixture-of-Experts? Empirical study on Qwen3.5-35B-A3B | 1.30× MoE speedup · <4% acceptance · batch verification amortization |
| [**apple-silicon-llm-inference**](https://github.com/AtomGradient/apple-silicon-llm-inference) | Efficient on-device LLM inference: from quantization to speculative decoding | Q6_K Pareto-optimal · +25.7% SD throughput · 7 quant levels benchmarked |
| [**Prism**](https://github.com/AtomGradient/Prism) | Cross-domain personal data integration on consumer hardware | 1.48x IIR · 125.5x federation compression · 49.9 TPS (35B on M2 Ultra) |
| [**hybird-batch-prefill-on-ane**](https://github.com/AtomGradient/hybird-batch-prefill-on-ane) | ANE batch prefill for on-device parallel LLM inference | 11.3x prefill speedup · 79% power reduction · <30ms state transfer |
| [**hybrid-ane-mlx-bench**](https://github.com/AtomGradient/hybrid-ane-mlx-bench) | Disaggregated LLM inference on Apple Silicon | ANE matches GPU at ~410 tokens · 282x power reduction |
| [**swift-qwen3-tts**](https://github.com/AtomGradient/swift-qwen3-tts) | On-device text-to-speech (Qwen3 TTS 0.6B, native Swift) | 67% compression · RTF 0.68x · 12 languages |
| [**swift-gemma-cli**](https://github.com/AtomGradient/swift-gemma-cli) | On-device vision language model (Gemma 3 4B) | 25% compression · 110 tok/s · 3.4x image speedup |
| [**OptMLX**](https://github.com/AtomGradient/OptMLX) | MLX memory optimization research | 20x mmap speedup · zero-copy model loading |

---

## Focus Areas

- **Edge Inference** — Running large models on consumer Apple Silicon (ANE + GPU hybrid pipelines)
- **Model Compression** — Quantization, pruning, and distillation for on-device deployment
- **Privacy-First AI** — All computation local, zero data leakage
- **Open Research** — Reproducible benchmarks and open-source implementations

---

<sub>© 2026 AtomGradient · All research open-source under MIT</sub>

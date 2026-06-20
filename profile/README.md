# AtomGradient ⚡

> **Private AI that lives on your device** — We build the full stack for on-device AI: from the inference engine to the app you ship.

*They said weights are frozen. We made them grow with you.*

**AI Models That Grow for You.** A model born for you. No matter how time passes or the world changes, it is your most faithful companion — facing the world as you do, learning and growing together, never leaving your side.

🌐 [atomgradient.com](https://atomgradient.com) · 📖 [Developer Docs](https://www.atomgradient.com/en/developers)

---

## Products

The Edge stack — everything you need to build, optimize, and ship on-device AI apps on Apple Silicon.

| Layer | Repo | What it does |
|-------|------|-------------|
| **Engine** | [**edge-engine**](https://github.com/AtomGradient/edge-engine) | Native Metal inference runtime — LLM, VLM, ASR, TTS on Apple Silicon |
| **SDK** | [**edge-kit**](https://github.com/AtomGradient/edge-kit) | Swift SDK — load models, stream tokens, manage memory, mesh devices |
| **Learning** | [**edge-halo**](https://github.com/AtomGradient/edge-halo-binary) | On-device self-learning — models grow with you, data never leaves the device |
| **App Template** | [**edge-scaffold**](https://github.com/AtomGradient/edge-scaffold) | iOS app scaffold — import EdgeKit, customize, ship to App Store |
| **Workbench** | [**edge-studio**](https://github.com/AtomGradient/edge-studio) | Python CLI + web UI — analyze, optimize, benchmark, export models |

```
edge-studio (optimize & export)
    ↓
edge-scaffold (iOS app template)
    ├── edge-kit (Swift SDK)
    │     └── edge-engine (Metal inference)
    └── edge-halo (on-device learning, binary)
```

```bash
# Get started
pip install edge-studio           # Python workbench
edge demo chat                    # Try on-device chat
```

```swift
// Swift — 5 lines to on-device LLM
import EdgeInference
let engine = LLMEngine()
try await engine.loadLocal(directory: modelURL)
for try await chunk in engine.generate(messages: [.user("Hello")]) {
    print(chunk.text, terminator: "")
}
```

---

## Research & Tools

[speculative-moe-research](https://github.com/AtomGradient/speculative-moe-research) · [apple-silicon-llm-inference](https://github.com/AtomGradient/apple-silicon-llm-inference) · [Prism](https://github.com/AtomGradient/Prism) · [hybird-batch-prefill-on-ane](https://github.com/AtomGradient/hybird-batch-prefill-on-ane) · [hybrid-ane-mlx-bench](https://github.com/AtomGradient/hybrid-ane-mlx-bench) · [swift-qwen3-tts](https://github.com/AtomGradient/swift-qwen3-tts) · [swift-gemma-cli](https://github.com/AtomGradient/swift-gemma-cli) · [OptMLX](https://github.com/AtomGradient/OptMLX) · [Vanilla](https://github.com/AtomGradient/Vanilla)

---

<sub>© 2026 AtomGradient · Products and research open-source under MIT</sub>

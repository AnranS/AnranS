<p align="center">
  <img src="./assets/anran-dog-cartoon-banner.png" width="100%" alt="Anran — LLM inference, AI infrastructure, and learning in public. Anran’s gray-and-tan dog, with upright ears and a leaf-shaped hair clip, as a playful cartoon at a laptop." />
</p>

<p align="center">
  <a href="#ai-infra-handbooks"><img src="https://img.shields.io/badge/Focus-LLM%20Inference%20%26%20AI%20Infra-D6A334?style=for-the-badge&logo=nvidia&logoColor=1A1A1A" alt="Focus: LLM Inference and AI Infra" /></a>
  <a href="#learning-in-public"><img src="https://img.shields.io/badge/Learning-In%20Public-242424?style=for-the-badge&logo=readthedocs&logoColor=F7F4EE" alt="Learning in public" /></a>
  <a href="#now-building"><img src="https://img.shields.io/badge/Build-Engines%20%26%20Kernels-8B6745?style=for-the-badge&logo=rust&logoColor=white" alt="Build: engines and kernels" /></a>
</p>

<p align="center">
  <a href="https://github.com/AnranS?tab=followers"><img src="https://img.shields.io/github/followers/AnranS?style=flat-square&color=8B6745&label=Followers" alt="GitHub followers" /></a>
  <a href="https://github.com/AnranS?tab=repositories"><img src="https://img.shields.io/github/stars/AnranS?style=flat-square&color=D6A334&label=Repository%20stars" alt="Stars across public repositories" /></a>
</p>

---

## 👋 About Me

I'm **Anran**. I work on **LLM inference and AI infrastructure** — and I learn it the only way that sticks: by writing the thing from scratch, running it, and measuring it.

Most of what I publish is the trail of that process. An inference engine in Rust + CUDA with validation reports. Thirteen handbooks that walk from a tensor to a serving system, where **every code example is executed in CI and its output compared line by line**. Hundreds of exercises you can solve in the browser.

> Read the paper. Write the kernel. Measure it. Then explain it to someone else.

<p align="center">
  <code>LLM Inference</code> · <code>CUDA Kernels</code> · <code>PyTorch</code> · <code>Distributed Training</code> · <code>Diffusion</code> · <code>Rust Runtimes</code>
</p>

<p align="center">
  <a href="#ai-infra-handbooks">AI Infra Handbooks</a> ·
  <a href="#learning-in-public">Learning in public</a> ·
  <a href="#now-building">Now building</a> ·
  <a href="#open-source-contributions">Contributions</a> ·
  <a href="#project-index">Project index</a>
</p>

---

<a id="ai-infra-handbooks"></a>

## 📚 AI Infra Handbooks — the main thing I'm building

**[ai-infra-handbooks](https://github.com/AnranS/ai-infra-handbooks)** · **[read it →](https://anrans.github.io/ai-infra-handbooks/)** · **[English edition →](https://anrans.github.io/ai-infra-handbooks/en/)**

Thirteen interlinked handbooks that go from "what is a tensor" to "here is a working inference engine", in Chinese and English.

<p align="center">
  <img src="https://img.shields.io/badge/Handbooks-13-D6A334?style=flat-square" alt="13 handbooks" />
  <img src="https://img.shields.io/badge/Chapters-291-8B6745?style=flat-square" alt="291 chapters" />
  <img src="https://img.shields.io/badge/Exercises-288-242424?style=flat-square" alt="288 exercises" />
  <img src="https://img.shields.io/badge/Flashcards-2060-478CBF?style=flat-square" alt="2060 flashcards" />
  <img src="https://img.shields.io/badge/Languages-%E4%B8%AD%E6%96%87%20%2F%20English-76B900?style=flat-square" alt="Chinese and English" />
</p>

| | Handbook | What it covers |
|---|---|---|
| 🧠 | **[LLM Internals](https://anrans.github.io/ai-infra-handbooks/llm/)** | Attention, RoPE, KV Cache, quantization, and the arithmetic behind capacity estimates. |
| 🔥 | **[PyTorch in a Hurry](https://anrans.github.io/ai-infra-handbooks/torch/)** | Tensors, shapes, autograd, `nn.Module`, training loops — enough to read everything else. |
| ⚡ | **[Advanced CUDA](https://anrans.github.io/ai-infra-handbooks/cuda/)** | Reductions, GEMM, FlashAttention, Tensor Cores, Triton, Nsight, `torch.compile`. |
| 🌱 | **[Train a Small Model](https://anrans.github.io/ai-infra-handbooks/scratch/)** | Corpus → BPE tokenizer → a small GPT → SFT, LoRA, DPO, distillation, on your own machine. |
| 🧩 | **[Distributed Training](https://anrans.github.io/ai-infra-handbooks/train/)** | DDP, ZeRO/FSDP, tensor / pipeline / expert parallelism, RL training. |
| 🚀 | **[Inference Systems](https://anrans.github.io/ai-infra-handbooks/serving/)** | Continuous batching, paged KV, prefill/decode disaggregation, speculative decoding, serving ops. |
| 🛠 | **[mini-sglang from Scratch](https://anrans.github.io/ai-infra-handbooks/minisgl/)** | Build a complete inference engine chapter by chapter — scheduler, radix cache, CUDA graphs, TP. |
| 🎨 | **[Image & Video Generation](https://anrans.github.io/ai-infra-handbooks/media/)** | Diffusion and flow matching, samplers, and how generative media is actually served. |
| 📜 | **[SGLang Design Evolution](https://anrans.github.io/ai-infra-handbooks/sglang/)** | Reading a real engine's design through its commit history. |

<sub>Plus four foundations that the rest leans on: **[Python](https://anrans.github.io/ai-infra-handbooks/python/)** · **[C++](https://anrans.github.io/ai-infra-handbooks/cpp/)** · **[CS Fundamentals](https://anrans.github.io/ai-infra-handbooks/cs/)** · **[Math](https://anrans.github.io/ai-infra-handbooks/math/)**.</sub>

**What makes it different from notes:**

- **Every example really runs.** Python, C++ and CUDA samples are executed by CI on each push and their output is compared with the page, line by line — if a number drifts, the build goes red.
- **[288 exercises](https://anrans.github.io/ai-infra-handbooks/practice/)**, graded in your browser (Python on WebAssembly, plus a CUDA simulator) or from the command line on a real GPU.
- **[A learning roadmap](https://anrans.github.io/ai-infra-handbooks/roadmap/)** and **[2060 spaced-repetition flashcards](https://anrans.github.io/ai-infra-handbooks/cards/)** generated from the chapters themselves.
- **Bilingual**, with the English edition built from the same sources so the code can never diverge.

---

<a id="learning-in-public"></a>

## 🧭 The AI stack I'm working through

| Layer | What I'm learning | Where it lives |
|---|---|---|
| **Model internals** | Attention variants, positional encodings, normalization, MoE routing | [LLM Internals](https://anrans.github.io/ai-infra-handbooks/llm/) · [tiny-llm](https://github.com/AnranS/tiny-llm) |
| **Framework** | Autograd, dispatcher, memory allocator, `torch.compile` | [PyTorch in a Hurry](https://anrans.github.io/ai-infra-handbooks/torch/) |
| **Kernels** | Reductions, tiled GEMM, online softmax, FlashAttention, Triton | [Advanced CUDA](https://anrans.github.io/ai-infra-handbooks/cuda/) |
| **Training** | Pretraining a small GPT, SFT, LoRA, DPO, distillation; ZeRO and 3D parallelism | [Train a Small Model](https://anrans.github.io/ai-infra-handbooks/scratch/) · [Distributed Training](https://anrans.github.io/ai-infra-handbooks/train/) |
| **Inference** | Scheduling, paged KV cache, radix prefix reuse, speculative decoding, PD disaggregation | [Inference Systems](https://anrans.github.io/ai-infra-handbooks/serving/) · [nano-vllm-rs](https://github.com/AnranS/nano-vllm-rs) |
| **Engines** | Writing one end to end, then reading how a production engine got there | [mini-sglang](https://anrans.github.io/ai-infra-handbooks/minisgl/) · [SGLang Evolution](https://anrans.github.io/ai-infra-handbooks/sglang/) |
| **Generative media** | Diffusion, flow matching, video pipelines and their serving cost | [Image & Video Generation](https://anrans.github.io/ai-infra-handbooks/media/) |

Everything above is verified on real hardware where it needs to be: the repository ships a [`setup-gpu.sh`](https://github.com/AnranS/ai-infra-handbooks/blob/main/setup-gpu.sh) and a 14-item [`gpu_check.py`](https://github.com/AnranS/ai-infra-handbooks/blob/main/gpu_check.py) self-check that runs the GPU-only examples on an actual card.

---

<a id="now-building"></a>

## 🚀 Now Building

| Track | Projects & direction |
|---|---|
| **AI learning platform** | **[ai-infra-handbooks](https://github.com/AnranS/ai-infra-handbooks)** — 13 bilingual handbooks, 291 chapters, 288 browser-graded exercises, every sample verified in CI. |
| **Inference engineering** | **[nano-vllm-rs](https://github.com/AnranS/nano-vllm-rs)** — single-GPU Qwen3 inference in Rust + CUDA, with attention validation and reproducible benchmarks. No Python, no PyTorch, no libtorch in the inference path. |
| **Inference education** | **[sglang-interactive-guide](https://github.com/AnranS/sglang-interactive-guide)** — 13 Chinese chapters with browser experiments, source links, and exercises. Learn offline, without a GPU. |
| **Runtimes & delivery** | **[wasm-split-tool](https://github.com/AnranS/wasm-split-tool)** — split large WebAssembly modules and load code on demand. |
| **Everyday tools** | **[DesktopPulse](https://github.com/AnranS/DesktopPulse)** · **[inline-vocab-translator](https://github.com/AnranS/inline-vocab-translator)** — desktop widgets and tools for reading across languages. |
| **Game-engine tooling** | **[godot_for_minigame](https://github.com/AnranS/godot_for_minigame)** · **[tiktok-minigame-unity-demo](https://github.com/AnranS/tiktok-minigame-unity-demo)** — exports, platform SDK integration, and working API examples. |

### 🔬 Inside the inference work

**nano-vllm-rs** connects implementation to evidence:

- [Attention validation](https://github.com/AnranS/nano-vllm-rs/blob/main/ATTENTION.md)
- [Stress tests and reproducible results](https://github.com/AnranS/nano-vllm-rs/blob/main/STRESS_TEST.md)
- [Build, run, and inspect the implementation](https://github.com/AnranS/nano-vllm-rs)

Validation currently targets Qwen3-0.6B. Known chunked-output differences are documented in the validation report.

**mini-sglang** (inside the handbooks) goes the other way: 25 chapters that build a working engine — scheduler, radix prefix cache, CUDA graphs, tensor parallelism, an OpenAI-compatible server — with 63 tests that compare its output against Hugging Face token by token.

---

<a id="open-source-contributions"></a>

## 🤝 Open-source Contributions

Selected merged contributions to **[deepcoldy/botmux](https://github.com/deepcoldy/botmux)**, a bridge between IM platforms and AI coding CLIs:

| Contribution | Merged work |
|---|---|
| **Codex integration** | [PR #157](https://github.com/deepcoldy/botmux/pull/157) — support goal passthrough. |
| **Resource efficiency** | [PR #153](https://github.com/deepcoldy/botmux/pull/153) — reduce memory leaks, redundant disk writes, and idle screenshot overhead. |
| **Remote configuration** | [PR #132](https://github.com/deepcoldy/botmux/pull/132) — add `/botconfig` with owner-only configuration cards. |

---

## 🛠 Tech Toolbox

**AI & inference**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Triton](https://img.shields.io/badge/Triton-Kernels-8B6745?style=flat-square)
![SGLang](https://img.shields.io/badge/SGLang-Inference-D6A334?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-Serving-242424?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=1A1A1A)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-242424?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

**Runtimes, apps & tooling**

![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-242424?style=flat-square&logo=swift&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-242424?style=flat-square&logo=unity&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

<a id="project-index"></a>

## 🗂 Project Index

### AI, inference & learning

| Project | Role | Description |
|---|---|---|
| [ai-infra-handbooks](https://github.com/AnranS/ai-infra-handbooks) | Learning platform | 13 bilingual handbooks, 291 chapters, 288 graded exercises, CI-verified examples. |
| [nano-vllm-rs](https://github.com/AnranS/nano-vllm-rs) | Implementation | Rust + CUDA inference engine and validation reports. |
| [sglang-interactive-guide](https://github.com/AnranS/sglang-interactive-guide) | Learning guide | 13 interactive chapters on inference serving. |
| [leetcode](https://github.com/AnranS/leetcode) | Practice | Python and Rust algorithm solutions. |

### Game platforms & developer tools

| Project | Stack | Description |
|---|---|---|
| [godot_for_minigame](https://github.com/AnranS/godot_for_minigame) | Godot · JavaScript | Mini Game export tooling and platform integration. |
| [tiktok-minigame-unity-demo](https://github.com/AnranS/tiktok-minigame-unity-demo) | Unity · C# | Reference examples across 14 SDK API categories, with bilingual documentation. |
| [wasm-split-tool](https://github.com/AnranS/wasm-split-tool) | Rust · WebAssembly | On-demand loading for split WebAssembly modules. |

### Native apps & reading tools

| Project | Stack | Description |
|---|---|---|
| [DesktopPulse](https://github.com/AnranS/DesktopPulse) | Swift · WidgetKit | System, weather, and AI-tool usage widgets for macOS. |
| [inline-vocab-translator](https://github.com/AnranS/inline-vocab-translator) | JavaScript | Inline translation and vocabulary learning. |
| [wallpaper](https://github.com/AnranS/wallpaper) | TypeScript | macOS wallpaper project. |

<details>
<summary>📚 Learning forks & earlier experiments</summary>

These repositories are forks or practice projects, listed separately from the work above.

**Inference & ML learning forks**

- [nano-vllm](https://github.com/AnranS/nano-vllm) · [mini-sglang](https://github.com/AnranS/mini-sglang) · [tiny-llm](https://github.com/AnranS/tiny-llm)
- [minimind](https://github.com/AnranS/minimind) · [pytorch-deep-learning](https://github.com/AnranS/pytorch-deep-learning)

**Runtime & tooling forks**

- [botmux](https://github.com/AnranS/botmux) · [claude-code](https://github.com/AnranS/claude-code)
- [rust](https://github.com/AnranS/rust) · [deno](https://github.com/AnranS/deno) · [node](https://github.com/AnranS/node) · [cocos-engine](https://github.com/AnranS/cocos-engine)

**Personal configuration & practice**

- [nvim](https://github.com/AnranS/nvim) · [leetcode_solutions](https://github.com/AnranS/leetcode_solutions)

</details>

<details>
<summary>📖 Documentation & releases</summary>

- [AI Infra Handbooks — read online](https://anrans.github.io/ai-infra-handbooks/) · [English edition](https://anrans.github.io/ai-infra-handbooks/en/)
- [AI Infra Handbooks — exercises](https://anrans.github.io/ai-infra-handbooks/practice/) · [roadmap](https://anrans.github.io/ai-infra-handbooks/roadmap/) · [flashcards](https://anrans.github.io/ai-infra-handbooks/cards/)
- [SGLang guide: offline entry and source](https://github.com/AnranS/sglang-interactive-guide)
- [Godot Mini Game documentation](https://anrans.github.io/godot_for_minigame/)
- [Godot Mini Game releases](https://github.com/AnranS/godot_for_minigame/releases)
- [wasm-split: how it works](https://github.com/AnranS/wasm-split-tool#how-it-works)
- [wasm-split: performance](https://github.com/AnranS/wasm-split-tool#performance)
- [DesktopPulse setup](https://github.com/AnranS/DesktopPulse#运行)

</details>

<details>
<summary>🏆 GitHub statistics & contribution activity</summary>
<br>
<img src="./assets/public-profile-stats.svg" width="500" alt="Anran's public GitHub profile statistics, dated snapshot" />
<br><br>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AnranS/AnranS/output/github-contribution-grid-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/AnranS/AnranS/output/github-contribution-grid-snake.svg" width="100%" alt="Snake animation of Anran's GitHub contribution grid" />
</picture>

</details>

---

## 📫 Connect

Learning something in the same direction? The handbooks are open — corrections, better explanations and new exercises are all welcome, and every chapter links to the source it came from.

Have a question, an edge case, or an idea for a tool? Open an issue in the relevant project — reproducible examples are always useful.

[![GitHub](https://img.shields.io/badge/GitHub-%40AnranS-242424?style=flat-square&logo=github&logoColor=white)](https://github.com/AnranS?tab=repositories)
[![Handbooks](https://img.shields.io/badge/Read-AI%20Infra%20Handbooks-D6A334?style=flat-square&logo=readthedocs&logoColor=1A1A1A)](https://anrans.github.io/ai-infra-handbooks/)

<sub>Learning through implementation, sharing through working software.</sub>

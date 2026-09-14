<p align="center">
  <img src="./assets/anran-dog-banner.png" width="100%" alt="Anran — inference systems, runtimes, and developer tools. Anran’s gray-and-tan dog, with upright ears and a leaf-shaped hair clip, illustrated at a laptop." />
</p>

<p align="center">
  <a href="#now-building"><img src="https://img.shields.io/badge/Focus-Inference%20Systems-D6A334?style=for-the-badge&logo=nvidia&logoColor=1A1A1A" alt="Focus: Inference Systems" /></a>
  <a href="#selected-work"><img src="https://img.shields.io/badge/Build-Runtimes%20%26%20Tools-242424?style=for-the-badge&logo=rust&logoColor=F7F4EE" alt="Build: Runtimes and Tools" /></a>
  <a href="https://github.com/AnranS?tab=repositories"><img src="https://img.shields.io/badge/Base-Shanghai-8B6745?style=for-the-badge&logoColor=white" alt="Based in Shanghai" /></a>
</p>

<p align="center">
  <a href="https://github.com/AnranS?tab=followers"><img src="https://img.shields.io/github/followers/AnranS?style=flat-square&color=8B6745&label=Followers" alt="GitHub followers" /></a>
  <a href="https://github.com/AnranS?tab=repositories"><img src="https://img.shields.io/github/stars/AnranS?style=flat-square&color=D6A334&label=Repository%20stars" alt="Stars across public repositories" /></a>
</p>

---

## 👋 About Me

I'm **Anran**, building **inference systems, runtimes, and developer tools**. My projects span Rust + CUDA inference, WebAssembly tooling, game-engine integrations, and native macOS apps.

I like opening up the layers between a model and the machine—and turning what I learn into small implementations, interactive guides, and practical tools.

> Understand the internals. Make the behavior visible. Build something useful.

<p align="center">
  <code>LLM Inference</code> · <code>Rust &amp; CUDA</code> · <code>WebAssembly</code> · <code>Game Tooling</code> · <code>Native Apps</code>
</p>

<p align="center">
  <a href="#now-building">Now building</a> ·
  <a href="#selected-work">Selected work</a> ·
  <a href="#open-source-contributions">Contributions</a> ·
  <a href="#project-index">Project index</a>
</p>

---

<a id="now-building"></a>

## 🚀 Now Building & Learning

| Track | Projects & direction |
|---|---|
| **Inference engineering** | **[nano-vllm-rs](https://github.com/AnranS/nano-vllm-rs)** — single-GPU Qwen3 inference in Rust + CUDA, with attention validation and reproducible benchmarks. |
| **Inference education** | **[sglang-interactive-guide](https://github.com/AnranS/sglang-interactive-guide)** — 13 Chinese chapters, browser experiments, source links, and exercises. Learn offline, without a GPU. |
| **Game-engine tooling** | **[godot_for_minigame](https://github.com/AnranS/godot_for_minigame)** · **[tiktok-minigame-unity-demo](https://github.com/AnranS/tiktok-minigame-unity-demo)** — exports, platform SDK integration, and working API examples. |
| **Runtimes & delivery** | **[wasm-split-tool](https://github.com/AnranS/wasm-split-tool)** — split large WebAssembly modules and load code on demand. |
| **Everyday tools** | **[DesktopPulse](https://github.com/AnranS/DesktopPulse)** · **[inline-vocab-translator](https://github.com/AnranS/inline-vocab-translator)** — desktop widgets and tools for reading across languages. |

---

<a id="selected-work"></a>

## ✦ Selected Work

| Project | Focus | What it does |
|---|---|---|
| **[nano-vllm-rs](https://github.com/AnranS/nano-vllm-rs)** | `Rust` `CUDA` | Qwen3 inference on a single GPU. The inference process runs without Python, PyTorch, or libtorch; FlashAttention is optional and experimental. |
| **[SGLang Interactive Guide](https://github.com/AnranS/sglang-interactive-guide)** | `LLM Inference` `Learning` | An offline learning path through scheduling, KV Cache, RadixAttention, speculative decoding, and serving. |
| **[Godot Mini Game](https://github.com/AnranS/godot_for_minigame)** | `Godot` `SDK Integration` | Export Godot 4 games to WeChat and Douyin Mini Games, with TikTok Native in beta. |
| **[wasm-split-tool](https://github.com/AnranS/wasm-split-tool)** | `Rust` `WebAssembly` | Split a module into an eager primary and a lazy secondary that share memory, tables, and globals. |
| **[DesktopPulse](https://github.com/AnranS/DesktopPulse)** | `SwiftUI` `WidgetKit` | Native macOS widgets for system health, weather, and AI-tool usage. |
| **[Inline Vocabulary Translator](https://github.com/AnranS/inline-vocab-translator)** | `JavaScript` `Browser Tools` | Translate Chinese → English while reading, highlight unfamiliar vocabulary, and sync across devices. |

### 🔬 Inside the inference work

**nano-vllm-rs** connects implementation to evidence:

- [Attention validation](https://github.com/AnranS/nano-vllm-rs/blob/main/ATTENTION.md)
- [Stress tests and reproducible results](https://github.com/AnranS/nano-vllm-rs/blob/main/STRESS_TEST.md)
- [Build, run, and inspect the implementation](https://github.com/AnranS/nano-vllm-rs)

Validation currently targets Qwen3-0.6B. Known chunked-output differences are documented in the validation report.

**SGLang Interactive Guide** pairs explanations with browser experiments. The simulations teach mechanisms; they are not GPU benchmarks.

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

**Languages**

![Rust](https://img.shields.io/badge/Rust-242424?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-D6A334?style=flat-square&logo=javascript&logoColor=1A1A1A)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

**Inference & runtimes**

![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![SGLang](https://img.shields.io/badge/SGLang-Inference%20Learning-8B6745?style=flat-square)

**Apps & game tooling**

![SwiftUI](https://img.shields.io/badge/SwiftUI-242424?style=flat-square&logo=swift&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-242424?style=flat-square&logo=unity&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

<a id="project-index"></a>

## 🗂 Project Index

### Inference & learning

| Project | Role | Description |
|---|---|---|
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

- [Godot Mini Game documentation](https://anrans.github.io/godot_for_minigame/)
- [Godot Mini Game releases](https://github.com/AnranS/godot_for_minigame/releases)
- [wasm-split: how it works](https://github.com/AnranS/wasm-split-tool#how-it-works)
- [wasm-split: performance](https://github.com/AnranS/wasm-split-tool#performance)
- [DesktopPulse setup](https://github.com/AnranS/DesktopPulse#运行)
- [SGLang guide: offline entry and source](https://github.com/AnranS/sglang-interactive-guide)

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

Have a question, an edge case, or an idea for a tool? Open an issue in the relevant project—reproducible examples are always useful.

[![GitHub](https://img.shields.io/badge/GitHub-%40AnranS-242424?style=flat-square&logo=github&logoColor=white)](https://github.com/AnranS?tab=repositories)

<sub>Learning through implementation, sharing through working software.</sub>

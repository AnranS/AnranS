<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="./assets/profile-header-mobile-dark.svg" />
    <source media="(prefers-color-scheme: light) and (max-width: 600px)" srcset="./assets/profile-header-mobile-light.svg" />
    <source media="(prefers-color-scheme: dark)" srcset="./assets/profile-header-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/profile-header-light.svg" />
    <img src="./assets/profile-header-light.svg" width="100%" alt="Anran — learning Transformer inference and ML systems from first principles" />
  </picture>
</p>

<h1 align="center">Hi, I'm Anran 👋</h1>

<p align="center">
  <strong>I'm learning modern AI systems by rebuilding Transformer inference from first principles.</strong>
</p>

<p align="center">
  <a href="#ai-learning-in-public">AI learning</a> ·
  <a href="#learning-roadmap">Roadmap</a> ·
  <a href="#systems-background">Systems background</a> ·
  <a href="#toolbox">Toolbox</a>
</p>

My current focus is not just using models, but understanding what happens between tokens and generated text. I turn each topic into small implementations, tests, notebooks, concept notes, and benchmarks—and keep the whole learning trail public.

## AI learning, in public

<table>
  <tr>
    <td width="64%" valign="top">
      <h2><a href="https://github.com/AnranS/transformer-inference-from-scratch">Transformer Inference From Scratch: Zero to One</a></h2>
      <p>From Tokenizer to KV Cache, I'm building a Llama-style decoder-only inference engine step by step—starting from the math, making every tensor shape explicit, and verifying each layer before moving on.</p>
      <p>This is a <strong>40-unit, test-driven learning path</strong> toward Hugging Face numerical parity and reproducible Prefill/Decode performance analysis.</p>
      <p>
        <a href="https://github.com/AnranS/transformer-inference-from-scratch/blob/master/docs/README.md"><strong>Start learning →</strong></a> ·
        <a href="https://github.com/AnranS/transformer-inference-from-scratch/blob/master/docs/roadmap.md">40-unit roadmap</a> ·
        <a href="https://github.com/AnranS/transformer-inference-from-scratch/tree/master/src/mini_transformer">Source</a> ·
        <a href="https://github.com/AnranS/transformer-inference-from-scratch/tree/master/tests">Tests</a>
      </p>
      <p><code>Python</code> <code>PyTorch</code> <code>Transformers</code> <code>pytest</code> <code>Jupyter</code></p>
    </td>
    <td width="36%" valign="top">
      <h3>Current checkpoint</h3>
      <p><code>Day 9 / 40</code></p>
      <p><strong>Built:</strong><br />Embeddings, LM Head, autoregressive generation, causal and padding masks, multi-head attention.</p>
      <p><strong>Next gate:</strong><br />Hugging Face LlamaAttention numerical alignment.</p>
      <p><sub>The live checkpoint is maintained in the learning repository.</sub></p>
    </td>
  </tr>
</table>

### Graduation criteria

- Match final logits with the Hugging Face reference implementation
- Produce identical generation results with and without KV Cache
- Publish reproducible Prefill/Decode benchmarks and performance analysis

## Learning roadmap

| Stage | Focus | Evidence I want to produce |
| --- | --- | --- |
| **01 · Foundations** — built | Tokenizer, embeddings, LM Head, autoregressive generation | Shape contracts, notebooks, unit tests |
| **02 · Model internals** — now | Attention, RMSNorm, SwiGLU, RoPE, decoder blocks | Layer-by-layer numerical alignment |
| **03 · Efficient inference** — next | Sampling, padding, Prefill, Decode, KV Cache | Cache/no-cache correctness parity |
| **04 · ML systems** — next | GQA, benchmarks, profiler, memory analysis | A reproducible performance report |

My learning loop is deliberately engineering-heavy: derive the operation, inspect the shapes, implement the smallest correct version, lock it down with tests, compare against a trusted reference, and only then optimize it.

## Systems background

The same systems mindset shows up in the tools I build outside the learning project:

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/AnranS/pi_spark">pi-spark</a></h3>
      <p>A PostgreSQL-backed distributed run engine for durable agent workloads, with leases, fencing, retries, and capability routing.</p>
      <p><code>TypeScript</code> <code>PostgreSQL</code> <code>Docker</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/AnranS/repo-maestro">Repo Maestro</a></h3>
      <p>A local-first multi-repo workflow orchestrator that plans dependency-aware changes as auditable DAGs.</p>
      <p><code>Rust</code> <code>React</code> <code>Developer Tools</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/AnranS/wasm-split-tool">wasm-split</a></h3>
      <p>A profile-guided Rust splitter and TypeScript runtime for loading large WebAssembly modules in hot and cold stages.</p>
      <p><code>Rust</code> <code>WebAssembly</code> <code>TypeScript</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/AnranS/godot_for_minigame">Godot Mini Game</a></h3>
      <p>Export Godot 4 projects to WeChat, Douyin, and TikTok Mini Games through an editor-native, CI-validated WebAssembly toolchain.</p>
      <p><code>Godot</code> <code>GDScript</code> <code>WebAssembly</code></p>
    </td>
  </tr>
</table>

## Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,rust,wasm,ts,nodejs,swift,godot,postgres,docker,git,githubactions&perline=12" alt="Python, PyTorch, Rust, WebAssembly, TypeScript, Node.js, Swift, Godot, PostgreSQL, Docker, Git, and GitHub Actions" />
</p>

<p align="center">
  <sub>Transformer inference · ML systems · runtime engineering · developer tooling</sub>
</p>

## GitHub at a glance

<p align="center">
  <img src="https://raw.githubusercontent.com/AnranS/AnranS/output/metrics.svg" alt="Anran's GitHub activity overview" width="100%" />
</p>

<details>
  <summary><strong>Languages and contribution trail</strong></summary>
  <br />
  <p align="center">
    <img src="https://raw.githubusercontent.com/AnranS/AnranS/output/metrics-languages.svg" alt="Most-used languages across Anran's repositories" width="62%" />
  </p>
  <p align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AnranS/AnranS/output/github-contribution-grid-snake-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AnranS/AnranS/output/github-contribution-grid-snake.svg" />
      <img src="https://raw.githubusercontent.com/AnranS/AnranS/output/github-contribution-grid-snake.svg" alt="GitHub contribution trail" width="100%" />
    </picture>
  </p>
</details>

<br />

<p align="center">
  <em>Learning in public, one verified tensor shape at a time.</em>
</p>

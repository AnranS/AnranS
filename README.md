<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="./assets/engineering-header-mobile-dark.svg" />
  <source media="(prefers-color-scheme: light) and (max-width: 600px)" srcset="./assets/engineering-header-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="./assets/engineering-header-dark.svg" />
  <img src="./assets/engineering-header-light.svg" width="100%" alt="Anran — inference systems, runtimes, and developer tools. Rust, CUDA, and WebAssembly." />
</picture>

<p>
  <a href="#featured-work">Featured work</a> &nbsp; / &nbsp;
  <a href="#across-the-stack">Across the stack</a> &nbsp; / &nbsp;
  <a href="#built-with">Built with</a>
</p>

I build software close to the runtime: **LLM inference, WebAssembly tooling, game-engine integrations, and native macOS apps.** I care about correctness you can check, experiments you can reproduce, and tools you can use.

## Featured work

<table>
<tr><td>
<sub>01 &nbsp; / &nbsp; INFERENCE SYSTEMS</sub>
<h2><a href="https://github.com/AnranS/nano-vllm-rs">nano-vllm-rs ↗</a></h2>
<p><strong>Qwen3 inference. Rust + CUDA. One GPU.</strong></p>
<p>A native inference engine with paged attention and an optional FlashAttention backend. The inference process runs without Python, PyTorch, or libtorch.</p>
<p><code>Rust</code> <code>CUDA</code> <code>Qwen3</code> <code>BF16</code></p>
<p><a href="https://github.com/AnranS/nano-vllm-rs#本机快速开始"><strong>Build &amp; run →</strong></a> &nbsp; · &nbsp; <a href="https://github.com/AnranS/nano-vllm-rs/blob/main/ATTENTION.md">Attention validation</a> &nbsp; · &nbsp; <a href="https://github.com/AnranS/nano-vllm-rs/blob/main/STRESS_TEST.md">Stress tests</a></p>
<p><sub>Validated on Qwen3-0.6B. FlashAttention is experimental; known chunked-output differences are documented in the validation report.</sub></p>
</td></tr>
</table>

## Across the stack

<table>
<tr>
<td width="50%" valign="top">
<sub>02 &nbsp; / &nbsp; ENGINE TOOLING</sub>
<h3><a href="https://github.com/AnranS/godot_for_minigame">Godot Mini Game ↗</a></h3>
<p>Bring Godot games to WeChat and Douyin Mini Games, with TikTok Native in beta. Engine bundles, platform SDKs, and validated exports in one editor workflow.</p>
<p><code>Godot</code> <code>GDScript</code> <code>WASM</code></p>
<p><a href="https://anrans.github.io/godot_for_minigame/">Documentation</a> · <a href="https://github.com/AnranS/godot_for_minigame/releases">Releases</a></p>
</td>
<td width="50%" valign="top">
<sub>03 &nbsp; / &nbsp; RUNTIME ENGINEERING</sub>
<h3><a href="https://github.com/AnranS/wasm-split-tool">wasm-split ↗</a></h3>
<p>Load large WebAssembly modules in stages. Profile-guided hot/cold splitting pairs a Rust CLI with a TypeScript runtime for code loaded on demand.</p>
<p><code>Rust</code> <code>WebAssembly</code> <code>TypeScript</code></p>
<p><a href="https://github.com/AnranS/wasm-split-tool#how-it-works">Architecture</a> · <a href="https://github.com/AnranS/wasm-split-tool#performance">Performance</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<sub>04 &nbsp; / &nbsp; NATIVE APPS</sub>
<h3><a href="https://github.com/AnranS/DesktopPulse">DesktopPulse ↗</a></h3>
<p>System health, weather, and AI-tool usage on the macOS desktop. Native WidgetKit widgets powered by a local menu-bar app, with glass and cyberpunk appearances.</p>
<p><code>Swift</code> <code>SwiftUI</code> <code>WidgetKit</code></p>
<p><a href="https://github.com/AnranS/DesktopPulse#运行">Build &amp; setup</a></p>
</td>
<td width="50%" valign="top">
<sub>05 &nbsp; / &nbsp; EVERYDAY TOOLS</sub>
<h3><a href="https://github.com/AnranS/inline-vocab-translator">Inline Vocabulary ↗</a></h3>
<p>Chinese-to-English translation where you read. Select text, highlight vocabulary you are learning, and sync across devices through GitHub Gist or Google Drive.</p>
<p><code>JavaScript</code> <code>Browser tooling</code></p>
<p><a href="https://github.com/AnranS/inline-vocab-translator">Explore the project</a></p>
</td>
</tr>
</table>

**Also built:** [TikTok Mini Game Unity Demo](https://github.com/AnranS/tiktok-minigame-unity-demo) — SDK integration examples across 14 API categories, with bilingual documentation.

## Built with

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=rust%2Cpython%2Ccpp%2Cwasm%2Cts%2Cswift%2Cgodot%2Cgit&amp;theme=dark&amp;perline=8" />
  <img src="https://skillicons.dev/icons?i=rust%2Cpython%2Ccpp%2Cwasm%2Cts%2Cswift%2Cgodot%2Cgit&amp;theme=light&amp;perline=8" width="384" alt="Rust, Python, C++, WebAssembly, TypeScript, Swift, Godot, and Git" />
</picture>

<br />

<sub>Explore the code, run an experiment, or open an issue in the relevant repository.</sub>

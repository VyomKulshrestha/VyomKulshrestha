<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0b3b5a&height=205&section=header&text=Vyom%20Kulshrestha&fontSize=46&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=Building%20agentic%20systems%20from%20desktop%20interaction%20to%20kernels%20and%20DNA%20storage&descAlignY=59&descColor=b1bac4&descSize=15" width="100%" alt="Vyom Kulshrestha"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1100&color=58A6FF&center=true&vCenter=true&width=850&lines=Open-source+AI+systems+engineer+and+founder;Heliox+OS+%C2%B7+FerrumOS+%C2%B7+Nucle-OS;Rust+%C2%B7+Python+%C2%B7+TypeScript+%C2%B7+no_std;Autonomy+with+evidence%2C+permissions%2C+and+verification)](https://git.io/typing-svg)

[![Heliox](https://img.shields.io/badge/Heliox_OS-Live-58a6ff?style=for-the-badge&logo=safari&logoColor=white)](https://www.helioxos.dev)
[![FerrumOS](https://img.shields.io/badge/FerrumOS-Research_OS-ff6b6b?style=for-the-badge&logo=rust&logoColor=white)](https://ferrum-os.vercel.app)
[![NucleScript](https://img.shields.io/badge/NucleScript-Try_in_browser-3fb950?style=for-the-badge&logo=webassembly&logoColor=white)](https://nuclescript.github.io/playground/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vyomkulshrestha)
[![Sponsor](https://img.shields.io/badge/GitHub-Sponsor-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/VyomKulshrestha)

</div>

## About me

I am an AI systems engineer and open-source founder in Agra, India, with a CSE (AI/ML) background from VIT. I work across the full stack: Rust kernels and `no_std` userland, Python agent runtimes, TypeScript interfaces, model evaluation, CI, releases, and product design.

My recurring question is:

> How do we give an agent useful autonomy without confusing intelligence with authority?

That is why my projects publish capability boundaries, reproducible evidence, failure history, and limitations alongside the features.

## Three systems, one direction

| Project | What exists today | Start with the evidence |
|---|---|---|
| [**Heliox OS**](https://github.com/VyomKulshrestha/Heliox-OS) | Local-first governed desktop agent for typed, voice, gesture, gaze, browser, application, IDE, and system interaction. Its 21-specialist mesh registers providers for 157 declared actions. | [v0.12.0](https://github.com/VyomKulshrestha/Heliox-OS/releases/tag/v0.12.0) · [Website](https://www.helioxos.dev) · [Proof](https://www.helioxos.dev/proof.html) · [Capabilities](https://www.helioxos.dev/capabilities.json) |
| [**FerrumOS**](https://github.com/VyomKulshrestha/Ferrum-OS) | Bootable x86_64 Rust research OS with Ring-3 userland, capability-gated syscalls, a JEPA-assisted safety screen, and a simulator-backed cyber-physical software tier. | [Website](https://ferrum-os.vercel.app) · [Proof](https://ferrum-os.vercel.app/proof) · [Research paper](https://doi.org/10.5281/zenodo.21829808) |
| [**Nucle-OS**](https://github.com/VyomKulshrestha/Nucle-OS) | Software-defined DNA storage engine plus NucleScript, a compiler-checked DSL for molecular-storage workflows. The current workspace documents 729 discovered tests. | [README and benchmarks](https://github.com/VyomKulshrestha/Nucle-OS#readme) · [Live playground](https://nuclescript.github.io/playground/) |

---

## Heliox OS — multimodal computer control

<div align="center">

[![Heliox OS](https://github-readme-stats.vercel.app/api/pin/?username=VyomKulshrestha&repo=Heliox-OS&theme=github_dark&border_color=30363d&title_color=58a6ff&icon_color=58a6ff&text_color=b1bac4)](https://github.com/VyomKulshrestha/Heliox-OS)

[![Stars](https://img.shields.io/github/stars/VyomKulshrestha/Heliox-OS?style=flat-square&color=58a6ff&labelColor=0d1117)](https://github.com/VyomKulshrestha/Heliox-OS/stargazers)
[![Forks](https://img.shields.io/github/forks/VyomKulshrestha/Heliox-OS?style=flat-square&color=58a6ff&labelColor=0d1117)](https://github.com/VyomKulshrestha/Heliox-OS/forks)
[![Release](https://img.shields.io/github/v/release/VyomKulshrestha/Heliox-OS?style=flat-square&color=58a6ff&labelColor=0d1117)](https://github.com/VyomKulshrestha/Heliox-OS/releases)
[![Downloads](https://img.shields.io/github/downloads/VyomKulshrestha/Heliox-OS/total?style=flat-square&color=7c6fe0&labelColor=0d1117)](https://github.com/VyomKulshrestha/Heliox-OS/releases)
[![CI](https://img.shields.io/github/actions/workflow/status/VyomKulshrestha/Heliox-OS/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/VyomKulshrestha/Heliox-OS/actions/workflows/ci.yml)

</div>

Heliox is an MIT-licensed desktop agent for Windows, macOS, and Linux. It converts natural-language and opt-in multimodal input into validated plans, asks before risky work, and routes actions through permission and verification contracts.

- **157 declared action types** backed by **21 executable specialists**.
- Text, continuous voice, gesture, gaze-region signals, screen context, and experimental neural input share a priority-controlled interaction path.
- Local and cloud model providers plus text-only planning through officially authenticated Codex and Claude Code CLIs; provider credentials remain with the provider tools.
- Local IDE MCP, secure Air Handoff, calendar/email/allowlisted-SSH integrations, plugin manifests, a repository-governed marketplace, approval gates, rollback planning, and outcome verification.
- Public capability catalog, benchmark artifacts, release feeds, failure notes, and agent-readable documentation.
- The measured guarded CPU-status fast path is **27.229 ms median / 29.476 ms p95** across 100 non-LLM iterations; it is not presented as end-to-end voice, browser, provider, or UI latency.

**Current limitation:** provider coverage is not the same as independently observed success. Eleven of the 157 actions currently have an independent post-condition verifier; hardware accuracy for microphones, cameras, gaze, gestures, and EEG requires human testing.

---

## FerrumOS — an operating system boundary for agents

<div align="center">

[![FerrumOS](https://github-readme-stats.vercel.app/api/pin/?username=VyomKulshrestha&repo=Ferrum-OS&theme=github_dark&border_color=30363d&title_color=ff6b6b&icon_color=ff6b6b&text_color=b1bac4)](https://github.com/VyomKulshrestha/Ferrum-OS)

[![Research DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21829808.svg)](https://doi.org/10.5281/zenodo.21829808)
[![CI](https://img.shields.io/github/actions/workflow/status/VyomKulshrestha/Ferrum-OS/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/VyomKulshrestha/Ferrum-OS/actions/workflows/ci.yml)

</div>

FerrumOS studies what changes when an agent acts through an operating-system security boundary rather than only through application-level tools.

- Bootable Rust kernel, ELF loading, real Ring-3 processes, scheduler, filesystem, GUI, and package/runtime services.
- **61-syscall ABI**, **41 canonical agent operations**, and **five permission tiers**.
- Every public tool path passes through deterministic policy and a provider-independent predictive screen before execution.
- Public QEMU evidence covers **101/101 focused command paths** and **81/81 catalog entries** for the recorded audit commit.
- The simulator-backed cyber-physical software tier passes **152/152 deterministic contracts** and **32/32 physical-model, robustness, and neural-decoder gates**.
- Ring-3 world-model preview measurements span **1.29–1.57 ms** run means across H=1…5 with zero measured heap growth in three runs.
- Synthetic neural intent is bounded and fail-closed; physical predictions remain shadow-only and cannot grant actuator authority.

The published fixture reports **81.4% balanced accuracy for rules + JEPA vs 81.2% for rules + a per-action mean baseline**. That is deliberately documented as no material JEPA advantage on that fixture—not hidden behind the headline.

> FerrumOS is a QEMU/Bochs research OS. The cyber-physical results are software and simulator evidence—not proof of installed third-party simulators or transports, robot execution, broad physical-PC compatibility, hard-real-time behavior, formal safety certification, or validated live EEG control.

---

## Nucle-OS — software-defined DNA storage

<div align="center">

[![Nucle-OS](https://github-readme-stats.vercel.app/api/pin/?username=VyomKulshrestha&repo=Nucle-OS&theme=github_dark&border_color=30363d&title_color=3fb950&icon_color=3fb950&text_color=b1bac4)](https://github.com/VyomKulshrestha/Nucle-OS)

[![Release](https://img.shields.io/github/v/release/VyomKulshrestha/Nucle-OS?style=flat-square&color=3fb950&labelColor=0d1117)](https://github.com/VyomKulshrestha/Nucle-OS/releases)
[![Rust](https://img.shields.io/badge/Rust-workspace-3fb950?style=flat-square&logo=rust&labelColor=0d1117)](https://github.com/VyomKulshrestha/Nucle-OS)

</div>

Nucle-OS treats molecular storage as a software system with explicit codecs, recovery, indexing, policy, observability, and hardware-provider boundaries.

- Eight-layer engine: synthesis simulation, encoding, ECC, retrieval/indexing, VFS, agent interface, hardware bridge, and block-device abstraction.
- Yin–Yang, ternary, fountain, and direct-packing codecs with biological constraint checks.
- Reed–Solomon error-and-erasure recovery, fountain erasure repair, and partial-order-alignment consensus.
- Durable VFS with versioning, migration, capacity limits, encryption, integrity scanning, tenancy, audit logs, and Prometheus metrics.
- NucleScript compiler, type/effect system, LSP, VS Code extension, package registry, CLI, native playground, and browser WASM playground.
- **729 discovered tests: 728 passed and one ignored** in the documented workspace run.

The project simulates and integrates DNA-storage workflows in software; it does not claim that every workflow has been run against a production wet lab.

---

## Research and reproducibility

| Artifact | What it establishes | Boundary |
|---|---|---|
| [FerrumOS world-model report](https://doi.org/10.5281/zenodo.21829808) | Reproducible comparison of deterministic rules, JEPA, and baseline prediction at an OS action boundary | Authored fixture; not an independent replication or safety certificate |
| [FerrumOS public dataset](https://doi.org/10.5281/zenodo.21829193) | Versioned evidence used by the published evaluation | Dataset scope does not establish physical deployment accuracy |
| [Heliox proof center](https://www.helioxos.dev/proof.html) | Capability coverage, software benchmarks, known limitations, and failure history | Software CI does not replace physical microphone/camera/EEG testing |
| [Nucle-OS benchmark documentation](https://github.com/VyomKulshrestha/Nucle-OS#demo--it-actually-works) | Codec, noise, ECC, recovery, and full-pipeline software evidence | Simulation and vendor adapters are not wet-lab validation |

## Tools I reach for

<div align="center">

![Rust](https://img.shields.io/badge/Rust-0d1117?style=for-the-badge&logo=rust&logoColor=CE422B)
![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=3178C6)
![Svelte](https://img.shields.io/badge/Svelte-0d1117?style=for-the-badge&logo=svelte&logoColor=FF3E00)
![Tauri](https://img.shields.io/badge/Tauri-0d1117?style=for-the-badge&logo=tauri&logoColor=FFC131)
![WebAssembly](https://img.shields.io/badge/WebAssembly-0d1117?style=for-the-badge&logo=webassembly&logoColor=654FF0)
![QEMU](https://img.shields.io/badge/QEMU-0d1117?style=for-the-badge&logo=qemu&logoColor=FF6600)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=2496ED)

</div>

## Build, validate, contribute

I am interested in collaborations around agentic operating systems, capability security, assistive multimodal interfaces, world models, compilers, and molecular storage.

- Start with [Heliox issues](https://github.com/VyomKulshrestha/Heliox-OS/issues) if you want to improve a user-facing agent.
- Start with [FerrumOS research and architecture](https://github.com/VyomKulshrestha/Ferrum-OS#start-here) if you work on OS or model safety boundaries.
- Try [NucleScript in the browser](https://nuclescript.github.io/playground/) if compilers or DNA storage are your direction.
- Sponsor physical validation, clean-machine testing, and open hardware research through [GitHub Sponsors](https://github.com/sponsors/VyomKulshrestha).

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=VyomKulshrestha&show_icons=true&theme=github_dark&border_color=30363d&title_color=58a6ff&icon_color=58a6ff&text_color=b1bac4&hide_border=false)](https://github.com/VyomKulshrestha)

<br/>

**Build ambitious systems. Measure what they actually do. Publish the gap.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b3b5a,50:161b22,100:0d1117&height=100&section=footer" width="100%" alt="Footer"/>

</div>

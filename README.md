# Awesome Harbor

A curated list of awesome projects in the Harbor ecosystem.

## Contents

- [Evaluation Benchmarks](#evaluation-benchmarks)
- [Training Datasets](#training-datasets)
- [Training & RL](#training--rl)
- [Tools](#tools)

---

## Evaluation Benchmarks

- [terminal-bench-2](https://github.com/laude-institute/terminal-bench-2) - Measures agent ability to complete tasks in a terminal
- [terminal-bench-pro](https://github.com/alibaba/terminal-bench-pro) - Extension of terminal-bench by Alibaba
- [skillsbench](https://github.com/benchflow-ai/skillsbench) - Measures agent ability to use skills
- [otel-bench](https://github.com/QuesmaOrg/otel-bench) - Measures agent ability to instrument code with OpenTelemetry across multiple languages
- [CompileBench](https://github.com/QuesmaOrg/CompileBench) - Measures agent ability to build a working binary from source
- [harbor-datasets](https://github.com/laude-institute/harbor-datasets) - Popular benchmarks (e.g. SWE-bench verified) ported to run in Harbor.
- [RuneBench](https://github.com/MaxBittker/RuneBench) - Measures agent ability to play RuneScape and complete tasks via TypeScript SDK
- [legacy-bench](https://github.com/Factory-AI/legacy-bench) - Evaluates agents on maintaining, debugging, and modernizing legacy code in COBOL, Java 7, Fortran, C, and Assembly
- [SWE-Atlas](https://github.com/scaleapi/SWE-Atlas) - Evaluates agents on professional SWE tasks including codebase comprehension and test writing

## Training Datasets

- [SWE-gen-Java](https://github.com/abundant-ai/SWE-gen-Java) - 1000 JVM tasks generated from 16 open-source GitHub repos using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [SWE-gen-JS](https://github.com/abundant-ai/SWE-gen-JS) - 1000 JS/TS tasks generated from 30 open-source GitHub repos using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [SWE-gen-Rust](https://github.com/abundant-ai/SWE-gen-Rust) - 1000 Rust SWE tasks generated using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [SWE-gen-Go](https://github.com/abundant-ai/SWE-gen-Go) - 1000 Go SWE tasks generated using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [SWE-gen-Cpp](https://github.com/abundant-ai/SWE-gen-Cpp) - 1000 C++ SWE tasks generated using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [Nemotron-Terminal-Synthetic-Tasks](https://huggingface.co/datasets/nvidia/Nemotron-Terminal-Synthetic-Tasks) - Synthetic terminal tasks by NVIDIA
- [seta-env](https://github.com/camel-ai/seta-env) - Scaling Environments for Terminal Agents: fully automated Harbor task synthesis and verification

## Training & RL

- [OpenThoughts-Agent](https://github.com/open-thoughts/OpenThoughts-Agent) - Generating Harbor tasks, distilling trajectories with SFT, and training with SkyRL
- [endless-terminals](https://github.com/kanishkg/endless-terminals) - Procedurally generates terminal-use tasks and trains terminal agents with SkyRL
- [Ares](https://github.com/withmartian/ares) - Framework for online RL training of LLM agents, built on Harbor and SkyRL
- [SkyRL Harbor Integration](https://docs.skyrl.ai/docs/harbor) - Guide for RL training of agents with SkyRL and Harbor

## Tools

- [harbor-bot](https://github.com/parsewave/harbor-bot) - GitHub bot automating QA on Harbor tasks
- [Benchmark Template](https://github.com/harbor-framework/benchmark) - Template for building benchmarks on Harbor with automated QA in CI
- [SWE-gen](https://github.com/abundant-ai/SWE-gen) - Convert GitHub PRs into Harbor tasks
- [Oddish](https://github.com/abundant-ai/oddish) - Eval scheduler for running Harbor tasks with provider-aware queuing and automatic retries
- [TerminalBenchTaskGenerator](https://github.com/yipihey/TerminalBenchTaskGenerator) - Desktop app for chat-driven authoring of Harbor benchmark tasks
- [AutoAgent](https://github.com/kevinrgu/autoagent) - Autonomous system that uses AI agents to iteratively improve other agents' configs and prompts based on benchmark scores

---

## Contributing

Contributions welcome! Open a PR to add a project you have created or love using.

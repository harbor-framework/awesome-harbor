# Awesome Harbor

A curated list of awesome projects in the Harbor ecosystem.

### Contents

- [Evaluation Benchmarks](#evaluation-benchmarks)
- [Training Datasets](#training-datasets)
- [Training & RL](#training--rl)
- [Tools](#tools)

---

### Evaluation Benchmarks

- [Terminal-Bench](https://github.com/harbor-framework/terminal-bench) - Measures frontier agent capabilities across a diverse set of challenging terminal tasks
- [Terminal-Bench 2.1](https://github.com/harbor-framework/terminal-bench-2) - Measures agent ability to complete tasks in a terminal
- [Terminal-Bench Science](https://github.com/harbor-framework/terminal-bench-science) - Evaluates agents on expert-curated scientific research workflows
- [Terminal-Bench Pro](https://github.com/alibaba/terminal-bench-pro) - Extension of Terminal-Bench by Alibaba
- [skillsbench](https://github.com/benchflow-ai/skillsbench) - Measures agent ability to use skills
- [otel-bench](https://github.com/QuesmaOrg/otel-bench) - Measures agent ability to instrument code with OpenTelemetry across multiple languages
- [o11y-bench](https://github.com/grafana/o11y-bench) - Evaluates agents on observability and SRE tasks using a real Grafana stack
- [CompileBench](https://github.com/QuesmaOrg/CompileBench) - Measures agent ability to build a working binary from source
- [APEX-Agents 1.1](https://hub.harborframework.com/datasets/mercor/apex-agents-1-1/latest) - Evaluates agents on long-horizon professional knowledge-work tasks in realistic tool-rich environments
- [RuneBench](https://github.com/MaxBittker/RuneBench) - Measures agent ability to play RuneScape and complete tasks via TypeScript SDK
- [legacy-bench](https://github.com/Factory-AI/legacy-bench) - Evaluates agents on maintaining, debugging, and modernizing legacy code in COBOL, Java 7, Fortran, C, and Assembly
- [SWE-Atlas](https://github.com/scaleapi/SWE-Atlas) - Evaluates agents on professional SWE tasks including codebase comprehension and test writing
- [SWE-sweep](https://github.com/facebookresearch/swe-sweep) - Evaluates agents on autonomously discovering and repairing bugs in large codebases
- [PostTrainBench](https://github.com/aisa-group/PostTrainBench) - Evaluates agents on autonomously post-training language models across diverse downstream tasks

### Training Datasets

- [SWE-gen-Java](https://github.com/abundant-ai/SWE-gen-Java) - 1000 JVM tasks generated from 16 open-source GitHub repos using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [SWE-gen-JS](https://github.com/abundant-ai/SWE-gen-JS) - 1000 JS/TS tasks generated from 30 open-source GitHub repos using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [SWE-gen-Rust](https://github.com/abundant-ai/SWE-gen-Rust) - 1000 Rust SWE tasks generated using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [SWE-gen-Go](https://github.com/abundant-ai/SWE-gen-Go) - 1000 Go SWE tasks generated using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [SWE-gen-Cpp](https://github.com/abundant-ai/SWE-gen-Cpp) - 1000 C++ SWE tasks generated using [SWE-gen](https://github.com/abundant-ai/SWE-gen)
- [Nemotron-Terminal-Synthetic-Tasks](https://huggingface.co/datasets/nvidia/Nemotron-Terminal-Synthetic-Tasks) - Synthetic terminal tasks by NVIDIA
- [seta-env](https://github.com/camel-ai/seta-env) - Scaling Environments for Terminal Agents: fully automated Harbor task synthesis and verification

### Training & RL

- [OpenThoughts-Agent](https://github.com/open-thoughts/OpenThoughts-Agent) - Generating Harbor tasks, distilling trajectories with SFT, and training with SkyRL
- [endless-terminals](https://github.com/kanishkg/endless-terminals) - Procedurally generates terminal-use tasks and trains terminal agents with SkyRL
- [Ares](https://github.com/withmartian/ares) - Framework for online RL training of LLM agents, built on Harbor and SkyRL
- [SkyRL Harbor Integration](https://docs.skyrl.ai/docs/harbor) - Guide for RL training of agents with SkyRL and Harbor
- [ApexAgents-SkyRL-Recipe](https://github.com/Mercor-Intelligence/ApexAgents-SkyRL-Recipe) - End-to-end recipe for RL training knowledge-work agents with Harbor and SkyRL

### Tools

- [harbor-bot](https://github.com/parsewave/harbor-bot) - GitHub bot automating QA on Harbor tasks
- [Benchmark Template](https://github.com/harbor-framework/benchmark) - Template for building benchmarks on Harbor with automated QA in CI
- [SWE-gen](https://github.com/abundant-ai/SWE-gen) - Convert GitHub PRs into Harbor tasks
- [Repo2RLEnv](https://github.com/huggingface/Repo2RLEnv) - Generates verifiable Harbor tasks and RL environments from software repositories
- [Harbor-HF](https://github.com/huggingface/harbor-hf) - Hosted control service for running and managing Harbor benchmarks on Hugging Face Jobs
- [Oddish](https://github.com/abundant-ai/oddish) - Eval scheduler for running Harbor tasks with provider-aware queuing and automatic retries
- [TerminalBenchTaskGenerator](https://github.com/yipihey/TerminalBenchTaskGenerator) - Desktop app for chat-driven authoring of Harbor benchmark tasks
- [AutoAgent](https://github.com/kevinrgu/autoagent) - Autonomous agent harness engineering driven by benchmark scores
- [Meta-Harness](https://github.com/stanford-iris-lab/meta-harness-tbench2-artifact) - Autonomous improvement of harness code using previous iterations and Harbor evaluations
- [ATIF Trajectory Viewer](https://github.com/Slimshilin/ATIF-trajectory-viewer) - Browser-based viewer for replaying agent trajectories and analyzing failures with an automated failure taxonomy

---

### Contributing

Contributions welcome! Open a PR to add a project you have created or love using.

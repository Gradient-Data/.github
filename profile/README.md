<div align="center">

# Gradient Data

### The world is our post-training lab.

Verifiable environments, real-world trajectories, and reinforcement learning infrastructure for frontier labs and enterprises.

[gradientdata.ai](https://gradientdata.ai/) · [logits.dev](https://logits.dev) · [Zero2Repo](https://github.com/Gradient-Data/Zero2Repo)

</div>

## Research at the core

Gradient Data is a research-driven AI company focused on reinforcement learning and model post-training. We build verifiable environments, training data, evaluation systems, and infrastructure for developing more capable and reliable agents.

The vision is to make the world itself a post-training lab, where agents learn through meaningful tasks, observable outcomes, and verifiable feedback.

Backed by Sequoia China and other leading investors. The team brings experience from UC Berkeley, Carnegie Mellon, Tsinghua University, Google, Apple, and ByteDance.

## Inside every environment package

| | |
| --- | --- |
| **Environment** | Runnable tasks, resettable workspaces, and controlled tool interfaces. |
| **Verifier / Reward** | Explicit success criteria, hidden tests, scoring logic, and anti-cheating checks. |
| **Trajectory** | Expert and multi-model success and failure trajectories for training and diagnosis. |
| **Evidence** | Model baselines, quality reports, provenance, failure stages, and repeat-run results. |

Each package documents the task context, success criteria, and observable outcomes, so teams can inspect, reproduce, and learn from agent behavior.

## Environments

### Software Engineering

From building repositories from scratch to developing features in real codebases, CLI engineering, and terminal tasks. Long-horizon environments span hours of development, debugging, and integration, with persistent workspaces and staged verification.

Repository creation · Long-horizon development · Terminal and CLI

Public benchmark: **[Zero2Repo](https://github.com/Gradient-Data/Zero2Repo)** gives an agent a product spec and an empty workspace, then scores the repository with hidden deterministic tests.

### Security

Environments for EVM smart contract security, CVE discovery and remediation, and CTF/Pwn challenges. Reproducible runtimes, isolated execution, and task-specific verifiers connect agent actions to observable security outcomes.

EVM security · CVE remediation · CTF / Pwn

### AI and scientific research

Research tasks across AI/ML, mathematics, physics, and bioinformatics. Single-turn experimental design is assessed primarily through rubrics. Multi-turn AI research environments support training, tuning, and result analysis with staged feedback.

Experimental design · Iterative AI research · Scientific computing

### Professional workflows

Source-grounded analysis and multi-step work across documents, spreadsheets, browsers, and simulated SaaS tools. Deterministic checks and rubric-based evaluation assess workflow execution and the quality of final deliverables.

Documents and spreadsheets · Browser and SaaS · Professional deliverables

## Better feedback. More effective learning.

**Evaluation.** Reproducible, auditable evaluations for long-horizon tasks, complex tool use, reliability, and safety.

**Training infrastructure.** [Logits](https://logits.dev) provides reinforcement learning training APIs for model post-training and experimentation.

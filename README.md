# DI Federation — Governance Architecture & Reference Implementation

This repository accompanies the paper:

**"A Practical Governance Architecture for Federated Multi-Agent AI Systems"**
Author: **Joseph R. Daily**

This repo does **not** contain source code for the live system.
Instead, it provides the architectural documentation and operational reference
for a real, functioning federated multi-agent AI system.

---

## 📄 White Paper

The full governance architecture is described in the paper:

**A Practical Governance Architecture for Federated Multi-Agent AI Systems**

DOI: https://doi.org/10.5281/zenodo.18523384

This paper describes:

- Sovereign memory design
- Federated cross-query without shared state
- Tiered approval governance
- Worker containment and lifecycle control
- Knowledge graph–based epistemic tracking
- Operator observability surfaces for safe supervision

---

## 🔧 Operational Reference (Sanitized)

The file `DI_Federation_Operations_Guide_Sanitized.pdf` is the operational companion to the paper.

It documents how the architecture is implemented in a live system while
intentionally omitting environment-specific details, paths, ports, and code.

This guide shows:

- Agent communication model
- Worker spawning and TTL containment
- Approval workflows
- Memory architecture
- Knowledge graph structure
- Operator dashboard capabilities

---

## 🎨 Diagrams

The `/diagrams` folder contains visual representations of:

- Federated memory architecture
- Worker lifecycle and containment
- Swarm solve process

---

## ⚠️ What This Repository Is Not

This is **not** an open-source agent framework.

This repository exists to document a governance architecture and its
reference implementation for researchers, engineers, and AI safety
practitioners interested in multi-agent system design.

---

## 📬 Contact

For questions, discussion, or demonstrations of the live system,
please reach out via LinkedIn or GitHub.

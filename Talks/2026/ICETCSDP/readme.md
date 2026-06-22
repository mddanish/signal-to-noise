# The Agentic Operator: Automating Adversarial Reasoning with Local AI

This folder contains the complete presentation decks and structural frameworks delivered at **ICETCSDP 2026** (International Conference on Emerging Trends in Cyber Security & Digital Protection), hosted by MSIT, Kolkata[cite: 1].

## 📊 Presentation Editions

The research was structured around two distinct operational open-source agent frameworks[cite: 1]:

1. **[OpenCode Edition (Main Slide Deck)](./agentic-operator-oc-edition.html)**
   * Focuses on dual-agent planning/building methodologies, handling context-window compaction, and managing multi-token tool interactions natively[cite: 1, 2].
2. **[Hermes-Agent Edition (Secondary Slide Deck)](./The-Agentic-Operator.html)**
   * Focuses on self-improving persistent agent skills, custom `agents.md` system doctrines, and setting up constrained operator profiles to gate adversarial actions[cite: 1, 2].

---

## 🛠️ Operational Core Architecture

The research presented demonstrates a fully localized, OpSec-safe adversarial pipeline operating on commodity hardware inside an isolated lab environment[cite: 1]:

```text
PROXMOX HYPERVISOR
├── HERMES AGENT LXC (Ubuntu 24.04) 
│    ├── Hermes WebUI (Kanban Session Tracker)
│    └── Telegram Bot (Mobile C2 Visibility)
│          └── [Connected via Network to] ──► Ollama (Local Model Inference Engine)
├── KALI LINUX VM
│    └── kali-mcp (SSE Server on Port 8000 exposing 35 native security tools)
└── TARGET NETWORK (NeverBreached.local Environment)

```

### Key Technical Concepts Covered:

* **The Context Window Burn Problem:** Why raw tool outputs (like a `/24` Nmap log) degrade LLM reasoning and how context compaction fixes it.


* **The Model Context Protocol (MCP):** Bridging local model brains directly to standard utility execution tools securely.


* **Operator Gating Profiles:** Implementing hard boundaries (`White Hat`, `Grey Hat`, `Red Operator`) to prevent un-scoped or unbounded autonomous lateral movement.


* **Defensive Paradigm Shifts:** Shifting signature-based detection (fragile file hashes) to behavioral graph tracking that targets the *logical chain of intent*.



---

## 🗓️ Event Details

* **Conference:** ICETCSDP 2026 (MSIT, Dept. of Computer Science and Engineering)


* **Location:** Kolkata, India (Hybrid Mode)


* **Timeline:** June 19-20, 2026

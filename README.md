# Dynamic Recursive Tree RAG (DRT-RAG)
### A Self-Evolving Hierarchical Memory Architecture for Agentic AI

**Author:** Alex d'Anjou  
**Date:** April 2026  
**Status:** [Paper One of Three] - Preprint

---

## 🏗️ The Problem: The "Longitudinal Wall"
Current agentic systems struggle with **longitudinal reasoning**. While vector-based RAG excels at local fact-finding, it collapses when asked global questions requiring thematic understanding across months or years of history. 

## 🌲 The Solution: DRT-RAG
**DRT-RAG** is a self-evolving memory architecture that organizes interaction history into a dynamic Directed Acyclic Graph (DAG) navigated by an agentic **Librarian**.

### Key Innovations:
**Multi-Channel Node Schema:** Separates facts from narrative to resist information degradation.
**Agentic Librarian:** An LLM-driven controller that navigates the tree top-down with explicit intent rather than passive vector similarity.
**Current State Ledger:** Resolves temporal conflicts and "time-resolution errors" via a three-date validation protocol.
**Recursive Context Pruning:** Automatically abstracts history into higher-level layers to keep the global memory map within a configured context budget.

---

## 📊 Performance Benchmarks
*DRT-RAG is a substrate proposal targeting ceiling-level performance on **LongMemEval**.

| Metric | Focus |
| :--- | :--- |
| **Longitudinal Reasoning** | Thematic consistency over multi-session history. |
| **Temporal Accuracy** | Resolution of conflicting states over time via the Ledger. |
| **Token Efficiency** | Budgeted layer generation to prevent context window bloat. |

---

## 🗺️ The Unified Memory Roadmap
This series establishes a three-tier memory architecture:

1.  **Paper 1 (Current):** Dynamic Recursive Tree RAG: A Self-Evolving Hierarchical Memory Architecture for Agentic AI.
2.  **Paper 2:** The Goal Isn't Controlled AI — It's Well-Raised AI: Identity Formation Through Sleep-State Memory Consolidation.
3.  **Paper 3:** The Unified Memory Architecture: DRT-RAG and Sleep-State Consolidation as Complementary Tiers.

---

## 🛠️ Implementation & Collaboration
The reference implementation is focusing on a "Gold Standard" test harness for LongMemEval. We are looking for elite engineers to assist with the Librarian navigation loop and Ledger arbitration logic.

[📄 Read the Full Paper (PDF)] Paper/Dynamic Recursive Tree RAG - A Self-Evolving Hierarchical Memory Architecture for Agentic AI.pdf
## 📜 Citation
```text
d'Anjou, A. (2026). Dynamic Recursive Tree RAG: A Self-Evolving Hierarchical Memory Architecture for Agentic AI.

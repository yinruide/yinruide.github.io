---
layout: page
title: DetoxiGuard
description: Agentic LLM guardrail for toxic content detection and correction
img: assets/img/detoxiguard.jpg
importance: 1
category: featured
github: https://github.com/yinruide/DetoxiGuard
---

*Mar 2026 – May 2026* · [GitHub](https://github.com/yinruide/DetoxiGuard)

An agentic guardrail system where the agent invokes a toxicity classifier as a tool and iteratively rewrites flagged LLM outputs until safety checks pass.

- Implemented the pipeline in **LangGraph** with state management, conditional routing, and tool-calling integration, enabling modular swapping of classifiers and LLM backends.
- Fine-tuned **BERT** and **LLaMA** (with **LoRA**) on 159K multi-label samples with multi-GPU **DDP** training, achieving macro-F1 of 0.672 and per-label AUC of 0.985.
- Built a recall-optimized BERT–LLaMA **ensemble** with per-label threshold tuning (F2-score), improving macro-F1 by 42% (0.473 → 0.672) over the TF-IDF + Logistic Regression baseline.

**Stack:** LangGraph · PyTorch · Hugging Face · BERT · LLaMA · LoRA · DDP

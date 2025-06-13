---
layout: publication
title: 'MA-RAG: Multi-agent Retrieval-augmented Generation Via Collaborative Chain-of-thought Reasoning'
authors: Thang Nguyen, Peter Chin, Yu-wing Tai
conference: "Arxiv"
year: 2025
bibkey: nguyen2025ma
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20096"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
We present MA-RAG, a Multi-Agent framework for Retrieval-Augmented Generation (RAG) that addresses the inherent ambiguities and reasoning challenges in complex information-seeking tasks. Unlike conventional RAG methods that rely on either end-to-end fine-tuning or isolated component enhancements, MA-RAG orchestrates a collaborative set of specialized AI agents: Planner, Step Definer, Extractor, and QA Agents, to tackle each stage of the RAG pipeline with task-aware reasoning. Ambiguities may arise from underspecified queries, sparse or indirect evidence in retrieved documents, or the need to integrate information scattered across multiple sources. MA-RAG mitigates these challenges by decomposing the problem into subtasks, such as query disambiguation, evidence extraction, and answer synthesis, and dispatching them to dedicated agents equipped with chain-of-thought prompting. These agents communicate intermediate reasoning and progressively refine the retrieval and synthesis process. Our design allows fine-grained control over information flow without any model fine-tuning. Crucially, agents are invoked on demand, enabling a dynamic and efficient workflow that avoids unnecessary computation. This modular and reasoning-driven architecture enables MA-RAG to deliver robust, interpretable results. Experiments on multi-hop and ambiguous QA benchmarks demonstrate that MA-RAG outperforms state-of-the-art training-free baselines and rivals fine-tuned systems, validating the effectiveness of collaborative agent-based reasoning in RAG.

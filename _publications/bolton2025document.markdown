---
layout: publication
title: 'Document Retrieval Augmented Fine-tuning (DRAFT) For Safety-critical Software Assessments'
authors: Regan Bolton, Mohammadreza Sheikhfathollahi, Simon Parkinson, Vanessa Vulovic, Gary Bamford, Dan Basher, Howard Parkinson
conference: "Arxiv"
year: 2025
bibkey: bolton2025document
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01307"}
tags: ['Responsible AI', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Ethics and Bias', 'Pretraining Methods', 'Interpretability', 'Fine-Tuning']
---
Safety critical software assessment requires robust assessment against
complex regulatory frameworks, a process traditionally limited by manual
evaluation. This paper presents Document Retrieval-Augmented Fine-Tuning
(DRAFT), a novel approach that enhances the capabilities of a large language
model (LLM) for safety-critical compliance assessment. DRAFT builds upon
existing Retrieval-Augmented Generation (RAG) techniques by introducing a novel
fine-tuning framework that accommodates our dual-retrieval architecture, which
simultaneously accesses both software documentation and applicable reference
standards. To fine-tune DRAFT, we develop a semi-automated dataset generation
methodology that incorporates variable numbers of relevant documents with
meaningful distractors, closely mirroring real-world assessment scenarios.
Experiments with GPT-4o-mini demonstrate a 7% improvement in correctness over
the baseline model, with qualitative improvements in evidence handling,
response structure, and domain-specific reasoning. DRAFT represents a practical
approach to improving compliance assessment systems while maintaining the
transparency and evidence-based reasoning essential in regulatory domains.

---
layout: publication
title: 'Aligning Llms To Ask Good Questions A Case Study In Clinical Reasoning'
authors: Shuyue Stella Li, Jimin Mun, Faeze Brahman, Jonathan S. Ilgen, Yulia Tsvetkov, Maarten Sap
conference: "Arxiv"
year: 2025
bibkey: li2025aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14860'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Tools']
---
Large language models (LLMs) often fail to ask effective questions under
uncertainty, making them unreliable in domains where proactive
information-gathering is essential for decisionmaking. We present ALFA, a
framework that improves LLM question-asking by (i) decomposing the notion of a
"good" question into a set of theory-grounded attributes (e.g., clarity,
relevance), (ii) controllably synthesizing attribute-specific question
variations, and (iii) aligning models via preference-based optimization to
explicitly learn to ask better questions along these fine-grained attributes.
Focusing on clinical reasoning as a case study, we introduce the MediQ-AskDocs
dataset, composed of 17k real-world clinical interactions augmented with 80k
attribute-specific preference pairs of follow-up questions, as well as a novel
expert-annotated interactive healthcare QA task to evaluate question-asking
abilities. Models aligned with ALFA reduce diagnostic errors by 56.6% on
MediQ-AskDocs compared to SOTA instruction-tuned LLMs, with a question-level
win-rate of 64.4% and strong generalizability. Our findings suggest that
explicitly guiding question-asking with structured, fine-grained attributes
offers a scalable path to improve LLMs, especially in expert application
domains.

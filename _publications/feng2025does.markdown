---
layout: publication
title: 'Does Knowledge Distillation Matter For Large Language Model Based Bundle Generation?'
authors: Kaidong Feng, Zhu Sun, Jie Yang, Hui Fang, Xinghua Qu, Wenyuan Liu
conference: "Arxiv"
year: 2025
bibkey: feng2025does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.17220"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'RAG', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
LLMs are increasingly explored for bundle generation, thanks to their
reasoning capabilities and knowledge. However, deploying large-scale LLMs
introduces significant efficiency challenges, primarily high computational
costs during fine-tuning and inference due to their massive parameterization.
Knowledge distillation (KD) offers a promising solution, transferring expertise
from large teacher models to compact student models. This study systematically
investigates knowledge distillation approaches for bundle generation, aiming to
minimize computational demands while preserving performance. We explore three
critical research questions: (1) how does the format of KD impact bundle
generation performance? (2) to what extent does the quantity of distilled
knowledge influence performance? and (3) how do different ways of utilizing the
distilled knowledge affect performance? We propose a comprehensive KD framework
that (i) progressively extracts knowledge (patterns, rules, deep thoughts);
(ii) captures varying quantities of distilled knowledge through different
strategies; and (iii) exploits complementary LLM adaptation techniques
(in-context learning, supervised fine-tuning, combination) to leverage
distilled knowledge in small student models for domain-specific adaptation and
enhanced efficiency. Extensive experiments provide valuable insights into how
knowledge format, quantity, and utilization methodologies collectively shape
LLM-based bundle generation performance, exhibiting KD's significant potential
for more efficient yet effective LLM-based bundle generation.

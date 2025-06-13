---
layout: publication
title: 'Med-rlvr: Emerging Medical Reasoning From A 3B Base Model Via Reinforcement Learning'
authors: Sheng Zhang, Qianchu Liu, Guanghui Qin, Tristan Naumann, Hoifung Poon
conference: "Arxiv"
year: 2025
bibkey: zhang2025med
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19655"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Reinforcement learning from verifiable rewards (RLVR) has recently gained
attention for its ability to elicit self-evolved reasoning capabilitie from
base language models without explicit reasoning supervisions, as demonstrated
by DeepSeek-R1. While prior work on RLVR has primarily focused on mathematical
and coding domains, its applicability to other tasks and domains remains
unexplored. In this work, we investigate whether medical reasoning can emerge
from RLVR. We introduce Med-RLVR as an initial study of RLVR in the medical
domain leveraging medical multiple-choice question answering (MCQA) data as
verifiable labels. Our results demonstrate that RLVR is not only effective for
math and coding but also extends successfully to medical question answering.
Notably, Med-RLVR achieves performance comparable to traditional supervised
fine-tuning (SFT) on in-distribution tasks while significantly improving
out-of-distribution generalization, with an 8-point accuracy gain. Further
analysis of training dynamics reveals that, with no explicit reasoning
supervision, reasoning emerges from the 3B-parameter base model. These findings
underscore the potential of RLVR in domains beyond math and coding, opening new
avenues for its application in knowledge-intensive fields such as medicine.

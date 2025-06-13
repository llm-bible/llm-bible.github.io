---
layout: publication
title: 'Can Memory-augmented Language Models Generalize On Reasoning-in-a-haystack Tasks?'
authors: Payel Das, Ching-yun Ko, Sihui Dai, Georgios Kollias, Subhajit Chaudhury, Aurelie Lozano
conference: "Arxiv"
year: 2025
bibkey: das2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07903"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer', 'Reinforcement Learning']
---
Large language models often expose their brittleness in reasoning tasks,
especially while executing long chains of reasoning over context. We propose
MemReasoner, a new and simple memory-augmented LLM architecture, in which the
memory learns the relative order of facts in context, and enables hopping over
them, while the decoder selectively attends to the memory. MemReasoner is
trained end-to-end, with optional supporting fact supervision of varying
degrees. We train MemReasoner, along with existing memory-augmented transformer
models and a state-space model, on two distinct synthetic multi-hop reasoning
tasks. Experiments performed under a variety of challenging scenarios,
including the presence of long distractor text or target answer changes in test
set, show strong generalization of MemReasoner on both single- and two-hop
tasks. This generalization of MemReasoner is achieved using none-to-weak
supporting fact supervision (using none and 1% of supporting facts for one-
and two-hop tasks, respectively). In contrast, baseline models overall struggle
to generalize and benefit far less from using full supporting fact supervision.
The results highlight the importance of explicit memory mechanisms, combined
with additional weak supervision, for improving large language model's context
processing ability toward reasoning tasks.

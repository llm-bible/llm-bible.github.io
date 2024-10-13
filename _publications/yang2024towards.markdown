---
layout: publication
title: 'Metaaligner: Towards Generalizable Multi-objective Alignment Of Language Models'
authors: Yang Kailai, Liu Zhiwei, Xie Qianqian, Huang Jimin, Zhang Tianlin, Ananiadou Sophia
conference: "Arxiv"
year: 2024
bibkey: yang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17141"}
tags: ['In Context Learning', 'Prompting', 'Training Techniques']
---
Recent advancements in large language models (LLMs) aim to tackle
heterogeneous human expectations and values via multi-objective preference
alignment. However, existing methods are parameter-adherent to the policy
model, leading to two key limitations: (1) the high-cost repetition of their
alignment algorithms for each new target model; (2) they cannot expand to
unseen objectives due to their static alignment objectives. In this work, we
propose Meta-Objective Aligner (MetaAligner), a model that performs conditional
weak-to-strong correction for weak responses to approach strong responses.
MetaAligner is the first policy-agnostic and generalizable method for
multi-objective preference alignment, which enables plug-and-play alignment by
decoupling parameter updates from the policy models and facilitates zero-shot
preference alignment for unseen objectives via in-context learning.
Experimental results show that MetaAligner achieves significant and balanced
improvements in multi-objective alignments on 10 state-of-the-art policy
models, and outperforms previous alignment methods with down to 15.71x less GPU
training hours. The model also effectively aligns unseen objectives, marking
the first step towards generalizable multi-objective preference alignment.

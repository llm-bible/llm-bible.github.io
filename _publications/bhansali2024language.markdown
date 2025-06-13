---
layout: publication
title: 'LEGO: Language Model Building Blocks'
authors: Shrenik Bhansali, Alwin Jin, Tyler Lizzo, Larry Heck
conference: "Arxiv"
year: 2024
bibkey: bhansali2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18287"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Pruning', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
Large language models (LLMs) are essential in natural language processing
(NLP) but are costly in data collection, pre-training, fine-tuning, and
inference. Task-specific small language models (SLMs) offer a cheaper
alternative but lack robustness and generalization. This paper proposes LEGO, a
novel technique to extract SLMs from an LLM and recombine them. Using
state-of-the-art LLM pruning strategies, we can create task- and user-specific
SLM building blocks that are efficient for fine-tuning and inference while also
preserving user data privacy. LEGO utilizes Federated Learning and a novel
aggregation scheme for the LLM reconstruction, maintaining robustness without
high costs and preserving user data privacy. We experimentally demonstrate the
versatility of LEGO, showing its ability to enable model heterogeneity and
mitigate the effects of data heterogeneity while maintaining LLM robustness.

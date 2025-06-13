---
layout: publication
title: 'Language-specific Latent Process Hinders Cross-lingual Performance'
authors: Zheng Wei Lim, Alham Fikri Aji, Trevor Cohn
conference: "Arxiv"
year: 2025
bibkey: lim2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13141"}
tags: ['Prompting']
---
Large language models (LLMs) are demonstrably capable of cross-lingual transfer, but can produce inconsistent output when prompted with the same queries written in different languages. To understand how language models are able to generalize knowledge from one language to the others, we apply the logit lens to interpret the implicit steps taken by LLMs to solve multilingual multi-choice reasoning questions. We find LLMs predict inconsistently and are less accurate because they rely on subspaces of individual languages, rather than working in a shared semantic space. While larger models are more multilingual, we show their hidden states are more likely to dissociate from the shared representation compared to smaller models, but are nevertheless more capable of retrieving knowledge embedded across different languages. Finally, we demonstrate that knowledge sharing can be modulated by steering the models' latent processing towards the shared semantic space. We find reinforcing utilization of the shared space improves the models' multilingual reasoning performance, as a result of more knowledge transfer from, and better output consistency with English.

---
layout: publication
title: Tandem Transformers For Inference Efficient Llms
authors: S Aishwarya P, Nair Pranav Ajit, Samaga Yashas, Boyd Toby, Kumar Sanjiv, Jain Prateek, Netrapalli Praneeth
conference: "Arxiv"
year: 2024
bibkey: s2024tandem
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08644"}
tags: ['Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
The autoregressive nature of conventional large language models (LLMs) inherently limits inference speed as tokens are generated sequentially. While speculative and parallel decoding techniques attempt to mitigate this they face limitations either relying on less accurate smaller models for generation or failing to fully leverage the base LLMs representations. We introduce a novel architecture Tandem transformers to address these issues. This architecture uniquely combines (1) a small autoregressive model and (2) a large model operating in block mode (processing multiple tokens simultaneously). The small models predictive accuracy is substantially enhanced by granting it attention to the large models richer representations. On the PaLM2 pretraining dataset a tandem of PaLM2-Bison and PaLM2-Gecko demonstrates a 3.337; improvement in next-token prediction accuracy over a standalone PaLM2-Gecko offering a 1.16x speedup compared to a PaLM2-Otter model with comparable downstream performance. We further incorporate the tandem model within the speculative decoding (SPEED) framework where the large model validates tokens from the small model. This ensures that the Tandem of PaLM2-Bison and PaLM2-Gecko achieves substantial speedup (around 1.14x faster than using vanilla PaLM2-Gecko in SPEED) while maintaining identical downstream task accuracy.

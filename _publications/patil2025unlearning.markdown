---
layout: publication
title: 'Unlearning Sensitive Information In Multimodal Llms: Benchmark And Attack-defense Evaluation'
authors: Vaidehi Patil, Yi-lin Sung, Peter Hase, Jie Peng, Tianlong Chen, Mohit Bansal
conference: "Arxiv"
year: 2025
bibkey: patil2025unlearning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01456"}
tags: ['Responsible AI', 'Tools', 'Interpretability and Explainability', 'RAG', 'Security', 'Multimodal Models', 'Prompting']
---
LLMs trained on massive datasets may inadvertently acquire sensitive
information such as personal details and potentially harmful content. This risk
is further heightened in multimodal LLMs as they integrate information from
multiple modalities (image and text). Adversaries can exploit this knowledge
through multimodal prompts to extract sensitive details. Evaluating how
effectively MLLMs can forget such information (targeted unlearning)
necessitates the creation of high-quality, well-annotated image-text pairs.
While prior work on unlearning has focused on text, multimodal unlearning
remains underexplored. To address this gap, we first introduce a multimodal
unlearning benchmark, UnLOK-VQA (Unlearning Outside Knowledge VQA), as well as
an attack-and-defense framework to evaluate methods for deleting specific
multimodal knowledge from MLLMs. We extend a visual question-answering dataset
using an automated pipeline that generates varying-proximity samples for
testing generalization and specificity, followed by manual filtering for
maintaining high quality. We then evaluate six defense objectives against seven
attacks (four whitebox, three blackbox), including a novel whitebox method
leveraging interpretability of hidden states. Our results show multimodal
attacks outperform text- or image-only ones, and that the most effective
defense removes answer information from internal model states. Additionally,
larger models exhibit greater post-editing robustness, suggesting that scale
enhances safety. UnLOK-VQA provides a rigorous benchmark for advancing
unlearning in MLLMs.

---
layout: publication
title: 'Ctrlrag: Black-box Adversarial Attacks Based On Masked Language Models In Retrieval-augmented Language Generation'
authors: Runqi Sui
conference: "Arxiv"
year: 2025
bibkey: sui2025black
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06950"}
tags: ['Masked Language Model', 'Security', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'BERT']
---
Retrieval-Augmented Generation (RAG) systems enhance Large Language Models
(LLMs) by integrating external knowledge bases. However, this integration
introduces a new security threat: adversaries can exploit the retrieval
mechanism to inject malicious content into the knowledge base, thereby
influencing the generated responses. Based on this attack vector, we propose
CtrlRAG, a novel attack method designed for RAG system in the black-box
setting, which aligns with real-world scenarios. Unlike existing attack
methods, CtrlRAG introduces a perturbation mechanism using Masked Language
Model (MLM) to dynamically optimize malicious content in response to changes in
the retrieved context. Experimental results demonstrate that CtrlRAG
outperforms three baseline methods in both Emotional Manipulation and
Hallucination Amplification objectives. Furthermore, we evaluate three existing
defense mechanisms, revealing their limited effectiveness against CtrlRAG and
underscoring the urgent need for more robust defenses.

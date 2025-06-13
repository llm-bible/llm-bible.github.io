---
layout: publication
title: 'Towards More Robust Retrieval-augmented Generation: Evaluating RAG Under Adversarial Poisoning Attacks'
authors: Jinyan Su, Jin Peng Zhou, Zhengxin Zhang, Preslav Nakov, Claire Cardie
conference: "Arxiv"
year: 2024
bibkey: su2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16708"}
tags: ['Security', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Applications']
---
Retrieval-Augmented Generation (RAG) systems have emerged as a promising
solution to mitigate LLM hallucinations and enhance their performance in
knowledge-intensive domains. However, these systems are vulnerable to
adversarial poisoning attacks, where malicious passages injected into retrieval
databases can mislead the model into generating factually incorrect outputs. In
this paper, we investigate both the retrieval and the generation components of
RAG systems to understand how to enhance their robustness against such attacks.
From the retrieval perspective, we analyze why and how the adversarial contexts
are retrieved and assess how the quality of the retrieved passages impacts
downstream generation. From a generation perspective, we evaluate whether LLMs'
advanced critical thinking and internal knowledge capabilities can be leveraged
to mitigate the impact of adversarial contexts, i.e., using skeptical prompting
as a self-defense mechanism. Our experiments and findings provide actionable
insights into designing safer and more resilient retrieval-augmented
frameworks, paving the way for their reliable deployment in real-world
applications.

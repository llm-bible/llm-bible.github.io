---
layout: publication
title: 'Improving In-context Learning With Small Language Model Ensembles'
authors: M. Mehdi Mojarradi, Lingyi Yang, Robert Mccraith, Adam Mahdi
conference: "Arxiv"
year: 2024
bibkey: mojarradi2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.21868"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) have shown impressive capabilities across
various tasks, but their performance on domain-specific tasks remains limited.
While methods like retrieval augmented generation and fine-tuning can help to
address this, they require significant resources. In-context learning (ICL) is
a cheap and efficient alternative but cannot match the accuracies of advanced
methods. We present Ensemble SuperICL, a novel approach that enhances ICL by
leveraging the expertise of multiple fine-tuned small language models (SLMs).
Ensemble SuperICL achieves state of the art (SoTA) results on several natural
language understanding benchmarks. Additionally, we test it on a medical-domain
labelling task and showcase its practicality by using off-the-shelf SLMs
fine-tuned on a general language task, achieving superior accuracy in
large-scale data labelling compared to all baselines. Finally, we conduct an
ablation study and sensitivity analyses to elucidate the underlying mechanism
of Ensemble SuperICL. Our research contributes to the growing demand for
efficient domain specialisation methods in LLMs, offering a cheap and effective
method for practitioners.

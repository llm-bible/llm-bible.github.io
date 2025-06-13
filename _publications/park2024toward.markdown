---
layout: publication
title: 'Toward Robust Ralms: Revealing The Impact Of Imperfect Retrieval On Retrieval-augmented Language Models'
authors: Seong-il Park, Jay-yoon Lee
conference: "Arxiv"
year: 2024
bibkey: park2024toward
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15107'}
tags: ['Attention Mechanism', 'RAG', 'Efficiency and Optimization', 'Security', 'Model Architecture', 'Reinforcement Learning']
---
Retrieval Augmented Language Models (RALMs) have gained significant attention
for their ability to generate accurate answer and improve efficiency. However,
RALMs are inherently vulnerable to imperfect information due to their reliance
on the imperfect retriever or knowledge source. We identify three common
scenarios-unanswerable, adversarial, conflicting-where retrieved document sets
can confuse RALM with plausible real-world examples. We present the first
comprehensive investigation to assess how well RALMs detect and handle such
problematic scenarios. Among these scenarios, to systematically examine
adversarial robustness we propose a new adversarial attack method, Generative
model-based ADVersarial attack (GenADV) and a novel metric Robustness under
Additional Document (RAD). Our findings reveal that RALMs often fail to
identify the unanswerability or contradiction of a document set, which
frequently leads to hallucinations. Moreover, we show the addition of an
adversary significantly degrades RALM's performance, with the model becoming
even more vulnerable when the two scenarios overlap (adversarial+unanswerable).
Our research identifies critical areas for assessing and enhancing the
robustness of RALMs, laying the foundation for the development of more robust
models.

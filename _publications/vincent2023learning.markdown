---
layout: publication
title: Mtcue Learning Zero45;shot Control Of Extra45;textual Attributes By Leveraging Unstructured Context In Neural Machine Translation
authors: Vincent Sebastian, Flynn Robert, Scarton Carolina
conference: "Arxiv"
year: 2023
bibkey: vincent2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15904"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Efficient utilisation of both intra45; and extra45;textual context remains one of the critical gaps between machine and human translation. Existing research has primarily focused on providing individual well45;defined types of context in translation such as the surrounding text or discrete external variables like the speakers gender. This work introduces MTCue a novel neural machine translation (NMT) framework that interprets all context (including discrete variables) as text. MTCue learns an abstract representation of context enabling transferability across different data settings and leveraging similar attributes in low45;resource scenarios. With a focus on a dialogue domain with access to document and metadata context we extensively evaluate MTCue in four language pairs in both translation directions. Our framework demonstrates significant improvements in translation quality over a parameter45;matched non45;contextual baseline as measured by BLEU (+0.88) and Comet (+1.58). Moreover MTCue significantly outperforms a tagging baseline at translating English text. Analysis reveals that the context encoder of MTCue learns a representation space that organises context based on specific attributes such as formality enabling effective zero45;shot control. Pre45;training on context embeddings also improves MTCues few45;shot performance compared to the tagging baseline. Finally an ablation study conducted on model components and contextual variables further supports the robustness of MTCue for context45;based NMT.

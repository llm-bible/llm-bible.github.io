---
layout: publication
title: 'Contrastive Speaker-aware Learning For Multi-party Dialogue Generation With Llms'
authors: Tianyu Sun, Kun Qian, Wenhong Wang
conference: "Arxiv"
year: 2025
bibkey: sun2025contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08842"}
tags: ['RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Multi-party dialogue generation presents significant challenges due to the
complex interplay of multiple speakers and interwoven conversational threads.
Traditional approaches often fall short in capturing these complexities,
particularly when relying on manually annotated dialogue relations. This paper
introduces Speaker-Attentive LLM (SA-LLM), a novel generative model that
leverages pre-trained Large Language Models (LLMs) and a speaker-aware
contrastive learning strategy to address these challenges. SA-LLM incorporates
a speaker-attributed input encoding and a contrastive learning objective to
implicitly learn contextual coherence and speaker roles without explicit
relation annotations. Extensive experiments on the Ubuntu IRC and Movie
Dialogues datasets demonstrate that SA-LLM significantly outperforms
state-of-the-art baselines in automatic and human evaluations, achieving
superior performance in fluency, coherence, informativeness, and response
diversity. Ablation studies and detailed error analyses further validate the
effectiveness of the proposed speaker-attentive training approach, highlighting
its robustness across different speaker roles and context lengths. The results
underscore the potential of SA-LLM as a powerful and annotation-free solution
for high-quality multi-party dialogue generation.

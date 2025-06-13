---
layout: publication
title: 'Align To Structure: Aligning Large Language Models With Structural Information'
authors: Zae Myung Kim, Anand Ramachandran, Farideh Tavazoee, Joo-kyung Kim, Oleg Rokhlenko, Dongyeop Kang
conference: "Arxiv"
year: 2025
bibkey: kim2025align
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03622"}
  - {name: "Code", url: "https://github.com/minnesotanlp/struct_align"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Generating long, coherent text remains a challenge for large language models
(LLMs), as they lack hierarchical planning and structured organization in
discourse generation. We introduce Structural Alignment, a novel method that
aligns LLMs with human-like discourse structures to enhance long-form text
generation. By integrating linguistically grounded discourse frameworks into
reinforcement learning, our approach guides models to produce coherent and
well-organized outputs. We employ a dense reward scheme within a Proximal
Policy Optimization framework, assigning fine-grained, token-level rewards
based on the discourse distinctiveness relative to human writing. Two
complementary reward models are evaluated: the first improves readability by
scoring surface-level textual features to provide explicit structuring, while
the second reinforces deeper coherence and rhetorical sophistication by
analyzing global discourse patterns through hierarchical discourse motifs,
outperforming both standard and RLHF-enhanced models in tasks such as essay
generation and long-document summarization. All training data and code will be
publicly shared at https://github.com/minnesotanlp/struct_align.

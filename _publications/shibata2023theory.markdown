---
layout: publication
title: 'Theory Of Hallucinations Based On Equivariance'
authors: Hisaichi Shibata
conference: "Arxiv"
year: 2023
bibkey: shibata2023theory
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.14504'}
tags: ['Reinforcement Learning', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
This study aims to acquire knowledge for creating very large language models
that are immune to hallucinations. Hallucinations in contemporary large
language models are often attributed to a misunderstanding of real-world social
relationships. Therefore, I hypothesize that very large language models capable
of thoroughly grasping all these relationships will be free from
hallucinations. Additionally, I propose that certain types of equivariant
language models are adept at learning and understanding these relationships.
Building on this, I have developed a specialized cross-entropy error function
to create a hallucination scale for language models, which measures their
extent of equivariance acquisition. Utilizing this scale, I tested language
models for their ability to acquire character-level equivariance. In
particular, I introduce and employ a novel technique based on T5 (Text To Text
Transfer Transformer) that efficiently understands permuted input texts without
the need for explicit dictionaries to convert token IDs (integers) to texts
(strings). This T5 model demonstrated a moderate ability to acquire
character-level equivariance. Additionally, I discovered scale laws that can
aid in developing hallucination-free language models at the character level.
This methodology can be extended to assess equivariance acquisition at the word
level, paving the way for very large language models that can comprehensively
understand relationships and, consequently, avoid hallucinations.

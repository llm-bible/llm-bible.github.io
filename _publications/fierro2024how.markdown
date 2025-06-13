---
layout: publication
title: 'How Do Multilingual Language Models Remember Facts?'
authors: Constanza Fierro, Negar Foroutan, Desmond Elliott, Anders Søgaard
conference: "Arxiv"
year: 2024
bibkey: fierro2024how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14387'}
tags: ['Training Techniques', 'Pre-Training', 'Model Architecture']
---
Large Language Models (LLMs) store and retrieve vast amounts of factual
knowledge acquired during pre-training. Prior research has localized and
identified mechanisms behind knowledge recall; however, it has only focused on
English monolingual models. The question of how these mechanisms generalize to
non-English languages and multilingual LLMs remains unexplored. In this paper,
we address this gap by conducting a comprehensive analysis of three
multilingual LLMs. First, we show that previously identified recall mechanisms
in English largely apply to multilingual contexts, with nuances based on
language and architecture. Next, through patching intermediate representations,
we localize the role of language during recall, finding that subject enrichment
is language-independent, while object extraction is language-dependent.
Additionally, we discover that the last token representation acts as a Function
Vector (FV), encoding both the language of the query and the content to be
extracted from the subject. Furthermore, in decoder-only LLMs, FVs compose
these two pieces of information in two separate stages. These insights reveal
unique mechanisms in multilingual LLMs for recalling information, highlighting
the need for new methodologies--such as knowledge evaluation, fact editing, and
knowledge acquisition--that are specifically tailored for multilingual LLMs.

---
layout: publication
title: 'Temporal Blind Spots In Large Language Models'
authors: Wallat Jonas, Jatowt Adam, Anand Avishek
conference: "Arxiv"
year: 2024
bibkey: wallat2024temporal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12078"}
  - {name: "Code", url: "https://github.com/jwallat/temporalblindspots"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have recently gained significant attention due
to their unparalleled ability to perform various natural language processing
tasks. These models, benefiting from their advanced natural language
understanding capabilities, have demonstrated impressive zero-shot performance.
However, the pre-training data utilized in LLMs is often confined to a specific
corpus, resulting in inherent freshness and temporal scope limitations.
Consequently, this raises concerns regarding the effectiveness of LLMs for
tasks involving temporal intents. In this study, we aim to investigate the
underlying limitations of general-purpose LLMs when deployed for tasks that
require a temporal understanding. We pay particular attention to handling
factual temporal knowledge through three popular temporal QA datasets.
Specifically, we observe low performance on detailed questions about the past
and, surprisingly, for rather new information. In manual and automatic testing,
we find multiple temporal errors and characterize the conditions under which QA
performance deteriorates. Our analysis contributes to understanding LLM
limitations and offers valuable insights into developing future models that can
better cater to the demands of temporally-oriented tasks. The code is
available\footnote\{https://github.com/jwallat/temporalblindspots\}.

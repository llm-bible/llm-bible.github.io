---
layout: publication
title: 'Tracing Multilingual Factual Knowledge Acquisition In Pretraining'
authors: Yihong Liu, Mingyang Wang, Amir Hossein Kargaran, Felicia Körner, Ercong Nie, Barbara Plank, François Yvon, Hinrich Schütze
conference: "Arxiv"
year: 2025
bibkey: liu2025tracing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14824"}
  - {name: "Code", url: "https://github.com/cisnlp/multilingual-fact-tracing"}
tags: ['Pretraining Methods', 'Training Techniques', 'Has Code', 'Reinforcement Learning']
---
Large Language Models (LLMs) are capable of recalling multilingual factual knowledge present in their pretraining data. However, most studies evaluate only the final model, leaving the development of factual recall and crosslingual consistency throughout pretraining largely unexplored. In this work, we trace how factual recall and crosslingual consistency evolve during pretraining, focusing on OLMo-7B as a case study. We find that both accuracy and consistency improve over time for most languages. We show that this improvement is primarily driven by the fact frequency in the pretraining corpus: more frequent facts are more likely to be recalled correctly, regardless of language. Yet, some low-frequency facts in non-English languages can still be correctly recalled. Our analysis reveals that these instances largely benefit from crosslingual transfer of their English counterparts -- an effect that emerges predominantly in the early stages of pretraining. We pinpoint two distinct pathways through which multilingual factual knowledge acquisition occurs: (1) frequency-driven learning, which is dominant and language-agnostic, and (2) crosslingual transfer, which is limited in scale and typically constrained to relation types involving named entities. We release our code and data to facilitate further research at https://github.com/cisnlp/multilingual-fact-tracing.

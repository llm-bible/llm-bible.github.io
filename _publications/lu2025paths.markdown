---
layout: publication
title: 'Paths Not Taken: Understanding And Mending The Multilingual Factual Recall Pipeline'
authors: Meng Lu, Ruochen Zhang, Carsten Eickhoff, Ellie Pavlick
conference: "Arxiv"
year: 2025
bibkey: lu2025paths
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20546'}
tags: ['Reinforcement Learning']
---
Multilingual large language models (LLMs) often exhibit factual inconsistencies across languages, with significantly better performance in factual recall tasks in English than in other languages. The causes of these failures, however, remain poorly understood. Using mechanistic analysis techniques, we uncover the underlying pipeline that LLMs employ, which involves using the English-centric factual recall mechanism to process multilingual queries and then translating English answers back into the target language. We identify two primary sources of error: insufficient engagement of the reliable English-centric mechanism for factual recall, and incorrect translation from English back into the target language for the final answer. To address these vulnerabilities, we introduce two vector interventions, both independent of languages and datasets, to redirect the model toward better internal paths for higher factual consistency. Our interventions combined increase the recall accuracy by over 35 percent for the lowest-performing language. Our findings demonstrate how mechanistic insights can be used to unlock latent multilingual capabilities in LLMs.

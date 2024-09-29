---
layout: publication
title: Is Your Large Language Model Knowledgeable Or A Choices-only Cheater
authors: Balepur Nishant, Rudinger Rachel
conference: "Arxiv"
year: 2024
bibkey: balepur2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01992"}
tags: ['Ethics And Bias']
---
Recent work shows that large language models (LLMs) can answer multiple-choice questions using only the choices but does this mean that MCQA leaderboard rankings of LLMs are largely influenced by abilities in choices-only settings To answer this we use a contrast set that probes if LLMs over-rely on choices-only shortcuts in MCQA. While previous works build contrast sets via expensive human annotations or model-generated data which can be biased we employ graph mining to extract contrast sets from existing MCQA datasets. We use our method on UnifiedQA a group of six commonsense reasoning datasets with high choices-only accuracy to build an 820-question contrast set. After validating our contrast set we test 12 LLMs finding that these models do not exhibit reliance on choice-only shortcuts when given both the question and choices. Thus despite the susceptibility~of MCQA to high choices-only accuracy we argue that LLMs are not obtaining high ranks on MCQA leaderboards just due to their ability to exploit choices-only shortcuts.

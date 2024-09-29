---
layout: publication
title: 'Measuring Faithfulness In Chain-of-thought Reasoning'
authors: Lanham Tamera, Chen Anna, Radhakrishnan Ansh, Steiner Benoit, Denison Carson, Hernandez Danny, Li Dustin, Durmus Esin, Hubinger Evan, Kernion Jackson, Lukošiūtė Kamilė, Nguyen Karina, Cheng Newton, Joseph Nicholas, Schiefer Nicholas, Rausch Oliver, Larson Robin, Mccandlish Sam, Kundu Sandipan, Kadavath Saurav, Yang Shannon, Henighan Thomas, Maxwell Timothy, Telleen-lawton Timothy, Hume Tristan, Hatfield-dodds Zac, Kaplan Jared, Brauner Jan, Bowman Samuel R., Perez Ethan
conference: "Arxiv"
year: 2023
bibkey: lanham2023measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.13702"}
tags: ['Interpretability And Explainability', 'Pretraining Methods']
---
Large language models (LLMs) perform better when they produce step-by-step Chain-of-Thought (CoT) reasoning before answering a question but it is unclear if the stated reasoning is a faithful explanation of the models actual reasoning (i.e. its process for answering the question). We investigate hypotheses for how CoT reasoning may be unfaithful by examining how the model predictions change when we intervene on the CoT (e.g. by adding mistakes or paraphrasing it). Models show large variation across tasks in how strongly they condition on the CoT when predicting their answer sometimes relying heavily on the CoT and other times primarily ignoring it. CoTs performance boost does not seem to come from CoTs added test-time compute alone or from information encoded via the particular phrasing of the CoT. As models become larger and more capable they produce less faithful reasoning on most tasks we study. Overall our results suggest that CoT can be faithful if the circumstances such as the model size and task are carefully chosen.

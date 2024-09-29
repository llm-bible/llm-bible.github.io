---
layout: publication
title: Prodigy A Profile45;based Dialogue Generation Dataset
authors: Occhipinti Daniela, Tekiroglu Serra Sinem, Guerini Marco
conference: "Arxiv"
year: 2023
bibkey: occhipinti2023profile
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05195"}
tags: ['Agentic', 'Applications', 'Tools', 'Training Techniques']
---
Providing dialogue agents with a profile representation can improve their consistency and coherence leading to better conversations. However current profile45;based dialogue datasets for training such agents contain either explicit profile representations that are simple and dialogue45;specific or implicit representations that are difficult to collect. In this work we propose a unified framework in which we bring together both standard and more sophisticated profile representations by creating a new resource where each dialogue is aligned with all possible speaker representations such as communication style biographies and personality. This framework allows to test several baselines built using generative language models with several profile configurations. The automatic evaluation shows that profile45;based models have better generalisation capabilities than models trained on dialogues only both in45;domain and cross45;domain settings. These results are consistent for fine45;tuned models and instruction45;based LLMs. Additionally human evaluation demonstrates a clear preference for generations consistent with both profile and context. Finally to account for possible privacy concerns all experiments are done under two configurations inter45;character and intra45;character. In the former the LM stores the information about the character in its internal representation while in the latter the LM does not retain any personal information but uses it only at inference time.

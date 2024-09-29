---
layout: publication
title: TEST Text Prototype Aligned Embedding To Activate Llms Ability For Time Series
authors: Sun Chenxi, Li Hongyan, Li Yaliang, Hong Shenda
conference: "Arxiv"
year: 2023
bibkey: sun2023text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.08241"}
tags: ['Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
This work summarizes two ways to accomplish Time45;Series (TS) tasks in todays Large Language Model (LLM) context LLM45;for45;TS (model45;centric) designs and trains a fundamental large model or fine45;tunes a pre45;trained LLM for TS data; TS45;for45;LLM (data45;centric) converts TS into a model45;friendly representation to enable the pre45;trained LLM to handle TS data. Given the lack of data limited resources semantic context requirements and so on this work focuses on TS45;for45;LLM where we aim to activate LLMs ability for TS data by designing a TS embedding method suitable for LLM. The proposed method is named TEST. It first tokenizes TS builds an encoder to embed TS via instance45;wise feature45;wise and text45;prototype45;aligned contrast where the TS embedding space is aligned to LLM embedding layer space then creates soft prompts to make LLM more open to that embeddings and finally implements TS tasks using the frozen LLM. We also demonstrate the feasibility of TS45;for45;LLM through theory and experiments. Experiments are carried out on TS classification forecasting and representation tasks using eight frozen LLMs with various structures and sizes. The results show that the pre45;trained LLM with TEST strategy can achieve better or comparable performance than todays SOTA TS models and offer benefits for few45;shot and generalization. By treating LLM as the pattern machine TEST can endow LLMs ability to process TS data without compromising language ability. We hope that this study will serve as a foundation for future work to support TS+LLM progress.

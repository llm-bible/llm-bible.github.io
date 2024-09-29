---
layout: publication
title: Making Large Language Models Better Data Creators
authors: Lee Dong-ho, Pujara Jay, Sewak Mohit, White Ryen W., Jauhar Sujay Kumar
conference: "Arxiv"
year: 2023
bibkey: lee2023making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20111"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning', 'Security']
---
Although large language models (LLMs) have advanced the state45;of45;the45;art in NLP significantly deploying them for downstream applications is still challenging due to cost responsiveness control or concerns around privacy and security. As such trainable models are still the preferred option in some cases. However these models still require human45;labeled data for optimal performance which is expensive and time45;consuming to obtain. In order to address this issue several techniques to reduce human effort involve labeling or generating data using LLMs. Although these methods are effective for certain applications in practice they encounter difficulties in real45;world scenarios. Labeling data requires careful data selection while generating data necessitates task45;specific prompt engineering. In this paper we propose a unified data creation pipeline that requires only a single formatting example and which is applicable to a broad range of tasks including traditionally problematic ones with semantically devoid label spaces. In our experiments we demonstrate that instruction45;following LLMs are highly cost45;effective data creators and that models trained with these data exhibit performance better than those trained with human45;labeled data (by up to 17.537;) on out45;of45;distribution evaluation while maintaining comparable performance on in45;distribution tasks. These results have important implications for the robustness of NLP systems deployed in the real45;world.

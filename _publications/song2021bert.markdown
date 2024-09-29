---
layout: publication
title: Bob\: BERT Over BERT For Training Persona-based Dialogue Models From Limited Personalized Data
authors: Song Haoyu, Wang Yan, Zhang Kaiyan, Zhang Wei-nan, Liu Ting
conference: "Arxiv"
year: 2021
bibkey: song2021bert
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.06169"}
tags: ['Agentic', 'Applications', 'BERT', 'Model Architecture', 'Training Techniques']
---
Maintaining consistent personas is essential for dialogue agents. Although tremendous advancements have been brought the limited-scale of annotated persona-dense data are still barriers towards training robust and consistent persona-based dialogue models. In this work we show how the challenges can be addressed by disentangling persona-based dialogue generation into two sub-tasks with a novel BERT-over-BERT (BoB) model. Specifically the model consists of a BERT-based encoder and two BERT-based decoders where one decoder is for response generation and another is for consistency understanding. In particular to learn the ability of consistency understanding from large-scale non-dialogue inference data we train the second decoder in an unlikelihood manner. Under different limited data settings both automatic and human evaluations demonstrate that the proposed model outperforms strong baselines in response quality and persona consistency.

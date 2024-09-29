---
layout: publication
title: KPT Keyword45;guided Pre45;training For Grounded Dialog Generation
authors: Zhu Qi, Mi Fei, Zhang Zheng, Wang Yasheng, Li Yitong, Jiang Xin, Liu Qun, Zhu Xiaoyan, Huang Minlie
conference: "Arxiv"
year: 2022
bibkey: zhu2022keyword
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.01739"}
tags: ['Agentic', 'Applications', 'Training Techniques']
---
Incorporating external knowledge into the response generation process is essential to building more helpful and reliable dialog agents. However collecting knowledge45;grounded conversations is often costly calling for a better pre45;trained model for grounded dialog generation that generalizes well w.r.t. different types of knowledge. In this work we propose KPT (Keyword45;guided Pre45;Training) a novel self45;supervised pre45;training method for grounded dialog generation without relying on extra knowledge annotation. Specifically we use a pre45;trained language model to extract the most uncertain tokens in the dialog as keywords. With these keywords we construct two kinds of knowledge and pre45;train a knowledge45;grounded response generation model aiming at handling two different scenarios (1) the knowledge should be faithfully grounded; (2) it can be selectively used. For the former the grounding knowledge consists of keywords extracted from the response. For the latter the grounding knowledge is additionally augmented with keywords extracted from other utterances in the same dialog. Since the knowledge is extracted from the dialog itself KPT can be easily performed on a large volume and variety of dialogue data. We considered three data sources (open45;domain task45;oriented conversational QA) with a total of 2.5M dialogues. We conduct extensive experiments on various few45;shot knowledge45;grounded generation tasks including grounding on dialog acts knowledge graphs persona descriptions and Wikipedia passages. Our comprehensive experiments and analyses demonstrate that KPT consistently outperforms state45;of45;the45;art methods on these tasks with diverse grounding knowledge.

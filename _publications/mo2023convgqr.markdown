---
layout: publication
title: ConvGQR Generative Query Reformulation for Conversational Search
authors: Mo Fengran, Mao Kelong, Zhu Yutao, Wu Yihong, Huang Kaiyu, Nie Jian-yun
conference: "Arxiv"
year: 2023
bibkey: mo2023convgqr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15645"}
tags: ['Merging', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
In conversational search the users real search intent for the current turn is dependent on the previous conversation history. It is challenging to determine a good search query from the whole conversation context. To avoid the expensive re-training of the query encoder most existing methods try to learn a rewriting model to de-contextualize the current query by mimicking the manual query rewriting. However manually rewritten queries are not always the best search queries. Training a rewriting model on them would limit the models ability to produce good search queries. Another useful hint is the potential answer to the question. In this paper we propose ConvGQR a new framework to reformulate conversational queries based on generative pre-trained language models (PLMs) one for query rewriting and another for generating potential answers. By combining both ConvGQR can produce better search queries. In addition to relate query reformulation to retrieval performance we propose a knowledge infusion mechanism to optimize both query reformulation and retrieval. Extensive experiments on four conversational search datasets demonstrate the effectiveness of ConvGQR.

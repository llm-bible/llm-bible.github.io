---
layout: publication
title: 'Unleash Llms Potential For Recommendation By Coordinating Twin-tower Dynamic Semantic Token Generator'
authors: Jun Yin, Zhengxin Zeng, Mingzheng Li, Hao Yan, Chaozhuo Li, Weihao Han, Jianjin Zhang, Ruochen Liu, Allen Sun, Denvy Deng, Feng Sun, Qi Zhang, Shirui Pan, Senzhang Wang
conference: "Arxiv"
year: 2024
bibkey: yin2024unleash
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.09253"}
tags: ['RAG', 'Tools', 'RecSys', 'Merging']
---
Owing to the unprecedented capability in semantic understanding and logical
reasoning, the pre-trained large language models (LLMs) have shown fantastic
potential in developing the next-generation recommender systems (RSs). However,
the static index paradigm adopted by current methods greatly restricts the
utilization of LLMs capacity for recommendation, leading to not only the
insufficient alignment between semantic and collaborative knowledge, but also
the neglect of high-order user-item interaction patterns. In this paper, we
propose Twin-Tower Dynamic Semantic Recommender (TTDS), the first generative RS
which adopts dynamic semantic index paradigm, targeting at resolving the above
problems simultaneously. To be more specific, we for the first time contrive a
dynamic knowledge fusion framework which integrates a twin-tower semantic token
generator into the LLM-based recommender, hierarchically allocating meaningful
semantic index for items and users, and accordingly predicting the semantic
index of target item. Furthermore, a dual-modality variational auto-encoder is
proposed to facilitate multi-grained alignment between semantic and
collaborative knowledge. Eventually, a series of novel tuning tasks specially
customized for capturing high-order user-item interaction patterns are proposed
to take advantages of user historical behavior. Extensive experiments across
three public datasets demonstrate the superiority of the proposed methodology
in developing LLM-based generative RSs. The proposed TTDS recommender achieves
an average improvement of 19.41% in Hit-Rate and 20.84% in NDCG metric,
compared with the leading baseline methods.

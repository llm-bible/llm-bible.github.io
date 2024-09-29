---
layout: publication
title: Bridging Items And Language A Transition Paradigm For Large Language Model45;based Recommendation
authors: Xinyu Lin, Wenjie Wang, Yongqi Li, Fuli Feng, See-kiong Ng, Tat-seng Chua
conference: "Arxiv"
year: 2023
bibkey: lin2023bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2310.06491v2"}
tags: ['Merging', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Harnessing Large Language Models (LLMs) for recommendation is rapidly emerging which relies on two fundamental steps to bridge the recommendation item space and the language space 1) item indexing utilizes identifiers to represent items in the language space and 2) generation grounding associates LLMs generated token sequences to in45;corpus items. However previous methods exhibit inherent limitations in the two steps. Existing ID45;based identifiers (e.g. numeric IDs) and description45;based identifiers (e.g. titles) either lose semantics or lack adequate distinctiveness. Moreover prior generation grounding methods might generate invalid identifiers thus misaligning with in45;corpus items. To address these issues we propose a novel Transition paradigm for LLM45;based Recommender (named TransRec) to bridge items and language. Specifically TransRec presents multi45;facet identifiers which simultaneously incorporate ID title and attribute for item indexing to pursue both distinctiveness and semantics. Additionally we introduce a specialized data structure for TransRec to ensure generating valid identifiers only and utilize substring indexing to encourage LLMs to generate from any position of identifiers. Lastly TransRec presents an aggregated grounding module to leverage generated multi45;facet identifiers to rank in45;corpus items efficiently. We instantiate TransRec on two backbone models BART45;large and LLaMA45;7B. Extensive results on three real45;world datasets under diverse settings validate the superiority of TransRec.

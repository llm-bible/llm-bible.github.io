---
layout: publication
title: 'Empowering Retrieval-based Conversational Recommendation With Contrasting User Preferences'
authors: Heejin Kook, Junyoung Kim, Seongmin Park, Jongwuk Lee
conference: "Arxiv"
year: 2025
bibkey: kook2025empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22005"}
  - {name: "Code", url: "https://github.com/kookeej/CORAL"}
tags: ['RAG', 'RecSys', 'Has Code']
---
Conversational recommender systems (CRSs) are designed to suggest the target
item that the user is likely to prefer through multi-turn conversations. Recent
studies stress that capturing sentiments in user conversations improves
recommendation accuracy. However, they employ a single user representation,
which may fail to distinguish between contrasting user intentions, such as
likes and dislikes, potentially leading to suboptimal performance. To this end,
we propose a novel conversational recommender model, called COntrasting user
pReference expAnsion and Learning (CORAL). Firstly, CORAL extracts the user's
hidden preferences through contrasting preference expansion using the reasoning
capacity of the LLMs. Based on the potential preference, CORAL explicitly
differentiates the contrasting preferences and leverages them into the
recommendation process via preference-aware learning. Extensive experiments
show that CORAL significantly outperforms existing methods in three benchmark
datasets, improving up to 99.72% in Recall@10. The code and datasets are
available at https://github.com/kookeej/CORAL

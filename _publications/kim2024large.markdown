---
layout: publication
title: Large Language Models Meet Collaborative Filtering An Efficient All45;round Llm45;based Recommender System
authors: Kim Sein, Kang Hongseok, Choi Seungyoon, Kim Donghyun, Yang Minchul, Park Chanyoung
conference: "Arxiv"
year: 2024
bibkey: kim2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11343"}
  - {name: "Code", url: "https://github.com/ghdtjr/A&#45;LLMRec"}
tags: ['Efficiency And Optimization', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Collaborative filtering recommender systems (CF45;RecSys) have shown successive results in enhancing the user experience on social media and e45;commerce platforms. However as CF45;RecSys struggles under cold scenarios with sparse user45;item interactions recent strategies have focused on leveraging modality information of user/items (e.g. text or images) based on pre45;trained modality encoders and Large Language Models (LLMs). Despite their effectiveness under cold scenarios we observe that they underperform simple traditional collaborative filtering models under warm scenarios due to the lack of collaborative knowledge. In this work we propose an efficient All45;round LLM45;based Recommender system called A45;LLMRec that excels not only in the cold scenario but also in the warm scenario. Our main idea is to enable an LLM to directly leverage the collaborative knowledge contained in a pre45;trained state45;of45;the45;art CF45;RecSys so that the emergent ability of the LLM as well as the high45;quality user/item embeddings that are already trained by the state45;of45;the45;art CF45;RecSys can be jointly exploited. This approach yields two advantages (1) model45;agnostic allowing for integration with various existing CF45;RecSys and (2) efficiency eliminating the extensive fine45;tuning typically required for LLM45;based recommenders. Our extensive experiments on various real45;world datasets demonstrate the superiority of A45;LLMRec in various scenarios including cold/warm few45;shot cold user and cross45;domain scenarios. Beyond the recommendation task we also show the potential of A45;LLMRec in generating natural language outputs based on the understanding of the collaborative knowledge by performing a favorite genre prediction task. Our code is available at https://github.com/ghdtjr/A&#45;LLMRec .

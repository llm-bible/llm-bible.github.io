---
layout: publication
title: 'Part: Enhancing Proactive Social Chatbots With Personalized Real-time Retrieval'
authors: Zihan Niu, Zheyong Xie, Shaosheng Cao, Chonggang Lu, Zheyu Ye, Tong Xu, Zuozhu Liu, Yan Gao, Jia Chen, Zhe Xu, Yi Wu, Yao Hu
conference: "Arxiv"
year: 2025
bibkey: niu2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20624"}
tags: ['RAG', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Social chatbots have become essential intelligent companions in daily
scenarios ranging from emotional support to personal interaction. However,
conventional chatbots with passive response mechanisms usually rely on users to
initiate or sustain dialogues by bringing up new topics, resulting in
diminished engagement and shortened dialogue duration. In this paper, we
present PaRT, a novel framework enabling context-aware proactive dialogues for
social chatbots through personalized real-time retrieval and generation.
Specifically, PaRT first integrates user profiles and dialogue context into a
large language model (LLM), which is initially prompted to refine user queries
and recognize their underlying intents for the upcoming conversation. Guided by
refined intents, the LLM generates personalized dialogue topics, which then
serve as targeted queries to retrieve relevant passages from RedNote. Finally,
we prompt LLMs with summarized passages to generate knowledge-grounded and
engagement-optimized responses. Our approach has been running stably in a
real-world production environment for more than 30 days, achieving a 21.77%
improvement in the average duration of dialogues.

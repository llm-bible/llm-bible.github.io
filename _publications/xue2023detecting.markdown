---
layout: publication
title: RCOT Detecting And Rectifying Factual Inconsistency In Reasoning By Reversing Chain45;of45;thought
authors: Xue Tianci, Wang Ziqi, Wang Zhenhailong, Han Chi, Yu Pengfei, Ji Heng
conference: "Arxiv"
year: 2023
bibkey: xue2023detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11499"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language Models (LLMs) have achieved promising performance on arithmetic reasoning tasks by incorporating step45;by45;step chain45;of45;thought (CoT) prompting. However LLMs face challenges in maintaining factual consistency during reasoning exhibiting tendencies to condition overlooking question misinterpretation and condition hallucination over given problems. Existing methods use coarse45;grained feedback (e.g. whether the answer is correct) to improve factual consistency. In this work we propose RCoT (Reversing Chain45;of45;Thought) a novel method to improve LLMs reasoning abilities by automatically detecting and rectifying factual inconsistency in LLMs generated solutions. To detect factual inconsistency RCoT first asks LLMs to reconstruct the problem based on generated solutions. Then fine45;grained comparisons between the original problem and the reconstructed problem expose the factual inconsistency in the original solutions. To rectify the solution RCoT formulates detected factual inconsistency into fine45;grained feedback to guide LLMs in revising solutions. Experimental results demonstrate improvements of RCoT over standard CoT Self45;Consistency and Self45;Refine across seven arithmetic datasets. Moreover we find that manually written fine45;grained feedback can dramatically improve LLMs reasoning abilities (e.g. ChatGPT reaches 94.637; accuracy on GSM8K) encouraging the community to further explore the fine45;grained feedback generation methods.

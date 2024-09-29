---
layout: publication
title: Understanding Biases In Chatgpt45;based Recommender Systems Provider Fairness Temporal Stability And Recency
authors: Deldjoo Yashar
conference: "Arxiv"
year: 2024
bibkey: deldjoo2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10545"}
  - {name: "Code", url: "https://github.com/yasdel/Benchmark&#95;RecLLM&#95;Fairness"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
This paper explores the biases in ChatGPT45;based recommender systems focusing on provider fairness (item45;side fairness). Through extensive experiments and over a thousand API calls we investigate the impact of prompt design strategies45;including structure system role and intent45;on evaluation metrics such as provider fairness catalog coverage temporal stability and recency. The first experiment examines these strategies in classical top45;K recommendations while the second evaluates sequential in45;context learning (ICL). In the first experiment we assess seven distinct prompt scenarios on top45;K recommendation accuracy and fairness. Accuracy45;oriented prompts like Simple and Chain45;of45;Thought (COT) outperform diversification prompts which despite enhancing temporal freshness reduce accuracy by up to 5037;. Embedding fairness into system roles such as act as a fair recommender proved more effective than fairness directives within prompts. Diversification prompts led to recommending newer movies offering broader genre distribution compared to traditional collaborative filtering (CF) models. The second experiment explores sequential ICL comparing zero45;shot and few45;shot ICL. Results indicate that including user demographic information in prompts affects model biases and stereotypes. However ICL did not consistently improve item fairness and catalog coverage over zero45;shot learning. Zero45;shot learning achieved higher NDCG and coverage while ICL45;2 showed slight improvements in hit rate (HR) when age45;group context was included. Our study provides insights into biases of RecLLMs particularly in provider fairness and catalog coverage. By examining prompt design learning strategies and system roles we highlight the potential and challenges of integrating LLMs into recommendation systems. Further details can be found at https://github.com/yasdel/Benchmark&#95;RecLLM&#95;Fairness.

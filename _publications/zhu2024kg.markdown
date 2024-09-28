---
layout: publication
title: KG-FPQ Evaluating Factuality Hallucination in LLMs with Knowledge Graph-based False Premise Questions
authors: Zhu Yanxu, Xiao Jinlin, Wang Yuhang, Sang Jitao
conference: "Arxiv"
year: 2024
bibkey: zhu2024kg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05868"}
  - {name: "Code", url: "https://github.com/yanxuzhu/KG-FPQ"}
tags: ['ARXIV', 'Applications', 'GPT', 'Has Code', 'LLM', 'Model Architecture', 'Security']
---
Recent studies have demonstrated that large language models (LLMs) are susceptible to being misled by false premise questions (FPQs) leading to errors in factual knowledge know as factuality hallucination. Existing benchmarks that assess this vulnerability primarily rely on manual construction resulting in limited scale and lack of scalability. In this work we introduce an automated scalable pipeline to create FPQs based on knowledge graphs (KGs). The first step is modifying true triplets extracted from KGs to create false premises. Subsequently utilizing the state-of-the-art capabilities of GPTs we generate semantically rich FPQs. Based on the proposed method we present a comprehensive benchmark the Knowledge Graph-based False Premise Questions (KG-FPQ) which contains approximately 178k FPQs across three knowledge domains at six levels of confusability and in two task formats. Using KG-FPQ we conduct extensive evaluations on several representative LLMs and provide valuable insights. The KG-FPQ dataset and code are available at~https://github.com/yanxuzhu/KG-FPQ.

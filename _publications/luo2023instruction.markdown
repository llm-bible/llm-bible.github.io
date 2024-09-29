---
layout: publication
title: Recranker Instruction Tuning Large Language Model As Ranker For Top45;k Recommendation
authors: Luo Sichun, He Bowei, Zhao Haohan, Shao Wei, Qi Yanlin, Huang Yinya, Zhou Aojun, Yao Yuxuan, Li Zongpeng, Xiao Yuanzhang, Zhan Mingjie, Song Linqi
conference: "Arxiv"
year: 2023
bibkey: luo2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.16018"}
tags: ['Ethics And Bias', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities and have been extensively deployed across various domains including recommender systems. Prior research has employed specialized textit123;prompts125; to leverage the in45;context learning capabilities of LLMs for recommendation purposes. More recent studies have utilized instruction tuning techniques to align LLMs with human preferences promising more effective recommendations. However existing methods suffer from several limitations. The full potential of LLMs is not fully elicited due to low45;quality tuning data and the overlooked integration of conventional recommender signals. Furthermore LLMs may generate inconsistent responses for different ranking tasks in the recommendation potentially leading to unreliable results. In this paper we introduce textbf123;RecRanker125; tailored for instruction tuning LLMs to serve as the textbf123;Ranker125; for top45;textit123;k125; textbf123;Rec125;ommendations. Specifically we introduce an adaptive sampling module for sampling high45;quality representative and diverse training data. To enhance the prompt we introduce a position shifting strategy to mitigate position bias and augment the prompt with auxiliary information from conventional recommendation models thereby enriching the contextual understanding of the LLM. Subsequently we utilize the sampled data to assemble an instruction45;tuning dataset with the augmented prompts comprising three distinct ranking tasks pointwise pairwise and listwise rankings. We further propose a hybrid ranking method to enhance the model performance by ensembling these ranking tasks. Our empirical evaluations demonstrate the effectiveness of our proposed RecRanker in both direct and sequential recommendation scenarios.

---
layout: publication
title: 'Demorank: Selecting Effective Demonstrations For Large Language Models In Ranking Task'
authors: Liu Wenhan, Zhu Yutao, Dou Zhicheng
conference: "Arxiv"
year: 2024
bibkey: liu2024selecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16332"}
  - {name: "Code", url: "https://github.com/8421BCD/DemoRank"}
tags: ['Few Shot', 'Has Code', 'In Context Learning', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recently, there has been increasing interest in applying large language models (LLMs) as zero-shot passage rankers. However, few studies have explored how to select appropriate in-context demonstrations for the passage ranking task, which is the focus of this paper. Previous studies mainly apply a demonstration retriever to retrieve demonstrations and use top-\\(k\\) demonstrations for in-context learning (ICL). Although effective, this approach overlooks the dependencies between demonstrations, leading to inferior performance of few-shot ICL in the passage ranking task. In this paper, we formulate the demonstration selection as a \textit\{retrieve-then-rerank\} process and introduce the DemoRank framework. In this framework, we first use LLM feedback to train a demonstration retriever and construct a novel dependency-aware training samples to train a demonstration reranker to improve few-shot ICL. The construction of such training samples not only considers demonstration dependencies but also performs in an efficient way. Extensive experiments demonstrate DemoRank's effectiveness in in-domain scenarios and strong generalization to out-of-domain scenarios. Our codes are available at~\url\{https://github.com/8421BCD/DemoRank\}.

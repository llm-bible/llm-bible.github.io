---
layout: publication
title: Demorank Selecting Effective Demonstrations For Large Language Models In Ranking Task
authors: Liu Wenhan, Zhu Yutao, Dou Zhicheng
conference: "Arxiv"
year: 2024
bibkey: liu2024selecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16332"}
  - {name: "Code", url: "https://github.com/8421BCD/DemoRank&#125;"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recently there has been increasing interest in applying large language models (LLMs) as zero45;shot passage rankers. However few studies have explored how to select appropriate in45;context demonstrations for the passage ranking task which is the focus of this paper. Previous studies mainly apply a demonstration retriever to retrieve demonstrations and use top45;k demonstrations for in45;context learning (ICL). Although effective this approach overlooks the dependencies between demonstrations leading to inferior performance of few45;shot ICL in the passage ranking task. In this paper we formulate the demonstration selection as a textit123;retrieve45;then45;rerank125; process and introduce the DemoRank framework. In this framework we first use LLM feedback to train a demonstration retriever and construct a novel dependency45;aware training samples to train a demonstration reranker to improve few45;shot ICL. The construction of such training samples not only considers demonstration dependencies but also performs in an efficient way. Extensive experiments demonstrate DemoRanks effectiveness in in45;domain scenarios and strong generalization to out45;of45;domain scenarios. Our codes are available at~url123;https://github.com/8421BCD/DemoRank&#125;.

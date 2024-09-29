---
layout: publication
title: Tool45;augmented Reward Modeling
authors: Li Lei, Chai Yekun, Wang Shuohuan, Sun Yu, Tian Hao, Zhang Ningyu, Wu Hua
conference: "Arxiv"
year: 2023
bibkey: li2023tool
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01045"}
  - {name: "Code", url: "https://github.com/ernie&#45;research/Tool&#45;Augmented&#45;Reward&#45;Model&#125;&#125;"}
tags: ['Agentic', 'GPT', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Reward modeling (a.k.a. preference modeling) is instrumental for aligning large language models with human preferences particularly within the context of reinforcement learning from human feedback (RLHF). While conventional reward models (RMs) have exhibited remarkable scalability they oft struggle with fundamental functionality such as arithmetic computation code execution and factual lookup. In this paper we propose a tool45;augmented preference modeling approach named Themis to address these limitations by empowering RMs with access to external environments including calculators and search engines. This approach not only fosters synergy between tool utilization and reward grading but also enhances interpretive capacity and scoring reliability. Our study delves into the integration of external tools into RMs enabling them to interact with diverse external sources and construct task45;specific tool engagement and reasoning traces in an autoregressive manner. We validate our approach across a wide range of domains incorporating seven distinct external tools. Our experimental results demonstrate a noteworthy overall improvement of 17.737; across eight tasks in preference ranking. Furthermore our approach outperforms Gopher 280B by 7.337; on TruthfulQA task in zero45;shot evaluation. In human evaluations RLHF trained with Themis attains an average win rate of 3237; when compared to baselines across four distinct tasks. Additionally we provide a comprehensive collection of tool45;related RM datasets incorporating data from seven distinct tool APIs totaling 15000 instances. We have made the code data and model checkpoints publicly available to facilitate and inspire further research advancementsfootnote123;url123;https://github.com/ernie&#45;research/Tool&#45;Augmented&#45;Reward&#45;Model&#125;&#125;.

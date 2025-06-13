---
layout: publication
title: 'A Comparative Study On Reasoning Patterns Of Openai''s O1 Model'
authors: Siwei Wu, Zhongyuan Peng, Xinrun Du, Tuney Zheng, Minghao Liu, Jialong Wu, Jiachen Ma, Yizhi Li, Jian Yang, Wangchunshu Zhou, Qunshu Lin, Junbo Zhao, Zhaoxiang Zhang, Wenhao Huang, Ge Zhang, Chenghua Lin, J. H. Liu
conference: "Arxiv"
year: 2024
bibkey: wu2024comparative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13639"}
tags: ['Agentic', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Prompting', 'Attention Mechanism']
---
Enabling Large Language Models (LLMs) to handle a wider range of complex
tasks (e.g., coding, math) has drawn great attention from many researchers. As
LLMs continue to evolve, merely increasing the number of model parameters
yields diminishing performance improvements and heavy computational costs.
Recently, OpenAI's o1 model has shown that inference strategies (i.e.,
Test-time Compute methods) can also significantly enhance the reasoning
capabilities of LLMs. However, the mechanisms behind these methods are still
unexplored. In our work, to investigate the reasoning patterns of o1, we
compare o1 with existing Test-time Compute methods (BoN, Step-wise BoN, Agent
Workflow, and Self-Refine) by using OpenAI's GPT-4o as a backbone on general
reasoning benchmarks in three domains (i.e., math, coding, commonsense
reasoning). Specifically, first, our experiments show that the o1 model has
achieved the best performance on most datasets. Second, as for the methods of
searching diverse responses (e.g., BoN), we find the reward models' capability
and the search space both limit the upper boundary of these methods. Third, as
for the methods that break the problem into many sub-problems, the Agent
Workflow has achieved better performance than Step-wise BoN due to the
domain-specific system prompt for planning better reasoning processes. Fourth,
it is worth mentioning that we have summarized six reasoning patterns of o1,
and provided a detailed analysis on several reasoning benchmarks.

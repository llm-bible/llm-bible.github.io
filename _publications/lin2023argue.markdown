---
layout: publication
title: Argue With Me Tersely Towards Sentence-level Counter-argument Generation
authors: Lin Jiayu, Ye Rong, Han Meng, Zhang Qi, Lai Ruofei, Zhang Xinyu, Cao Zhao, Huang Xuanjing, Wei Zhongyu
conference: "Arxiv"
year: 2023
bibkey: lin2023argue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.13608"}
  - {name: "Code", url: "https://github.com/amazingljy1206/ArgTersely"}
tags: ['Applications', 'BERT', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
Counter-argument generation -- a captivating area in computational linguistics -- seeks to craft statements that offer opposing views. While most research has ventured into paragraph-level generation sentence-level counter-argument generation beckons with its unique constraints and brevity-focused challenges. Furthermore the diverse nature of counter-arguments poses challenges for evaluating model performance solely based on n-gram-based metrics. In this paper we present the ArgTersely benchmark for sentence-level counter-argument generation drawing from a manually annotated dataset from the ChangeMyView debate forum. We also propose Arg-LlaMA for generating high-quality counter-argument. For better evaluation we trained a BERT-based evaluator Arg-Judge with human preference data. We conducted comparative experiments involving various baselines such as LlaMA Alpaca GPT-3 and others. The results show the competitiveness of our proposed framework and evaluator in counter-argument generation tasks. Code and data are available at https://github.com/amazingljy1206/ArgTersely."

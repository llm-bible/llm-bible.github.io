---
layout: publication
title: 'Just Ask One More Time! Self-agreement Improves Reasoning Of Language Models In (almost) All Scenarios'
authors: Lin Lei, Fu Jiayi, Liu Pengli, Li Qingyang, Gong Yan, Wan Junchen, Zhang Fuzheng, Wang Zhongyuan, Zhang Di, Gai Kun
conference: "Arxiv"
year: 2023
bibkey: lin2023just
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08154"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Prompting', 'RAG']
---
Although chain-of-thought (CoT) prompting combined with language models has achieved encouraging results on complex reasoning tasks the naive greedy decoding used in CoT prompting usually causes the repetitiveness and local optimality. To address this shortcoming ensemble-optimization tries to obtain multiple reasoning paths to get the final answer assembly. However current ensemble-optimization methods either simply employ rule-based post-processing such as (textitself-consistency) or train an additional model based on several task-related human annotations to select the best one among multiple reasoning paths yet fail to generalize to realistic settings where the type of input questions is unknown or the answer format of reasoning paths is unknown. To avoid their limitations we propose (textbfSelf-Agreement) a generalizable ensemble-optimization method applying in almost all scenarios where the type of input questions and the answer format of reasoning paths may be known or unknown. Self-agreement firstly samples from language models decoder to generate a (textitdiverse) set of reasoning paths and subsequently prompts the language model (textitone more time) to determine the optimal answer by selecting the most (textitagreed) answer among the sampled reasoning paths. Self-agreement simultaneously achieves remarkable performance on six public reasoning benchmarks and superior generalization capabilities.

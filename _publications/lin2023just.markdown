---
layout: publication
title: Just Ask One More Time! Self45;agreement Improves Reasoning Of Language Models In (almost) All Scenarios
authors: Lin Lei, Fu Jiayi, Liu Pengli, Li Qingyang, Gong Yan, Wan Junchen, Zhang Fuzheng, Wang Zhongyuan, Zhang Di, Gai Kun
conference: "Arxiv"
year: 2023
bibkey: lin2023just
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08154"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Prompting', 'RAG']
---
Although chain45;of45;thought (CoT) prompting combined with language models has achieved encouraging results on complex reasoning tasks the naive greedy decoding used in CoT prompting usually causes the repetitiveness and local optimality. To address this shortcoming ensemble45;optimization tries to obtain multiple reasoning paths to get the final answer assembly. However current ensemble45;optimization methods either simply employ rule45;based post45;processing such as textit123;self45;consistency125; or train an additional model based on several task45;related human annotations to select the best one among multiple reasoning paths yet fail to generalize to realistic settings where the type of input questions is unknown or the answer format of reasoning paths is unknown. To avoid their limitations we propose textbf123;Self45;Agreement125; a generalizable ensemble45;optimization method applying in almost all scenarios where the type of input questions and the answer format of reasoning paths may be known or unknown. Self45;agreement firstly samples from language models decoder to generate a textit123;diverse125; set of reasoning paths and subsequently prompts the language model textit123;one more time125; to determine the optimal answer by selecting the most textit123;agreed125; answer among the sampled reasoning paths. Self45;agreement simultaneously achieves remarkable performance on six public reasoning benchmarks and superior generalization capabilities.

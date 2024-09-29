---
layout: publication
title: Ml-bench\: Evaluating Large Language Models And Agents For Machine Learning Tasks On Repository-level Code
authors: Tang Xiangru, Liu Yuliang, Cai Zefan, Shao Yanjun, Lu Junjie, Zhang Yichi, Deng Zexuan, Hu Helan, An Kaikai, Huang Ruijun, Si Shuzheng, Chen Sheng, Zhao Haozhe, Chen Liang, Wang Yan, Liu Tianyu, Jiang Zhiwei, Chang Baobao, Fang Yin, Qin Yujia, Zhou Wangchunshu, Zhao Yilun, Cohan Arman, Gerstein Mark
conference: "Arxiv"
year: 2023
bibkey: tang2023ml
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09835"}
  - {name: "Code", url: "https://github.com/gersteinlab/ML-bench"}
tags: ['Agent', 'Agentic', 'Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Despite Large Language Models (LLMs) like GPT-4 achieving impressive results in function-level code generation they struggle with repository-scale code understanding (e.g. coming up with the right arguments for calling routines) requiring a deeper comprehension of complex file interactions. Also recently people have developed LLM agents that attempt to interact with repository code (e.g. compiling and evaluating its execution) prompting the need to evaluate their performance. These gaps have motivated our development of ML-Bench a benchmark rooted in real-world programming applications that leverage existing code repositories to perform tasks. Addressing the need for LLMs to interpret long code contexts and translate instructions into precise executable scripts ML-Bench encompasses annotated 9641 examples across 18 GitHub repositories challenging LLMs to accommodate user-specified arguments and documentation intricacies effectively. To evaluate both LLMs and AI agents two setups are employed ML-LLM-Bench for assessing LLMs text-to-code conversion within a predefined deployment environment and ML-Agent-Bench for testing autonomous agents in an end-to-end task execution within a Linux sandbox environment. Our findings indicate that while GPT-4o leads with a Pass@5 rate surpassing 5037; there remains significant scope for improvement highlighted by issues such as hallucinated outputs and difficulties with bash script generation. Notably in the more demanding ML-Agent-Bench GPT-4o achieves a 76.4737; success rate reflecting the efficacy of iterative action and feedback in complex task resolution. Our code dataset and models are available at https://github.com/gersteinlab/ML-bench."

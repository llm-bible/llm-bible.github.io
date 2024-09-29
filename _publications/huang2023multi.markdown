---
layout: publication
title: Agentcoder\: Multi-agent-based Code Generation With Iterative Testing And Optimisation
authors: Huang Dong, Zhang Jie M., Luck Michael, Bu Qingwen, Qing Yuhao, Cui Heming
conference: "Arxiv"
year: 2023
bibkey: huang2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.13010"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Transformer']
---
The advancement of natural language processing (NLP) has been significantly boosted by the development of transformer-based large language models (LLMs). These models have revolutionized NLP tasks particularly in code generation aiding developers in creating software with enhanced efficiency. Despite their advancements challenges in balancing code snippet generation with effective test case generation and execution persist. To address these issues this paper introduces Multi-Agent Assistant Code Generation (AgentCoder) a novel solution comprising a multi-agent framework with specialized agents the programmer agent the test designer agent and the test executor agent. During the coding procedure the programmer agent will focus on the code generation and refinement based on the test executor agents feedback. The test designer agent will generate test cases for the generated code and the test executor agent will run the code with the test cases and write the feedback to the programmer. This collaborative system ensures robust code generation surpassing the limitations of single-agent models and traditional methodologies. Our extensive experiments on 9 code generation models and 12 enhancement approaches showcase AgentCoders superior performance over existing code generation models and prompt engineering techniques across various benchmarks. For example AgentCoder (GPT-4) achieves 96.337; and 91.837; pass@1 in HumanEval and MBPP datasets with an overall token overhead of 56.9K and 66.3K while state-of-the-art obtains only 90.237; and 78.937; pass@1 with an overall token overhead of 138.2K and 206.5K.

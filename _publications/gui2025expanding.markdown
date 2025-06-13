---
layout: publication
title: 'CRPE: Expanding The Reasoning Capability Of Large Language Model For Code Generation'
authors: Ningxin Gui, Qianghuai Jia, Feijun Jiang, Yuling Jiao, Dechun Wang, Jerry Zhijian Yang
conference: "Arxiv"
year: 2025
bibkey: gui2025expanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10594'}
tags: ['GPT', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'Reinforcement Learning']
---
We introduce CRPE (Code Reasoning Process Enhancer), an innovative three-stage framework for data synthesis and model training that advances the development of sophisticated code reasoning capabilities in large language models (LLMs). Building upon existing system-1 models, CRPE addresses the fundamental challenge of enhancing LLMs' analytical and logical processing in code generation tasks. Our framework presents a methodologically rigorous yet implementable approach to cultivating advanced code reasoning abilities in language models. Through the implementation of CRPE, we successfully develop an enhanced COT-Coder that demonstrates marked improvements in code generation tasks. Evaluation results on LiveCodeBench (20240701-20240901) demonstrate that our COT-Coder-7B-StepDPO, derived from Qwen2.5-Coder-7B-Base, with a pass@1 accuracy of 21.88, exceeds all models with similar or even larger sizes. Furthermore, our COT-Coder-32B-StepDPO, based on Qwen2.5-Coder-32B-Base, exhibits superior performance with a pass@1 accuracy of 35.08, outperforming GPT4O on the benchmark. Overall, CRPE represents a comprehensive, open-source method that encompasses the complete pipeline from instruction data acquisition through expert code reasoning data synthesis, culminating in an autonomous reasoning enhancement mechanism.

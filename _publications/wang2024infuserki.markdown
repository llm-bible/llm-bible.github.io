---
layout: publication
title: InfuserKI Enhancing Large Language Models with Knowledge Graphs via Infuser-Guided Knowledge Integration
authors: Wang Fali, Bao Runxue, Wang Suhang, Yu Wenchao, Liu Yanchi, Cheng Wei, Chen Haifeng
conference: "Arxiv"
year: 2024
bibkey: wang2024infuserki
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11441"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Though Large Language Models (LLMs) have shown remarkable open-generation capabilities across diverse domains they struggle with knowledge-intensive tasks. To alleviate this issue knowledge integration methods have been proposed to enhance LLMs with domain-specific knowledge graphs using external modules. However they suffer from data inefficiency as they require both known and unknown knowledge for fine-tuning. Thus we study a novel problem of integrating unknown knowledge into LLMs efficiently without unnecessary overlap of known knowledge. Injecting new knowledge poses the risk of forgetting previously acquired knowledge. To tackle this we propose a novel Infuser-Guided Knowledge Integration (InfuserKI) framework that utilizes transformer internal states to determine whether to enhance the original LLM output with additional information thereby effectively mitigating knowledge forgetting. Evaluations on the UMLS-2.5k and MetaQA domain knowledge graphs demonstrate that InfuserKI can effectively acquire new knowledge and outperform state-of-the-art baselines by 9 and 6 respectively in reducing knowledge forgetting.

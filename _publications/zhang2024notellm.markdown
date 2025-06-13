---
layout: publication
title: 'Notellm-2: Multimodal Large Representation Models For Recommendation'
authors: Chao Zhang, Haoxin Zhang, Shiwei Wu, Di Wu, Tong Xu, Xiangyu Zhao, Yan Gao, Yao Hu, Enhong Chen
conference: "Arxiv"
year: 2024
bibkey: zhang2024notellm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.16789'}
  - {name: "Code", url: 'https://github.com/Applied-Machine-Learning-Lab/NoteLLM'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Merging', 'Tools', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated exceptional proficiency in
text understanding and embedding tasks. However, their potential in multimodal
representation, particularly for item-to-item (I2I) recommendations, remains
underexplored. While leveraging existing Multimodal Large Language Models
(MLLMs) for such tasks is promising, challenges arise due to their delayed
release compared to corresponding LLMs and the inefficiency in representation
tasks. To address these issues, we propose an end-to-end fine-tuning method
that customizes the integration of any existing LLMs and vision encoders for
efficient multimodal representation. Preliminary experiments revealed that
fine-tuned LLMs often neglect image content. To counteract this, we propose
NoteLLM-2, a novel framework that enhances visual information. Specifically, we
propose two approaches: first, a prompt-based method that segregates visual and
textual content, employing a multimodal In-Context Learning strategy to balance
focus across modalities; second, a late fusion technique that directly
integrates visual information into the final representations. Extensive
experiments, both online and offline, demonstrate the effectiveness of our
approach. Code is available at
https://github.com/Applied-Machine-Learning-Lab/NoteLLM.

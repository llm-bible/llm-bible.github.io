---
layout: publication
title: 'Concentrate Attention: Towards Domain-generalizable Prompt Optimization For Language Models'
authors: Li Chengzhengxu, Liu Xiaoming, Zhang Zhaohan, Wang Yichen, Liu Chen, Lan Yu, Shen Chao
conference: "Arxiv"
year: 2024
bibkey: li2024concentrate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10584"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
'Recent advances in prompt optimization have notably enhanced the performance of pre-trained language models (PLMs) on downstream tasks. However, the potential of optimized prompts on domain generalization has been under-explored. To explore the nature of prompt generalization on unknown domains, we conduct pilot experiments and find that (i) Prompts gaining more attention weight from PLMs'' deep layers are more generalizable and (ii) Prompts with more stable attention distributions in PLMs'' deep layers are more generalizable. Thus, we offer a fresh objective towards domain-generalizable prompts optimization named Concentration, which represents the lookback attention from the current decoding token to the prompt tokens, to increase the attention strength on prompts and reduce the fluctuation of attention distribution. We adapt this new objective to popular soft prompt and hard prompt optimization methods, respectively. Extensive experiments demonstrate that our idea improves comparison prompt optimization methods by 1.42&#37; for soft prompt generalization and 2.16&#37; for hard prompt generalization in accuracy on the multi-source domain generalization setting, while maintaining satisfying in-domain performance. The promising results validate the effectiveness of our proposed prompt optimization objective and provide key insights into domain-generalizable prompts.'

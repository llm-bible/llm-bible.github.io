---
layout: publication
title: 'Large Language Model Can Continue Evolving From Mistakes'
authors: Zhao Haokun, Han Haixia, Shi Jie, Du Chengyu, Liang Jiaqing, Xiao Yanghua
conference: "Arxiv"
year: 2024
bibkey: zhao2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08707"}
tags: ['Applications', 'Efficiency And Optimization', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
As world knowledge evolves and new task paradigms emerge, Continual Learning (CL) is crucial for keeping Large Language Models (LLMs) up-to-date and addressing their shortcomings. In practical applications, LLMs often require both continual instruction tuning (CIT) and continual pre-training (CPT) to adapt to new task paradigms and acquire necessary knowledge for task-solving. However, it remains challenging to collect CPT data that addresses the knowledge deficiencies in models while maintaining adequate volume, and improving the efficiency of utilizing this data also presents significant difficulties. Inspired by the 'summarizing mistakes' learning skill, we propose the Continue Evolving from Mistakes (CEM) method, aiming to provide a data-efficient approach for collecting CPT data and continually improving LLMs' performance through iterative evaluation and supplementation with mistake-relevant knowledge. To efficiently utilize these CPT data and mitigate forgetting, we design a novel CL training set construction paradigm that integrates parallel CIT and CPT data. Extensive experiments demonstrate the efficacy of the CEM method, achieving up to a 17&#37; improvement in accuracy in the best case. Furthermore, additional experiments confirm the potential of combining CEM with catastrophic forgetting mitigation methods, enabling iterative and continual model evolution.

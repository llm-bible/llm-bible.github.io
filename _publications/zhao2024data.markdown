---
layout: publication
title: 'CEM: A Data-efficient Method For Large Language Models To Continue Evolving From Mistakes'
authors: Haokun Zhao, Haixia Han, Jie Shi, Chengyu Du, Jiaqing Liang, Yanghua Xiao
conference: "Arxiv"
year: 2024
bibkey: zhao2024data
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.08707'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/cem-BB25'}
tags: ['Reinforcement Learning', 'Pre-Training', 'Has Code', 'Training Techniques']
---
As world knowledge advances and new task schemas emerge, Continual Learning
(CL) becomes essential for keeping Large Language Models (LLMs) current and
addressing their shortcomings. This process typically involves continual
instruction tuning (CIT) and continual pre-training (CPT) to enable these
models to adapt to novel tasks and acquire critical knowledge. However,
collecting sufficient CPT data and efficiently bridging knowledge gaps remain
significant challenges. Inspired by the 'summarizing mistakes' strategy, we
propose the Continue Evolving from Mistakes (CEM) method, a data-efficient
approach aiming to collect CPT data and continually improve LLMs' performance
through iterative evaluation and supplementation with mistake-relevant
knowledge. To further optimize data usage and mitigate forgetting, we introduce
a novel training paradigm that combines CIT and CPT. Experiments show that CEM
substantially enhances multiple models' performance on both in-domain and
out-of-domain QA tasks, achieving gains of up to 29.63%. Code and datasets are
available on https://anonymous.4open.science/r/cem-BB25.

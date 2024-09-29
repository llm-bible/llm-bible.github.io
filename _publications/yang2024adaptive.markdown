---
layout: publication
title: Adazeta Adaptive Zeroth45;order Tensor45;train Adaption For Memory45;efficient Large Language Models Fine45;tuning
authors: Yang Yifan, Zhen Kai, Banijamal Ershad, Mouchtaris Athanasios, Zhang Zheng
conference: "Arxiv"
year: 2024
bibkey: yang2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18060"}
tags: ['BERT', 'Efficiency And Optimization', 'Model Architecture', 'Tools']
---
Fine45;tuning large language models (LLMs) has achieved remarkable performance across various natural language processing tasks yet it demands more and more memory as model sizes keep growing. To address this issue the recently proposed Memory45;efficient Zeroth45;order (MeZO) methods attempt to fine45;tune LLMs using only forward passes thereby avoiding the need for a backpropagation graph. However significant performance drops and a high risk of divergence have limited their widespread adoption. In this paper we propose the Adaptive Zeroth45;order Tensor45;Train Adaption (AdaZeta) framework specifically designed to improve the performance and convergence of the ZO methods. To enhance dimension45;dependent ZO estimation accuracy we introduce a fast45;forward low45;parameter tensorized adapter. To tackle the frequently observed divergence issue in large45;scale ZO fine45;tuning tasks we propose an adaptive query number schedule that guarantees convergence. Detailed theoretical analysis and extensive experimental results on Roberta45;Large and Llama45;245;7B models substantiate the efficacy of our AdaZeta framework in terms of accuracy memory efficiency and convergence speed.

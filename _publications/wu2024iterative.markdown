---
layout: publication
title: ITERTL An Iterative Framework For Fine45;tuning Llms For RTL Code Generation
authors: Wu Peiyang, Guo Nan, Xiao Xiao, Li Wenming, Ye Xiaochun, Fan Dongrui
conference: "Arxiv"
year: 2024
bibkey: wu2024iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12022"}
tags: ['Applications', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recently large language models (LLMs) have demonstrated excellent performance in understanding human instructions and generating code which has inspired researchers to explore the feasibility of generating RTL code with LLMs. However the existing approaches to fine45;tune LLMs on RTL codes typically are conducted on fixed datasets which do not fully stimulate the capability of LLMs and require large amounts of reference data. To mitigate these issues we introduce a simple yet effective iterative training paradigm named ITERTL. During each iteration samples are drawn from the model trained in the previous cycle. Then these new samples are employed for training in this loop. Through this iterative approach the distribution mismatch between the model and the training samples is reduced. Additionally the model is thus enabled to explore a broader generative space and receive more comprehensive feedback. Theoretical analyses are conducted to investigate the mechanism of the effectiveness. Experimental results show the model trained through our proposed approach can compete with and even outperform the state45;of45;the45;art (SOTA) open45;source model with nearly 3737; reference samples achieving remarkable 42.937; and 62.237; pass35;64;1 rate on two VerilogEval evaluation datasets respectively. While using the same amount of reference samples our method can achieved a relative improvement of 16.937; and 12.537; in pass35;64;1 compared to the non45;iterative method. This study facilitates the application of LLMs for generating RTL code in practical scenarios with limited data.

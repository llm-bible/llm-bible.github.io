---
layout: publication
title: Progressively Selective Label Enhancement For Language Model Alignment
authors: Liu Biao, Xu Ning, Geng Xin
conference: "Arxiv"
year: 2024
bibkey: liu2024progressively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02599"}
tags: ['Agentic', 'Reinforcement Learning', 'Responsible AI', 'Tools']
---
Large Language Models have demonstrated impressive capabilities in various language tasks but may produce content that misaligns with human expectations raising ethical and legal concerns. Therefore it is important to explore the limitations and implement restrictions on the models to ensure safety and compliance with Reinforcement Learning from Human Feedback (RLHF) being the primary method. Due to challenges in stability and scalability with the RLHF stages researchers are exploring alternative methods to achieve effects comparable to those of RLHF. However these methods often depend on large high45;quality datasets and inefficiently utilize generated data. To deal with this problem we propose PSLE i.e. Progressively Selective Label Enhancement for Language Model Alignment a framework that fully utilizes all generated data by guiding the model with principles to align outputs with human expectations. Using a dynamically updated threshold our approach ensures efficient data utilization by incorporating all generated responses and weighting them based on their corresponding reward scores. Experimental results on multiple datasets demonstrate the effectiveness of PSLE compared to existing language model alignment methods.

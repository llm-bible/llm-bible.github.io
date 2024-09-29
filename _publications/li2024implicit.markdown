---
layout: publication
title: Implicit In45;context Learning
authors: Li Zhuowei, Xu Zihao, Han Ligong, Gao Yunhe, Wen Song, Liu Di, Wang Hao, Metaxas Dimitris N.
conference: "Arxiv"
year: 2024
bibkey: li2024implicit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14660"}
  - {name: "Code", url: "https://github.com/LzVv123456/I2CL"}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Security']
---
In45;context Learning (ICL) empowers large language models (LLMs) to adapt to unseen tasks during inference by prefixing a few demonstration examples prior to test queries. Despite its versatility ICL incurs substantial computational and memory overheads compared to zero45;shot learning and is susceptible to the selection and order of demonstration examples. In this work we introduce Implicit In45;context Learning (I2CL) an innovative paradigm that addresses the challenges associated with traditional ICL by absorbing demonstration examples within the activation space. I2CL first generates a condensed vector representation namely a context vector from the demonstration examples. It then integrates the context vector during inference by injecting a linear combination of the context vector and query activations into the models residual streams. Empirical evaluation on nine real45;world tasks across three model architectures demonstrates that I2CL achieves few45;shot performance with zero45;shot cost and exhibits robustness against the variation of demonstration examples. Furthermore I2CL facilitates a novel representation of task45;ids enhancing task similarity detection and enabling effective transfer learning. We provide a comprehensive analysis of I2CL offering deeper insights into its mechanisms and broader implications for ICL. The source code is available at https://github.com/LzVv123456/I2CL.

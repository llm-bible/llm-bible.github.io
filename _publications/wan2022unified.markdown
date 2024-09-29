---
layout: publication
title: 'Unite: Unified Translation Evaluation'
authors: Wan Yu, Liu Dayiheng, Yang Baosong, Zhang Haibo, Chen Boxing, Wong Derek F., Chao Lidia S.
conference: "Arxiv"
year: 2022
bibkey: wan2022unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.13346"}
  - {name: "Code", url: "https://github.com/NLP2CT/UniTE"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Translation quality evaluation plays a crucial role in machine translation. According to the input format it is mainly separated into three tasks i.e. reference-only source-only and source-reference-combined. Recent methods despite their promising results are specifically designed and optimized on one of them. This limits the convenience of these methods and overlooks the commonalities among tasks. In this paper we propose UniTE which is the first unified framework engaged with abilities to handle all three evaluation tasks. Concretely we propose monotonic regional attention to control the interaction among input segments and unified pretraining to better adapt multi-task learning. We testify our framework on WMT 2019 Metrics and WMT 2020 Quality Estimation benchmarks. Extensive analyses show that our (textit)single model can universally surpass various state-of-the-art or winner methods across tasks. Both source code and associated models are available at https://github.com/NLP2CT/UniTE."

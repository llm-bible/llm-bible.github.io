---
layout: publication
title: 'Nanolm: An Affordable LLM Pre-training Benchmark Via Accurate Loss Prediction Across Scales'
authors: Yao Yiqun, Fan Siqi, Huang Xiusheng, Fang Xuezhi, Li Xiang, Ni Ziyi, Jiang Xin, Meng Xuying, Han Peng, Shang Shuo, Liu Kang, Sun Aixin, Wang Yequan
conference: "Arxiv"
year: 2023
bibkey: yao2023affordable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.06875"}
  - {name: "Code", url: "https://github.com/cofe-ai/Mu-scaling"}
tags: ['Efficiency And Optimization', 'Has Code', 'Large Scale Training', 'Model Architecture', 'Scaling Laws', 'Training Techniques']
---
As language models scale up it becomes increasingly expensive to verify research ideas because conclusions on small models do not trivially transfer to large ones. A possible solution is to establish a generic system that accurately predicts certain metrics for large models without training them. Existing scaling laws require hyperparameter search on the largest models limiting their predicative capability. In this paper we present an approach (namely muScaling) to predict the pre-training loss based on our observations that Maximal Update Parametrization (muP) enables accurate fitting of scaling laws close to common loss basins in hyperparameter space. With muScaling different model designs can be compared on large scales by training only their smaller counterparts. Further we introduce nanoLM an affordable LLM pre-training benchmark that facilitates this new research paradigm. With around 1437; of the one-time pre-training cost we can accurately forecast the loss for models up to 52B. Our goal with nanoLM is to empower researchers with limited resources to reach meaningful conclusions on large models. We also aspire for our benchmark to serve as a bridge between the academic community and the industry. Code for muScaling is available at https://github.com/cofe-ai/Mu-scaling. Code for nanoLLM will be available later.

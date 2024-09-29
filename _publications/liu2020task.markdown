---
layout: publication
title: Task45;level Curriculum Learning For Non45;autoregressive Neural Machine Translation
authors: Liu Jinglin, Ren Yi, Tan Xu, Zhang Chen, Qin Tao, Zhao Zhou, Liu Tie-yan
conference: "Arxiv"
year: 2020
bibkey: liu2020task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2007.08772"}
tags: ['Applications', 'GPT', 'Pretraining Methods', 'Training Techniques']
---
Non45;autoregressive translation (NAT) achieves faster inference speed but at the cost of worse accuracy compared with autoregressive translation (AT). Since AT and NAT can share model structure and AT is an easier task than NAT due to the explicit dependency on previous target45;side tokens a natural idea is to gradually shift the model training from the easier AT task to the harder NAT task. To smooth the shift from AT training to NAT training in this paper we introduce semi45;autoregressive translation (SAT) as intermediate tasks. SAT contains a hyperparameter k and each k value defines a SAT task with different degrees of parallelism. Specially SAT covers AT and NAT as its special cases it reduces to AT when k = 1 and to NAT when k = N (N is the length of target sentence). We design curriculum schedules to gradually shift k from 1 to N with different pacing functions and number of tasks trained at the same time. We called our method as task45;level curriculum learning for NAT (TCL45;NAT). Experiments on IWSLT14 De45;En IWSLT16 En45;De WMT14 En45;De and De45;En datasets show that TCL45;NAT achieves significant accuracy improvements over previous NAT baselines and reduces the performance gap between NAT and AT models to 145;2 BLEU points demonstrating the effectiveness of our proposed method.

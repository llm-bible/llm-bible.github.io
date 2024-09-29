---
layout: publication
title: Bitdistiller Unleashing The Potential Of Sub45;445;bit Llms Via Self45;distillation
authors: Du Dayou, Zhang Yijia, Cao Shijie, Guo Jiaqi, Cao Ting, Chu Xiaowen, Xu Ningyi
conference: "Arxiv"
year: 2024
bibkey: du2024unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10631"}
  - {name: "Code", url: "https://github.com/DD&#45;DuDa/BitDistiller"}
tags: ['Distillation', 'Efficiency And Optimization', 'Has Code', 'Quantization', 'Tools', 'Training Techniques']
---
The upscaling of Large Language Models (LLMs) has yielded impressive advances in natural language processing yet it also poses significant deployment challenges. Weight quantization has emerged as a widely embraced solution to reduce memory and computational demands. This paper introduces BitDistiller a framework that synergizes Quantization45;Aware Training (QAT) with Knowledge Distillation (KD) to boost the performance of LLMs at ultra45;low precisions (sub45;445;bit). Specifically BitDistiller first incorporates a tailored asymmetric quantization and clipping technique to maximally preserve the fidelity of quantized weights and then proposes a novel Confidence45;Aware Kullback45;Leibler Divergence (CAKLD) objective which is employed in a self45;distillation manner to enable faster convergence and superior model performance. Empirical evaluations demonstrate that BitDistiller significantly surpasses existing methods in both 345;bit and 245;bit configurations on general language understanding and complex reasoning benchmarks. Notably BitDistiller is shown to be more cost45;effective demanding fewer data and training resources. The code is available at https://github.com/DD&#45;DuDa/BitDistiller.

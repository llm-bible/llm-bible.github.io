---
layout: publication
title: 'Bitdistiller: Unleashing The Potential Of Sub-4-bit Llms Via Self-distillation'
authors: Du Dayou, Zhang Yijia, Cao Shijie, Guo Jiaqi, Cao Ting, Chu Xiaowen, Xu Ningyi
conference: "Arxiv"
year: 2024
bibkey: du2024unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10631"}
  - {name: "Code", url: "https://github.com/DD-DuDa/BitDistiller"}
tags: ['Distillation', 'Efficiency And Optimization', 'Has Code', 'Quantization', 'Tools', 'Training Techniques']
---
The upscaling of Large Language Models (LLMs) has yielded impressive advances in natural language processing yet it also poses significant deployment challenges. Weight quantization has emerged as a widely embraced solution to reduce memory and computational demands. This paper introduces BitDistiller a framework that synergizes Quantization-Aware Training (QAT) with Knowledge Distillation (KD) to boost the performance of LLMs at ultra-low precisions (sub-4-bit). Specifically BitDistiller first incorporates a tailored asymmetric quantization and clipping technique to maximally preserve the fidelity of quantized weights and then proposes a novel Confidence-Aware Kullback-Leibler Divergence (CAKLD) objective which is employed in a self-distillation manner to enable faster convergence and superior model performance. Empirical evaluations demonstrate that BitDistiller significantly surpasses existing methods in both 3-bit and 2-bit configurations on general language understanding and complex reasoning benchmarks. Notably BitDistiller is shown to be more cost-effective demanding fewer data and training resources. The code is available at https://github.com/DD-DuDa/BitDistiller."

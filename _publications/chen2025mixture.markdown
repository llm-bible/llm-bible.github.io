---
layout: publication
title: 'Mixture Of Decoding: An Attention-inspired Adaptive Decoding Strategy To Mitigate Hallucinations In Large Vision-language Models'
authors: Xinlong Chen, Yuanxing Zhang, Qiang Liu, Junfei Wu, Fuzheng Zhang, Tieniu Tan
conference: "Arxiv"
year: 2025
bibkey: chen2025mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17061"}
  - {name: "Code", url: "https://github.com/xlchen0205/MoD"}
tags: ['Has Code', 'Multimodal Models', 'Model Architecture', 'Attention Mechanism']
---
Large Vision-Language Models (LVLMs) have exhibited impressive capabilities across various visual tasks, yet they remain hindered by the persistent challenge of hallucinations. To address this critical issue, we propose Mixture of Decoding (MoD), a novel approach for hallucination mitigation that dynamically adapts decoding strategies by evaluating the correctness of the model's attention on image tokens. Specifically, MoD measures the consistency between outputs generated from the original image tokens and those derived from the model's attended image tokens, to distinguish the correctness aforementioned. If the outputs are consistent, indicating correct attention, MoD employs a complementary strategy to amplify critical information. Conversely, if the outputs are inconsistent, suggesting erroneous attention, MoD utilizes a contrastive strategy to suppress misleading information. Extensive experiments demonstrate that MoD significantly outperforms existing decoding methods across multiple mainstream benchmarks, effectively mitigating hallucinations in LVLMs. The code is available at https://github.com/xlchen0205/MoD.

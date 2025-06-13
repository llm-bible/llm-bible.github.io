---
layout: publication
title: 'Afroxlmr-comet: Multilingual Knowledge Distillation With Attention Matching For Low-resource Languages'
authors: Joshua Sakthivel Raju, Sanjay S, Jaskaran Singh Walia, Srinivas Raghav, Vukosi Marivate
conference: "Arxiv"
year: 2025
bibkey: raju2025afroxlmr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18020"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Quantization', 'Distillation']
---
Language model compression through knowledge distillation has emerged as a
promising approach for deploying large language models in resource-constrained
environments. However, existing methods often struggle to maintain performance
when distilling multilingual models, especially for low-resource languages. In
this paper, we present a novel hybrid distillation approach that combines
traditional knowledge distillation with a simplified attention matching
mechanism, specifically designed for multilingual contexts. Our method
introduces an extremely compact student model architecture, significantly
smaller than conventional multilingual models. We evaluate our approach on five
African languages: Kinyarwanda, Swahili, Hausa, Igbo, and Yoruba. The distilled
student model; AfroXLMR-Comet successfully captures both the output
distribution and internal attention patterns of a larger teacher model
(AfroXLMR-Large) while reducing the model size by over 85%. Experimental
results demonstrate that our hybrid approach achieves competitive performance
compared to the teacher model, maintaining an accuracy within 85% of the
original model's performance while requiring substantially fewer computational
resources. Our work provides a practical framework for deploying efficient
multilingual models in resource-constrained environments, particularly
benefiting applications involving African languages.

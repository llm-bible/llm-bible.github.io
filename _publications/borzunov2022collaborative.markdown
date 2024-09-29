---
layout: publication
title: Petals Collaborative Inference And Fine45;tuning Of Large Models
authors: Borzunov Alexander, Baranchuk Dmitry, Dettmers Tim, Ryabinin Max, Belkada Younes, Chumachenko Artem, Samygin Pavel, Raffel Colin
conference: "Arxiv"
year: 2022
bibkey: borzunov2022collaborative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.01188"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Tools']
---
Many NLP tasks benefit from using large language models (LLMs) that often have more than 100 billion parameters. With the release of BLOOM45;176B and OPT45;175B everyone can download pretrained models of this scale. Still using these models requires high45;end hardware unavailable to many researchers. In some cases LLMs can be used more affordably via RAM offloading or hosted APIs. However these techniques have innate limitations offloading is too slow for interactive inference while APIs are not flexible enough for research that requires access to weights attention or logits. In this work we propose Petals 45; a system for inference and fine45;tuning of large models collaboratively by joining the resources of multiple parties. We demonstrate that this strategy outperforms offloading for very large models running inference of BLOOM45;176B on consumer GPUs with ≈ 1 step per second which is enough for many interactive LLM applications. Unlike most inference APIs Petals also natively exposes hidden states of served models allowing to train and share custom model extensions based on efficient fine45;tuning methods.

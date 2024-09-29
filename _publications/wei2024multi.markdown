---
layout: publication
title: Promptmm Multi45;modal Knowledge Distillation For Recommendation With Prompt45;tuning
authors: Wei Wei, Tang Jiabin, Jiang Yangqin, Xia Lianghao, Huang Chao
conference: "Arxiv"
year: 2024
bibkey: wei2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17188"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Prompting', 'Quantization', 'Reinforcement Learning', 'Tools']
---
Multimedia online platforms (e.g. Amazon TikTok) have greatly benefited from the incorporation of multimedia (e.g. visual textual and acoustic) content into their personal recommender systems. These modalities provide intuitive semantics that facilitate modality45;aware user preference modeling. However two key challenges in multi45;modal recommenders remain unresolved i) The introduction of multi45;modal encoders with a large number of additional parameters causes overfitting given high45;dimensional multi45;modal features provided by extractors (e.g. ViT BERT). ii) Side information inevitably introduces inaccuracies and redundancies which skew the modality45;interaction dependency from reflecting true user preference. To tackle these problems we propose to simplify and empower recommenders through Multi45;modal Knowledge Distillation (PromptMM) with the prompt45;tuning that enables adaptive quality distillation. Specifically PromptMM conducts model compression through distilling u45;i edge relationship and multi45;modal node content from cumbersome teachers to relieve students from the additional feature reduction parameters. To bridge the semantic gap between multi45;modal context and collaborative signals for empowering the overfitting teacher soft prompt45;tuning is introduced to perform student task45;adaptive. Additionally to adjust the impact of inaccuracies in multimedia data a disentangled multi45;modal list45;wise distillation is developed with modality45;aware re45;weighting mechanism. Experiments on real45;world data demonstrate PromptMMs superiority over existing techniques. Ablation tests confirm the effectiveness of key components. Additional tests show the efficiency and effectiveness.

---
layout: publication
title: F345;pruning A Training45;free And Generalized Pruning Strategy Towards Faster And Finer Text45;to45;video Synthesis
authors: Su Sitong, Liu Jianzhi, Gao Lianli, Song Jingkuan
conference: "Arxiv"
year: 2023
bibkey: su2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.03459"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Training Techniques', 'Transformer']
---
Recently Text45;to45;Video (T2V) synthesis has undergone a breakthrough by training transformers or diffusion models on large45;scale datasets. Nevertheless inferring such large models incurs huge costs.Previous inference acceleration works either require costly retraining or are model45;specific.To address this issue instead of retraining we explore the inference process of two mainstream T2V models using transformers and diffusion models.The exploration reveals the redundancy in temporal attention modules of both models which are commonly utilized to establish temporal relations among frames.Consequently we propose a training45;free and generalized pruning strategy called F345;Pruning to prune redundant temporal attention weights.Specifically when aggregate temporal attention values are ranked below a certain ratio corresponding weights will be pruned.Extensive experiments on three datasets using a classic transformer45;based model CogVideo and a typical diffusion45;based model Tune45;A45;Video verify the effectiveness of F345;Pruning in inference acceleration quality assurance and broad applicability.

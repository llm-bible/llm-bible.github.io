---
layout: publication
title: Compositional Text45;to45;image Synthesis With Attention Map Control Of Diffusion Models
authors: Wang Ruichen, Chen Zekang, Chen Chen, Ma Jian, Lu Haonan, Lin Xiaodong
conference: "Arxiv"
year: 2023
bibkey: wang2023compositional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13921"}
  - {name: "Code", url: "https://github.com/OPPOMente&#45;Lab/attention&#45;mask&#45;control"}
tags: ['Attention Mechanism', 'Has Code', 'Merging', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent text45;to45;image (T2I) diffusion models show outstanding performance in generating high45;quality images conditioned on textual prompts. However they fail to semantically align the generated images with the prompts due to their limited compositional capabilities leading to attribute leakage entity leakage and missing entities. In this paper we propose a novel attention mask control strategy based on predicted object boxes to address these issues. In particular we first train a BoxNet to predict a box for each entity that possesses the attribute specified in the prompt. Then depending on the predicted boxes a unique mask control is applied to the cross45; and self45;attention maps. Our approach produces a more semantically accurate synthesis by constraining the attention regions of each token in the prompt to the image. In addition the proposed method is straightforward and effective and can be readily integrated into existing cross45;attention45;based T2I generators. We compare our approach to competing methods and demonstrate that it can faithfully convey the semantics of the original text to the generated content and achieve high availability as a ready45;to45;use plugin. Please refer to https://github.com/OPPOMente&#45;Lab/attention&#45;mask&#45;control.

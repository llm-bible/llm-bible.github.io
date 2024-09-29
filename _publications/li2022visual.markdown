---
layout: publication
title: VALHALLA\: Visual Hallucination For Machine Translation
authors: Li Yi, Panda Rameswar, Kim Yoon, Chen Chun-fu, Feris Rogerio, Cox David, Vasconcelos Nuno
conference: "Arxiv"
year: 2022
bibkey: li2022visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.00100"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Designing better machine translation systems by considering auxiliary inputs such as images has attracted much attention in recent years. While existing methods show promising performance over the conventional text-only translation systems they typically require paired text and image as input during inference which limits their applicability to real-world scenarios. In this paper we introduce a visual hallucination framework called VALHALLA which requires only source sentences at inference time and instead uses hallucinated visual representations for multimodal machine translation. In particular given a source sentence an autoregressive hallucination transformer is used to predict a discrete visual representation from the input text and the combined text and hallucinated representations are utilized to obtain the target translation. We train the hallucination transformer jointly with the translation transformer using standard backpropagation with cross-entropy losses while being guided by an additional loss that encourages consistency between predictions using either ground-truth or hallucinated visual representations. Extensive experiments on three standard translation datasets with a diverse set of language pairs demonstrate the effectiveness of our approach over both text-only baselines and state-of-the-art methods. Project page http://www.svcl.ucsd.edu/projects/valhalla."

---
layout: publication
title: Compound Tokens Channel Fusion For Vision45;language Representation Learning
authors: Aladago Maxwell Mbabilla, Piergiovanni Aj
conference: "Arxiv"
year: 2022
bibkey: aladago2022compound
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.01447"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Transformer']
---
We present an effective method for fusing visual45;and45;language representations for several question answering tasks including visual question answering and visual entailment. In contrast to prior works that concatenate unimodal representations or use only cross45;attention we compose multimodal representations via channel fusion. By fusing on the channels the model is able to more effectively align the tokens compared to standard methods. These multimodal representations which we call compound tokens are generated with cross45;attention transformer layers. First vision tokens are used as queries to retrieve compatible text tokens through cross45;attention. We then chain the vision tokens and the queried text tokens along the channel dimension. We call the resulting representations compound tokens. A second group of compound tokens are generated using an analogous process where the text tokens serve as queries to the cross45;attention layer. We concatenate all the compound tokens for further processing with multimodal encoder. We demonstrate the effectiveness of compound tokens using an encoder45;decoder vision45;language model trained end45;to45;end in the open45;vocabulary setting. Compound Tokens achieve highly competitive performance across a range of question answering tasks including GQA VQA2.0 and SNLI45;VE.

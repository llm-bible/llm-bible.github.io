---
layout: publication
title: Bridgetower Building Bridges Between Encoders In Vision45;language Representation Learning
authors: Xu Xiao, Wu Chenfei, Rosenman Shachar, Lal Vasudev, Che Wanxiang, Duan Nan
conference: "Arxiv"
year: 2022
bibkey: xu2022building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.08657"}
  - {name: "Code", url: "https://github.com/microsoft/BridgeTower"}
tags: ['Has Code', 'Merging', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Vision45;Language (VL) models with the Two45;Tower architecture have dominated visual45;language representation learning in recent years. Current VL models either use lightweight uni45;modal encoders and learn to extract align and fuse both modalities simultaneously in a deep cross45;modal encoder or feed the last45;layer uni45;modal representations from the deep pre45;trained uni45;modal encoders into the top cross45;modal encoder. Both approaches potentially restrict vision45;language representation learning and limit model performance. In this paper we propose BridgeTower which introduces multiple bridge layers that build a connection between the top layers of uni45;modal encoders and each layer of the cross45;modal encoder. This enables effective bottom45;up cross45;modal alignment and fusion between visual and textual representations of different semantic levels of pre45;trained uni45;modal encoders in the cross45;modal encoder. Pre45;trained with only 4M images BridgeTower achieves state45;of45;the45;art performance on various downstream vision45;language tasks. In particular on the VQAv2 test45;std set BridgeTower achieves an accuracy of 78.7337; outperforming the previous state45;of45;the45;art model METER by 1.0937; with the same pre45;training data and almost negligible additional parameters and computational costs. Notably when further scaling the model BridgeTower achieves an accuracy of 81.1537; surpassing models that are pre45;trained on orders45;of45;magnitude larger datasets. Code and checkpoints are available at https://github.com/microsoft/BridgeTower.

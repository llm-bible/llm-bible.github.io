---
layout: publication
title: "Integrating Translation Memories Into Non-autoregressive Machine Translation"
authors: Xu Jitao, Crego Josep, Yvon François
conference: "Arxiv"
year: 2022
bibkey: xu2022integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.06020"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Non-autoregressive machine translation (NAT) has recently made great progress. However most works to date have focused on standard translation tasks even though some edit-based NAT models such as the Levenshtein Transformer (LevT) seem well suited to translate with a Translation Memory (TM). This is the scenario considered here. We first analyze the vanilla LevT model and explain why it does not do well in this setting. We then propose a new variant TM-LevT and show how to effectively train this model. By modifying the data presentation and introducing an extra deletion operation we obtain performance that are on par with an autoregressive approach while reducing the decoding load. We also show that incorporating TMs during training dispenses to use knowledge distillation a well-known trick used to mitigate the multimodality issue.

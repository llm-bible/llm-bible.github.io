---
layout: publication
title: Hybrid45;regressive Neural Machine Translation
authors: Wang Qiang, Hu Xinhui, Chen Ming
conference: "Arxiv"
year: 2022
bibkey: wang2022hybrid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.10416"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security']
---
In this work we empirically confirm that non45;autoregressive translation with an iterative refinement mechanism (IR45;NAT) suffers from poor acceleration robustness because it is more sensitive to decoding batch size and computing device setting than autoregressive translation (AT). Inspired by it we attempt to investigate how to combine the strengths of autoregressive and non45;autoregressive translation paradigms better. To this end we demonstrate through synthetic experiments that prompting a small number of ATs predictions can promote one45;shot non45;autoregressive translation to achieve the equivalent performance of IR45;NAT. Following this line we propose a new two45;stage translation prototype called hybrid45;regressive translation (HRT). Specifically HRT first generates discontinuous sequences via autoregression (e.g. make a prediction every k tokens k1) and then fills in all previously skipped tokens at once in a non45;autoregressive manner. We also propose a bag of techniques to effectively and efficiently train HRT without adding any model parameters. HRT achieves the state45;of45;the45;art BLEU score of 28.49 on the WMT En45;De task and is at least 1.5x faster than AT regardless of batch size and device. In addition another bonus of HRT is that it successfully inherits the good characteristics of AT in the deep45;encoder45;shallow45;decoder architecture. Concretely compared to the vanilla HRT with a 645;layer encoder and 645;layer decoder the inference speed of HRT with a 1245;layer encoder and 145;layer decoder is further doubled on both GPU and CPU without BLEU loss.

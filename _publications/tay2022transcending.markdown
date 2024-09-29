---
layout: publication
title: Transcending Scaling Laws With 0.137; Extra Compute
authors: Yi Tay, Jason Wei, Hyung Won Chung, Vinh Q. Tran, David R. So, Siamak Shakeri, Xavier Garcia, Huaixiu Steven Zheng, Jinfeng Rao, Aakanksha Chowdhery, Denny Zhou, Donald Metzler, Slav Petrov, Neil Houlsby, Quoc V. Le, Mostafa Dehghani
conference: "Arxiv"
year: 2022
bibkey: tay2022transcending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2210.11399v2"}
tags: ['Applications', 'Efficiency And Optimization', 'Large Scale Training', 'Model Architecture', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques']
---
Scaling language models improves performance but comes with significant computational costs. This paper proposes UL2R a method that substantially improves existing language models and their scaling curves with a relatively tiny amount of extra compute. The key idea is to continue training a state45;of45;the45;art large language model (e.g. PaLM) on a few more steps with UL2s mixture45;of45;denoiser objective. We show that with almost negligible extra computational costs and no new sources of data we are able to substantially improve the scaling properties of large language models on downstream metrics. In this paper we continue training PaLM with UL2R introducing a new set of models at 8B 62B and 540B scale which we call U45;PaLM. Impressively at 540B scale we show an approximately 2x computational savings rate where U45;PaLM achieves the same performance as the final PaLM 540B model at around half its computational budget (i.e. saving sim4.4 million TPUv4 hours). We further show that this improved scaling curve leads to emergent abilities on challenging BIG45;Bench tasks 45;45; for instance U45;PaLM does much better than PaLM on some tasks or demonstrates better quality at much smaller scale (62B as opposed to 540B). Overall we show that U45;PaLM outperforms PaLM on many few45;shot setups i.e. English NLP tasks (e.g. commonsense reasoning question answering) reasoning tasks with chain45;of45;thought (e.g. GSM8K) multilingual tasks (MGSM TydiQA) MMLU and challenging BIG45;Bench tasks. Finally we provide qualitative examples showing the new capabilities of U45;PaLM for single and multi45;span infilling.

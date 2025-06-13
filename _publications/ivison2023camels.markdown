---
layout: publication
title: 'Camels In A Changing Climate: Enhancing LM Adaptation With Tulu 2'
authors: Hamish Ivison, Yizhong Wang, Valentina Pyatkin, Nathan Lambert, Matthew Peters, Pradeep Dasigi, Joel Jang, David Wadden, Noah A. Smith, Iz Beltagy, Hannaneh Hajishirzi
conference: "Arxiv"
year: 2023
bibkey: ivison2023camels
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10702"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT']
---
Since the release of T\"ULU [Wang et al., 2023b], open resources for
instruction tuning have developed quickly, from better base models to new
finetuning techniques. We test and incorporate a number of these advances into
T\"ULU, resulting in T\"ULU 2, a suite of improved T\"ULU models for advancing
the understanding and best practices of adapting pretrained language models to
downstream tasks and user preferences. Concretely, we release: (1)
T\"ULU-V2-mix, an improved collection of high-quality instruction datasets; (2)
T\"ULU 2, LLAMA-2 models finetuned on the V2 mixture; (3) T\"ULU 2+DPO, T\"ULU
2 models trained with direct preference optimization (DPO), including the
largest DPO-trained model to date (T\"ULU 2+DPO 70B); (4) CODE T\"ULU 2, CODE
LLAMA models finetuned on our V2 mix that outperform CODE LLAMA and its
instruction-tuned variant, CODE LLAMA-Instruct. Our evaluation from multiple
perspectives shows that the T\"ULU 2 suite achieves state-of-the-art
performance among open models and matches or exceeds the performance of
GPT-3.5-turbo-0301 on several benchmarks. We release all the checkpoints, data,
training and evaluation code to facilitate future open efforts on adapting
large language models.

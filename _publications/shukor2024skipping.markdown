---
layout: publication
title: 'Skipping Computations In Multimodal Llms'
authors: Mustafa Shukor, Matthieu Cord
conference: "Arxiv"
year: 2024
bibkey: shukor2024skipping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09454"}
  - {name: "Code", url: "https://github.com/mshukor/ima-lmms"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning', 'Transformer', 'Has Code', 'Applications', 'Attention Mechanism']
---
Large Language Models (LLMs) have demonstrated remarkable success in both
textual and multimodal domains. However, this success often comes with
substantial computational costs, particularly when handling lengthy sequences
of multimodal inputs. This has sparked many efforts focusing on enhancing
efficiency during training and inference. In this study, we investigate the
computation redundancy in Multimodal Large Language Models (MLLMs) during
inference. We propose different methods to skip computations, such as skipping
entire blocks, FFN or self-attention (SA) layers. Additionally, we explore
parallelizing certain layers, such as FFN and SA layers. Our findings validate
that (1) significant amount of computations can be avoided at inference time,
especially for tasks such as Visual Question Answering (VQA). (2) Skipping
computations during training can recover 97% of the original performance, even
when skipping half of the blocks or removing 70% of the weights. Alternatively,
(3) properly training with smaller LLMs can yield comparable performance to
LLMs 2 or 3 times larger. To conclude, we extend our investigation to recent
MLLMs, such as LLaVA-1.5, showing similar observations. Our work show that
there is redundant computations inside MLLMs and thus the potential for
significantly improving inference costs without sacrificing performance. The
code is available here: https://github.com/mshukor/ima-lmms.

---
layout: publication
title: 'Is Parameter Collision Hindering Continual Learning In Llms?'
authors: Shuo Yang, Kun-peng Ning, Yu-yang Liu, Jia-yu Yao, Yong-hong Tian, Yi-bing Song, Li Yuan
conference: "Arxiv"
year: 2024
bibkey: yang2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10179"}
tags: ['RAG', 'Fine-Tuning']
---
Large Language Models (LLMs) often suffer from catastrophic forgetting when
learning multiple tasks sequentially, making continual learning (CL) essential
for their dynamic deployment. Existing state-of-the-art (SOTA) methods, such as
O-LoRA, typically focus on constructing orthogonality tasks to decouple
parameter interdependence from various domains.In this paper, we reveal that
building non-collision parameters is a more critical factor in addressing CL
challenges. Our theoretical and experimental analyses demonstrate that
non-collision parameters can provide better task orthogonality, which is a
sufficient but unnecessary condition. Furthermore, knowledge from multiple
domains will be preserved in non-collision parameter subspaces, making it more
difficult to forget previously seen data. Leveraging this insight, we propose
Non-collision Low-Rank Adaptation (N-LoRA), a simple yet effective approach
leveraging low collision rates to enhance CL in LLMs. Experimental results on
multiple CL benchmarks indicate that N-LoRA achieves superior performance
(+2.9), higher task orthogonality (*4.1 times), and lower parameter collision
(*58.1 times) than SOTA methods.

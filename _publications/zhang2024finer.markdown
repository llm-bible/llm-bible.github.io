---
layout: publication
title: Finercut Finer45;grained Interpretable Layer Pruning For Large Language Models
authors: Zhang Yang, Li Yawei, Wang Xinpeng, Shen Qianli, Plank Barbara, Bischl Bernd, Rezaei Mina, Kawaguchi Kenji
conference: "Arxiv"
year: 2024
bibkey: zhang2024finer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18218"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Transformer']
---
Overparametrized transformer networks are the state45;of45;the45;art architecture for Large Language Models (LLMs). However such models contain billions of parameters making large compute a necessity while raising environmental concerns. To address these issues we propose FinerCut a new form of fine45;grained layer pruning which in contrast to prior work at the transformer block level considers all self45;attention and feed45;forward network (FFN) layers within blocks as individual pruning candidates. FinerCut prunes layers whose removal causes minimal alternation to the models output 45;45; contributing to a new lean interpretable and task45;agnostic pruning method. Tested across 9 benchmarks our approach retains 9037; performance of Llama345;8B with 2537; layers removed and 9537; performance of Llama345;70B with 3037; layers removed all without fine45;tuning or post45;pruning reconstruction. Strikingly we observe intriguing results with FinerCut 4237; (34 out of 80) of the self45;attention layers in Llama345;70B can be removed while preserving 9937; of its performance 45;45; without additional fine45;tuning after removal. Moreover FinerCut provides a tool to inspect the types and locations of pruned layers allowing to observe interesting pruning behaviors. For instance we observe a preference for pruning self45;attention layers often at deeper consecutive decoder layers. We hope our insights inspire future efficient LLM architecture designs.

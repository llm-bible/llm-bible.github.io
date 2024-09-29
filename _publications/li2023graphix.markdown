---
layout: publication
title: Graphix45;t5 Mixing Pre45;trained Transformers With Graph45;aware Layers For Text45;to45;sql Parsing
authors: Li Jinyang, Hui Binyuan, Cheng Reynold, Qin Bowen, Ma Chenhao, Huo Nan, Huang Fei, Du Wenyu, Si Luo, Li Yongbin
conference: "Arxiv"
year: 2023
bibkey: li2023graphix
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.07507"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
The task of text45;to45;SQL parsing which aims at converting natural language questions into executable SQL queries has garnered increasing attention in recent years as it can assist end users in efficiently extracting vital information from databases without the need for technical background. One of the major challenges in text45;to45;SQL parsing is domain generalization i.e. how to generalize well to unseen databases. Recently the pre45;trained text45;to45;text transformer model namely T5 though not specialized for text45;to45;SQL parsing has achieved state45;of45;the45;art performance on standard benchmarks targeting domain generalization. In this work we explore ways to further augment the pre45;trained T5 model with specialized components for text45;to45;SQL parsing. Such components are expected to introduce structural inductive bias into text45;to45;SQL parsers thus improving models capacity on (potentially multi45;hop) reasoning which is critical for generating structure45;rich SQLs. To this end we propose a new architecture GRAPHIX45;T5 a mixed model with the standard pre45;trained transformer model augmented by some specially45;designed graph45;aware layers. Extensive experiments and analysis demonstrate the effectiveness of GRAPHIX45;T5 across four text45;to45;SQL benchmarks SPIDER SYN REALISTIC and DK. GRAPHIX45;T5 surpass all other T545;based parsers with a significant margin achieving new state45;of45;the45;art performance. Notably GRAPHIX45;T545;large reach performance superior to the original T545;large by 5.737; on exact match (EM) accuracy and 6.637; on execution accuracy (EX). This even outperforms the T545;3B by 1.237; on EM and 1.537; on EX.

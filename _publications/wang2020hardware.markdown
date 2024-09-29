---
layout: publication
title: HAT Hardware45;aware Transformers For Efficient Natural Language Processing
authors: Wang Hanrui, Wu Zhanghao, Liu Zhijian, Cai Han, Zhu Ligeng, Gan Chuang, Han Song
conference: "Arxiv"
year: 2020
bibkey: wang2020hardware
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.14187"}
  - {name: "Code", url: "https://github.com/mit&#45;han&#45;lab/hardware&#45;aware&#45;transformers.git"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Transformers are ubiquitous in Natural Language Processing (NLP) tasks but they are difficult to be deployed on hardware due to the intensive computation. To enable low45;latency inference on resource45;constrained hardware platforms we propose to design Hardware45;Aware Transformers (HAT) with neural architecture search. We first construct a large design space with textit123;arbitrary encoder45;decoder attention125; and textit123;heterogeneous layers125;. Then we train a textit123;SuperTransformer125; that covers all candidates in the design space and efficiently produces many textit123;SubTransformers125; with weight sharing. Finally we perform an evolutionary search with a hardware latency constraint to find a specialized textit123;SubTransformer125; dedicated to run fast on the target hardware. Extensive experiments on four machine translation tasks demonstrate that HAT can discover efficient models for different hardware (CPU GPU IoT device). When running WMT14 translation task on Raspberry Pi45;4 HAT can achieve textbf123;3125;× speedup textbf123;3.7125;× smaller size over baseline Transformer; textbf123;2.7125;× speedup textbf123;3.6125;× smaller size over Evolved Transformer with textbf123;12041125;× less search cost and no performance loss. HAT code is https://github.com/mit&#45;han&#45;lab/hardware&#45;aware&#45;transformers.git

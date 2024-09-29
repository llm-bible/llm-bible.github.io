---
layout: publication
title: Coca Fusing Position Embedding With Collinear Constrained Attention In Transformers For Long Context Window Extending
authors: Zhu Shiyi, Ye Jing, Jiang Wei, Xue Siqiao, Zhang Qi, Wu Yifan, Li Jianguo
conference: "Arxiv"
year: 2023
bibkey: zhu2023fusing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08646"}
  - {name: "Code", url: "https://github.com/codefuse&#45;ai/Collinear&#45;Constrained&#45;Attention"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Self45;attention and position embedding are two key modules in transformer45;based Large Language Models (LLMs). However the potential relationship between them is far from well studied especially for long context window extending. In fact anomalous behaviors harming long context extrapolation exist between Rotary Position Embedding (RoPE) and vanilla self45;attention unveiled by our work. To address this issue we propose a novel attention mechanism CoCA (Collinear Constrained Attention). Specifically we enforce a collinear constraint between Q and K to seamlessly integrate RoPE and self45;attention. While only adding minimal computational and spatial complexity this integration significantly enhances long context window extrapolation ability. We provide an optimized implementation making it a drop45;in replacement for any existing transformer45;based models. Extensive experiments show that CoCA performs extraordinarily well in extending context windows. A CoCA45;based GPT model trained with a context length of 512 can seamlessly extend the context window up to 32K (60×) without any fine45;tuning. Additionally by dropping CoCA in LLaMA45;7B we achieve extrapolation up to 32K within only 2K training length. Our code is publicly available at https://github.com/codefuse&#45;ai/Collinear&#45;Constrained&#45;Attention

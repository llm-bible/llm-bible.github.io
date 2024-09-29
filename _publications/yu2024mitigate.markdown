---
layout: publication
title: Mitigate Position Bias In Large Language Models Via Scaling A Single Dimension
authors: Yu Yijiong, Jiang Huiqiang, Luo Xufang, Wu Qianhui, Lin Chin-yew, Li Dongsheng, Yang Yuqing, Huang Yongfeng, Qiu Lili
conference: "Arxiv"
year: 2024
bibkey: yu2024mitigate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02536"}
  - {name: "Code", url: "https://aka.ms/PositionalHidden"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) are increasingly applied in various real45;world scenarios due to their excellent generalization capabilities and robust generative abilities. However they exhibit position bias also known as lost in the middle a phenomenon that is especially pronounced in long45;context scenarios which indicates the placement of the key information in different positions of a prompt can significantly affect accuracy. This paper first explores the micro45;level manifestations of position bias concluding that attention weights are a micro45;level expression of position bias. It further identifies that in addition to position embeddings causal attention mask also contributes to position bias by creating position45;specific hidden states. Based on these insights we propose a method to mitigate position bias by scaling this positional hidden states. Experiments on the NaturalQuestions Multi45;document QA KV retrieval LongBench and timeline reorder tasks using various models including RoPE models context windowextended models and Alibi models demonstrate the effectiveness and generalizability of our approach. Our method can improve performance by up to 15.237; by modifying just one dimension of hidden states. Our code is available at https://aka.ms/PositionalHidden.

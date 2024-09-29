---
layout: publication
title: H95;2O Heavy45;hitter Oracle For Efficient Generative Inference Of Large Language Models
authors: Zhang Zhenyu, Sheng Ying, Zhou Tianyi, Chen Tianlong, Zheng Lianmin, Cai Ruisi, Song Zhao, Tian Yuandong, Ré Christopher, Barrett Clark, Wang Zhangyang, Chen Beidi
conference: "Arxiv"
year: 2023
bibkey: zhang2023heavy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.14048"}
  - {name: "Code", url: "https://github.com/FMInference/H2O"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) despite their recent impressive accomplishments are notably cost45;prohibitive to deploy particularly for applications involving long45;content generation such as dialogue systems and story writing. Often a large amount of transient state information referred to as the KV cache is stored in GPU memory in addition to model parameters scaling linearly with the sequence length and batch size. In this paper we introduce a novel approach for implementing the KV cache which significantly reduces its memory footprint. Our approach is based on the noteworthy observation that a small portion of tokens contributes most of the value when computing attention scores. We call these tokens Heavy Hitters (H95;2). Through a comprehensive investigation we find that (i) the emergence of H95;2 is natural and strongly correlates with the frequent co45;occurrence of tokens in the text and (ii) removing them results in significant performance degradation. Based on these insights we propose Heavy Hitter Oracle (H95;2O) a KV cache eviction policy that dynamically retains a balance of recent and H95;2 tokens. We formulate the KV cache eviction as a dynamic submodular problem and prove (under mild assumptions) a theoretical guarantee for our novel eviction algorithm which could help guide future work. We validate the accuracy of our algorithm with OPT LLaMA and GPT45;NeoX across a wide range of tasks. Our implementation of H95;2O with 2037; heavy hitters improves the throughput over three leading inference systems DeepSpeed Zero45;Inference Hugging Face Accelerate and FlexGen by up to 29× 29× and 3× on OPT45;6.7B and OPT45;30B. With the same batch size H2O can reduce the latency by up to 1.9×. The code is available at https://github.com/FMInference/H2O.

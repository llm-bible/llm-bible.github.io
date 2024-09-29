---
layout: publication
title: Found In The Middle How Language Models Use Long Contexts Better Via Plug45;and45;play Positional Encoding
authors: Zhang Zhenyu, Chen Runjin, Liu Shiwei, Yao Zhewei, Ruwase Olatunji, Chen Beidi, Wu Xiaoxia, Wang Zhangyang
conference: "Arxiv"
year: 2024
bibkey: zhang2024found
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04797"}
  - {name: "Code", url: "https://github.com/VITA&#45;Group/Ms&#45;PoE"}
tags: ['Attention Mechanism', 'Has Code', 'Language Modeling', 'Merging', 'Model Architecture', 'RAG', 'Training Techniques']
---
This paper aims to overcome the lost45;in45;the45;middle challenge of large language models (LLMs). While recent advancements have successfully enabled LLMs to perform stable language modeling with up to 4 million tokens the persistent difficulty faced by most LLMs in identifying relevant information situated in the middle of the context has not been adequately tackled. To address this problem this paper introduces Multi45;scale Positional Encoding (Ms45;PoE) which is a simple yet effective plug45;and45;play approach to enhance the capacity of LLMs to handle the relevant information located in the middle of the context without fine45;tuning or introducing any additional overhead. Ms45;PoE leverages the position indice rescaling to relieve the long45;term decay effect introduced by RoPE while meticulously assigning distinct scaling ratios to different attention heads to preserve essential knowledge learned during the pre45;training step forming a multi45;scale context fusion from short to long distance. Extensive experiments with a wide range of LLMs demonstrate the efficacy of our approach. Notably Ms45;PoE achieves an average accuracy gain of up to 3.8 on the Zero45;SCROLLS benchmark over the original LLMs. Code are available at https://github.com/VITA&#45;Group/Ms&#45;PoE.

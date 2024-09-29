---
layout: publication
title: Found In The Middle How Language Models Use Long Contexts Better Via Plug-and-play Positional Encoding
authors: Zhang Zhenyu, Chen Runjin, Liu Shiwei, Yao Zhewei, Ruwase Olatunji, Chen Beidi, Wu Xiaoxia, Wang Zhangyang
conference: "Arxiv"
year: 2024
bibkey: zhang2024found
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04797"}
  - {name: "Code", url: "https://github.com/VITA-Group/Ms-PoE"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Has Code', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
This paper aims to overcome the lost-in-the-middle challenge of large language models (LLMs). While recent advancements have successfully enabled LLMs to perform stable language modeling with up to 4 million tokens the persistent difficulty faced by most LLMs in identifying relevant information situated in the middle of the context has not been adequately tackled. To address this problem this paper introduces Multi-scale Positional Encoding (Ms-PoE) which is a simple yet effective plug-and-play approach to enhance the capacity of LLMs to handle the relevant information located in the middle of the context without fine-tuning or introducing any additional overhead. Ms-PoE leverages the position indice rescaling to relieve the long-term decay effect introduced by RoPE while meticulously assigning distinct scaling ratios to different attention heads to preserve essential knowledge learned during the pre-training step forming a multi-scale context fusion from short to long distance. Extensive experiments with a wide range of LLMs demonstrate the efficacy of our approach. Notably Ms-PoE achieves an average accuracy gain of up to 3.8 on the Zero-SCROLLS benchmark over the original LLMs. Code are available at https://github.com/VITA-Group/Ms-PoE.

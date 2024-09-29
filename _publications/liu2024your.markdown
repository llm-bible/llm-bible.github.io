---
layout: publication
title: Bitdelta Your Fine45;tune May Only Be Worth One Bit
authors: Liu James, Xiao Guangxuan, Li Kai, Lee Jason D., Han Song, Dao Tri, Cai Tianle
conference: "Arxiv"
year: 2024
bibkey: liu2024your
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10193"}
tags: ['Applications', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) are typically trained in two phases pre45;training on large internet45;scale datasets and fine45;tuning for downstream tasks. Given the higher computational demand of pre45;training its intuitive to assume that fine45;tuning adds less new information to the model and is thus more compressible. We explore this assumption by decomposing the weights of fine45;tuned models into their pre45;trained components and an additional delta. We introduce a simple method BitDelta which successfully quantizes this delta down to 1 bit without compromising performance. This interesting finding not only highlights the potential redundancy of information added during fine45;tuning but also has significant implications for the multi45;tenant serving and multi45;tenant storage of fine45;tuned models. By enabling the use of a single high45;precision base model accompanied by multiple 145;bit deltas BitDelta dramatically reduces GPU memory requirements by more than 10x which can also be translated to enhanced generation latency in multi45;tenant settings. We validate BitDelta through experiments across Llama45;2 and Mistral model families and on models up to 70B parameters showcasing minimal performance degradation over all tested settings.

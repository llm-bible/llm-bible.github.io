---
layout: publication
title: Instructed Language Models With Retrievers Are Powerful Entity Linkers
authors: Xiao Zilin, Gong Ming, Wu Jie, Zhang Xingyao, Shou Linjun, Pei Jian, Jiang Daxin
conference: "Arxiv"
year: 2023
bibkey: xiao2023instructed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.03250"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Generative approaches powered by large language models (LLMs) have demonstrated emergent abilities in tasks that require complex reasoning abilities. Yet the generative nature still makes the generated content suffer from hallucinations thus unsuitable for entity45;centric tasks like entity linking (EL) requiring precise entity predictions over a large knowledge base. We present Instructed Generative Entity Linker (INSGENEL) the first approach that enables casual language models to perform entity linking over knowledge bases. Several methods to equip language models with EL capability were proposed in this work including (i) a sequence45;to45;sequence training EL objective with instruction45;tuning (ii) a novel generative EL framework based on a light45;weight potential mention retriever that frees the model from heavy and non45;parallelizable decoding achieving 4× speedup without compromise on linking metrics. INSGENEL outperforms previous generative alternatives with +6.8 F1 points gain on average also with a huge advantage in training data efficiency and training compute consumption. In addition our skillfully engineered in45;context learning (ICL) framework for EL still lags behind INSGENEL significantly reaffirming that the EL task remains a persistent hurdle for general LLMs.

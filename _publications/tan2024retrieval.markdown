---
layout: publication
title: "Retrieval Meets Reasoning: Even High-school Textbook Knowledge Benefits Multimodal Reasoning"
authors: Tan Cheng, Wei Jingxuan, Sun Linzhuang, Gao Zhangyang, Li Siyuan, Yu Bihui, Guo Ruifeng, Li Stan Z.
conference: "Arxiv"
year: 2024
bibkey: tan2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20834"}
tags: ['Multimodal Models', 'RAG', 'Tools', 'Training Techniques']
---
Large language models equipped with retrieval-augmented generation (RAG) represent a burgeoning field aimed at enhancing answering capabilities by leveraging external knowledge bases. Although the application of RAG with language-only models has been extensively explored its adaptation into multimodal vision-language models remains nascent. Going beyond mere answer generation the primary goal of multimodal RAG is to cultivate the models ability to reason in response to relevant queries. To this end we introduce a novel multimodal RAG framework named RMR (Retrieval Meets Reasoning). The RMR framework employs a bi-modal retrieval module to identify the most relevant question-answer pairs which then serve as scaffolds for the multimodal reasoning process. This training-free approach not only encourages the model to engage deeply with the reasoning processes inherent in the retrieved content but also facilitates the generation of answers that are precise and richly interpretable. Surprisingly utilizing solely the ScienceQA dataset collected from elementary and high school science curricula RMR significantly boosts the performance of various vision-language models across a spectrum of benchmark datasets including A-OKVQA MMBench and SEED. These outcomes highlight the substantial potential of our multimodal retrieval and reasoning mechanism to improve the reasoning capabilities of vision-language models.

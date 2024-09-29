---
layout: publication
title: 'Bailong: Bilingual Transfer Learning Based On Qlora And Zip-tie Embedding'
authors: Chen Lung-chuan, Li Zong-ru
conference: "Arxiv"
year: 2024
bibkey: chen2024bilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00862"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large language models (LLMs) have demonstrated exceptional performance in various NLP applications. However the majority of existing open-source LLMs are pre-trained primarily on English data and little part of other languages. This deficiency in multilingual training data results in suboptimal performance when applied to languages with fewer available resources. Furthermore enhancing the performance of LLMs on low-resource languages by full-parameter fine-tuning with additional data requires substantial computational resources posing computational barriers for research organizations and individual researchers. Consequently several techniques such as parameter-efficient tuning and advanced embedding initialization have been proposed to address these challenges. In this work we combine them to facilitate cross-lingual transfer on English-dominated open-source LLM. To effectively enhance the models proficiency in Traditional Chinese we conduct secondary pre-training on Llama 2 7B with Traditional Chinese data by leveraging QLoRA and our proposed zip-tie embedding initialization. The resulting model called Bailong which stands for Bilingual trAnsfer learnIng based on qLOra and zip-tie embeddiNG. We present Bailong-instruct 7B a fine-tuned version of Bailong 7B optimized for multi-turn dialogue scenarios. Recognizing the inadequacy of benchmark datasets in Traditional Chinese we further introduce Bailong-bench to assess the alignment of models with human preferences and the capability to follow instructions in both Traditional Chinese and English tasks. In our evaluation Bailong-instruct 7B exhibits competitive performance on Bailong-bench and other benchmark datasets when compared to other open-source models of similar or even larger parameter sizes. Bailong-instruct 7B and Bailong-bench are publicly available with the aim of empowering the community to build upon our efforts.

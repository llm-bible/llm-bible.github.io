---
layout: publication
title: Bailong Bilingual Transfer Learning Based On Qlora And Zip45;tie Embedding
authors: Chen Lung-chuan, Li Zong-ru
conference: "Arxiv"
year: 2024
bibkey: chen2024bilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00862"}
tags: ['Applications', 'Fine Tuning', 'RAG', 'Training Techniques']
---
Large language models (LLMs) have demonstrated exceptional performance in various NLP applications. However the majority of existing open45;source LLMs are pre45;trained primarily on English data and little part of other languages. This deficiency in multilingual training data results in suboptimal performance when applied to languages with fewer available resources. Furthermore enhancing the performance of LLMs on low45;resource languages by full45;parameter fine45;tuning with additional data requires substantial computational resources posing computational barriers for research organizations and individual researchers. Consequently several techniques such as parameter45;efficient tuning and advanced embedding initialization have been proposed to address these challenges. In this work we combine them to facilitate cross45;lingual transfer on English45;dominated open45;source LLM. To effectively enhance the models proficiency in Traditional Chinese we conduct secondary pre45;training on Llama 2 7B with Traditional Chinese data by leveraging QLoRA and our proposed zip45;tie embedding initialization. The resulting model called Bailong which stands for Bilingual trAnsfer learnIng based on qLOra and zip45;tie embeddiNG. We present Bailong45;instruct 7B a fine45;tuned version of Bailong 7B optimized for multi45;turn dialogue scenarios. Recognizing the inadequacy of benchmark datasets in Traditional Chinese we further introduce Bailong45;bench to assess the alignment of models with human preferences and the capability to follow instructions in both Traditional Chinese and English tasks. In our evaluation Bailong45;instruct 7B exhibits competitive performance on Bailong45;bench and other benchmark datasets when compared to other open45;source models of similar or even larger parameter sizes. Bailong45;instruct 7B and Bailong45;bench are publicly available with the aim of empowering the community to build upon our efforts.

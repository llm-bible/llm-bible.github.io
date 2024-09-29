---
layout: publication
title: Separate The Wheat From The Chaff: Model Deficiency Unlearning Via Parameter-efficient Module Operation
authors: Hu Xinshuo, Li Dongfang, Hu Baotian, Zheng Zihao, Liu Zhenyu, Zhang Min
conference: "Arxiv"
year: 2023
bibkey: hu2023separate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.08090"}
tags: ['Applications', 'Language Modeling', 'Pretraining Methods', 'RAG']
---
Large language models (LLMs) have been widely used in various applications but are known to suffer from issues related to untruthfulness and toxicity. While parameter-efficient modules (PEMs) have demonstrated their effectiveness in equipping models with new skills leveraging PEMs for deficiency unlearning remains underexplored. In this work we propose a PEMs operation approach namely Extraction-before-Subtraction (Ext-Sub) to enhance the truthfulness and detoxification of LLMs through the integration of expert PEM and anti-expert PEM. Remarkably even anti-expert PEM possess valuable capabilities due to their proficiency in generating fabricated content which necessitates language modeling and logical narrative competence. Rather than merely negating the parameters our approach involves extracting and eliminating solely the deficiency capability within anti-expert PEM while preserving the general capabilities. To evaluate the effectiveness of our approach in terms of truthfulness and detoxification we conduct extensive experiments on LLMs encompassing additional abilities such as language modeling and mathematical reasoning. Our empirical results demonstrate that our approach effectively improves truthfulness and detoxification while largely preserving the fundamental abilities of LLMs.

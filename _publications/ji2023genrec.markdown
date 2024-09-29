---
layout: publication
title: Genrec Large Language Model For Generative Recommendation
authors: Ji Jianchao, Li Zelong, Xu Shuyuan, Hua Wenyue, Ge Yingqiang, Tan Juntao, Zhang Yongfeng
conference: "Arxiv"
year: 2023
bibkey: ji2023genrec
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.00457"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools']
---
In recent years large language models (LLM) have emerged as powerful tools for diverse natural language processing tasks. However their potential for recommender systems under the generative recommendation paradigm remains relatively unexplored. This paper presents an innovative approach to recommendation systems using large language models (LLMs) based on text data. In this paper we present a novel LLM for generative recommendation (GenRec) that utilized the expressive power of LLM to directly generate the target item to recommend rather than calculating ranking score for each candidate item one by one as in traditional discriminative recommendation. GenRec uses LLMs understanding ability to interpret context learn user preferences and generate relevant recommendation. Our proposed approach leverages the vast knowledge encoded in large language models to accomplish recommendation tasks. We first we formulate specialized prompts to enhance the ability of LLM to comprehend recommendation tasks. Subsequently we use these prompts to fine-tune the LLaMA backbone LLM on a dataset of user-item interactions represented by textual data to capture user preferences and item characteristics. Our research underscores the potential of LLM-based generative recommendation in revolutionizing the domain of recommendation systems and offers a foundational framework for future explorations in this field. We conduct extensive experiments on benchmark datasets and the experiments shows that our GenRec has significant better results on large dataset.

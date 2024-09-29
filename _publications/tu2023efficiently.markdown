---
layout: publication
title: Efficiently Aligned Cross45;lingual Transfer Learning For Conversational Tasks Using Prompt45;tuning
authors: Tu Lifu, Qu Jin, Yavuz Semih, Joty Shafiq, Liu Wenhao, Xiong Caiming, Zhou Yingbo
conference: "Arxiv"
year: 2023
bibkey: tu2023efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01295"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Cross45;lingual transfer of language models trained on high45;resource languages like English has been widely studied for many NLP tasks but focus on conversational tasks has been rather limited. This is partly due to the high cost of obtaining non45;English conversational data which results in limited coverage. In this work we introduce XSGD for cross45;lingual alignment pretraining a parallel and large45;scale multilingual conversation dataset that we created by translating the English45;only Schema45;Guided Dialogue (SGD) dataset (Rastogi et al. 2020) into 105 other languages. XSGD contains approximately 330k utterances per language. To facilitate aligned cross45;lingual representations we develop an efficient prompt45;tuning45;based method for learning alignment prompts. We also investigate two different classifiers NLI45;based and vanilla classifiers and test cross45;lingual capability enabled by the aligned prompts. We evaluate our models cross45;lingual generalization capabilities on two conversation tasks slot45;filling and intent classification. Our results demonstrate the strong and efficient modeling ability of NLI45;based classifiers and the large cross45;lingual transfer improvements achieved by our aligned prompts particularly in few45;shot settings. In addition we highlight the nice results of our approach compared to LLMs such as text45;davinci45;003 and ChatGPT in both zero45;shot and few45;shot settings. While LLMs exhibit impressive performance in English their cross45;lingual capabilities in other languages particularly low45;resource languages are limited.

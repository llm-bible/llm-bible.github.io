---
layout: publication
title: Evaluation Of Chatgpt Family Of Models For Biomedical Reasoning And Classification
authors: Chen Shan, Li Yingya, Lu Sheng, Van Hoang, Aerts Hugo Jwl, Savova Guergana K., Bitterman Danielle S.
conference: "Arxiv"
year: 2023
bibkey: chen2023evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.02496"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Prompting', 'Tools']
---
Recent advances in large language models (LLMs) have shown impressive ability in biomedical question45;answering but have not been adequately investigated for more specific biomedical applications. This study investigates the performance of LLMs such as the ChatGPT family of models (GPT45;3.5s GPT45;4) in biomedical tasks beyond question45;answering. Because no patient data can be passed to the OpenAI API public interface we evaluated model performance with over 10000 samples as proxies for two fundamental tasks in the clinical domain 45; classification and reasoning. The first task is classifying whether statements of clinical and policy recommendations in scientific literature constitute health advice. The second task is causal relation detection from the biomedical literature. We compared LLMs with simpler models such as bag45;of45;words (BoW) with logistic regression and fine45;tuned BioBERT models. Despite the excitement around viral ChatGPT we found that fine45;tuning for two fundamental NLP tasks remained the best strategy. The simple BoW model performed on par with the most complex LLM prompting. Prompt engineering required significant investment.

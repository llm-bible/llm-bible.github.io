---
layout: publication
title: Cram Credibility45;aware Attention Modification In Llms For Combating Misinformation In RAG
authors: Deng Boyi, Wang Wenjie, Zhu Fengbin, Wang Qifan, Feng Fuli
conference: "Arxiv"
year: 2024
bibkey: deng2024credibility
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11497"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG']
---
Retrieval45;Augmented Generation (RAG) can alleviate hallucinations of Large Language Models (LLMs) by referencing external documents. However the misinformation in external documents may mislead LLMs generation. To address this issue we explore the task of credibility45;aware RAG in which LLMs automatically adjust the influence of retrieved documents based on their credibility scores to counteract misinformation. To this end we introduce a plug45;and45;play method named textbf123;Cr125;edibility45;aware textbf123;A125;ttention textbf123;M125;odification (CrAM). CrAM identifies influential attention heads in LLMs and adjusts their attention weights based on the credibility of the documents thereby reducing the impact of low45;credibility documents. Experiments on Natual Questions and TriviaQA using Llama245;13B Llama345;8B and Qwen45;7B show that CrAM improves the RAG performance of LLMs against misinformation pollution by over 2037; even surpassing supervised fine45;tuning methods.

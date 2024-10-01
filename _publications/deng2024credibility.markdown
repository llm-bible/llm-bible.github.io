---
layout: publication
title: 'Cram: Credibility-aware Attention Modification In Llms For Combating Misinformation In RAG'
authors: Deng Boyi, Wang Wenjie, Zhu Fengbin, Wang Qifan, Feng Fuli
conference: "Arxiv"
year: 2024
bibkey: deng2024credibility
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11497"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
"Retrieval-Augmented Generation (RAG) can alleviate hallucinations of Large Language Models (LLMs) by referencing external documents. However, the misinformation in external documents may mislead LLMs' generation. To address this issue, we explore the task of credibility-aware RAG, in which LLMs automatically adjust the influence of retrieved documents based on their credibility scores to counteract misinformation. To this end, we introduce a plug-and-play method named \(\textbf{Cr}\)edibility-aware \(\textbf{A}\)ttention \(\textbf{M}\)odification (CrAM). CrAM identifies influential attention heads in LLMs and adjusts their attention weights based on the credibility of the documents, thereby reducing the impact of low-credibility documents. Experiments on Natual Questions and TriviaQA using Llama2-13B, Llama3-8B, and Qwen-7B show that CrAM improves the RAG performance of LLMs against misinformation pollution by over 20&#37;, even surpassing supervised fine-tuning methods."

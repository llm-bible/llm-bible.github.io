---
layout: publication
title: 'Promptrefine: Enhancing Few-shot Performance On Low-resource Indic Languages With Example Selection From Related Example Banks'
authors: Soumya Suvra Ghosal, Soumyabrata Pal, Koyel Mukherjee, Dinesh Manocha
conference: "Arxiv"
year: 2024
bibkey: ghosal2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05710"}
tags: ['Few-Shot', 'Tools', 'Language Modeling', 'RAG', 'Ethics and Bias', 'Prompting', 'Applications', 'In-Context Learning']
---
Large Language Models (LLMs) have recently demonstrated impressive few-shot learning capabilities through in-context learning (ICL). However, ICL performance is highly dependent on the choice of few-shot demonstrations, making the selection of the most optimal examples a persistent research challenge. This issue is further amplified in low-resource Indic languages, where the scarcity of ground-truth data complicates the selection process. In this work, we propose PromptRefine, a novel Alternating Minimization approach for example selection that improves ICL performance on low-resource Indic languages. PromptRefine leverages auxiliary example banks from related high-resource Indic languages and employs multi-task learning techniques to align language-specific retrievers, enabling effective cross-language retrieval. Additionally, we incorporate diversity in the selected examples to enhance generalization and reduce bias. Through comprehensive evaluations on four text generation tasks -- Cross-Lingual Question Answering, Multilingual Question Answering, Machine Translation, and Cross-Lingual Summarization using state-of-the-art LLMs such as LLAMA-3.1-8B, LLAMA-2-7B, Qwen-2-7B, and Qwen-2.5-7B, we demonstrate that PromptRefine significantly outperforms existing frameworks for retrieving examples.

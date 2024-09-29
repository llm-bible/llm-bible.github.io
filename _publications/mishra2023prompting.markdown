---
layout: publication
title: Prompting With Pseudo45;code Instructions
authors: Mishra Mayank, Kumar Prince, Bhat Riyaz, Murthy Rudra V, Contractor Danish, Tamilselvam Srikanth
conference: "Arxiv"
year: 2023
bibkey: mishra2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11790"}
tags: ['Pretraining Methods', 'Prompting', 'RAG']
---
Prompting with natural language instructions has recently emerged as a popular method of harnessing the capabilities of large language models. Given the inherent ambiguity present in natural language it is intuitive to consider the possible advantages of prompting with less ambiguous prompt styles such as the use of pseudo45;code. In this paper we explore if prompting via pseudo45;code instructions helps improve the performance of pre45;trained language models. We manually create a dataset of pseudo45;code prompts for 132 different tasks spanning classification QA and generative language tasks sourced from the Super45;NaturalInstructions dataset. Using these prompts along with their counterparts in natural language we study their performance on two LLM families 45; BLOOM and CodeGen. Our experiments show that using pseudo45;code instructions leads to better results with an average increase (absolute) of 745;16 points in F1 scores for classification tasks and an improvement (relative) of 1245;3837; in aggregate ROUGE45;L scores across all tasks. We include detailed ablation studies which indicate that code comments docstrings and the structural clues encoded in pseudo45;code all contribute towards the improvement in performance. To the best of our knowledge our work is the first to demonstrate how pseudo45;code prompts can be helpful in improving the performance of pre45;trained LMs.

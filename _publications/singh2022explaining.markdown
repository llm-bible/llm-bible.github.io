---
layout: publication
title: Explaining Patterns In Data With Language Models Via Interpretable Autoprompting
authors: Singh Chandan, Morris John X., Aneja Jyoti, Rush Alexander M., Gao Jianfeng
conference: "Arxiv"
year: 2022
bibkey: singh2022explaining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.01848"}
tags: ['Applications', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have displayed an impressive ability to harness natural language to perform complex tasks. In this work we explore whether we can leverage this learned ability to find and explain patterns in data. Specifically given a pre45;trained LLM and data examples we introduce interpretable autoprompting (iPrompt) an algorithm that generates a natural45;language string explaining the data. iPrompt iteratively alternates between generating explanations with an LLM and reranking them based on their performance when used as a prompt. Experiments on a wide range of datasets from synthetic mathematics to natural45;language understanding show that iPrompt can yield meaningful insights by accurately finding groundtruth dataset descriptions. Moreover the prompts produced by iPrompt are simultaneously human45;interpretable and highly effective for generalization on real45;world sentiment classification datasets iPrompt produces prompts that match or even improve upon human45;written prompts for GPT45;3. Finally experiments with an fMRI dataset show the potential for iPrompt to aid in scientific discovery. All code for using the methods and data here is made available on Github.

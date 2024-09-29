---
layout: publication
title: Batchprompt&#58; Accomplish More With Less
authors: Lin Jianzhe, Diesendruck Maurice, Du Liang, Abraham Robin
conference: "Arxiv"
year: 2023
bibkey: lin2023accomplish
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.00384"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
As the ever-increasing token limits of large language models (LLMs) have enabled long context as input prompting with single data samples might no longer an efficient way. A straightforward strategy improving efficiency is to batch data within the token limit (e.g. 8k for gpt-3.5-turbo; 32k for GPT-4) which we call BatchPrompt. We have two initial observations for prompting with batched data. First we find that prompting with batched data in longer contexts will inevitably lead to worse performance compared to single-data prompting. Second the performance of the language model is significantly correlated with the positions and order of the batched data due to the corresponding change in decoder context. To retain efficiency and overcome performance loss we propose Batch Permutation and Ensembling (BPE) and a novel Self-reflection-guided EArly Stopping (SEAS) technique. Our comprehensive experimental evaluation demonstrates that BPE can boost the performance of BatchPrompt with a striking margin on a range of popular NLP tasks including question answering (Boolq) textual entailment (RTE) and duplicate questions identification (QQP). These performances are even competitive with/higher than single-data prompting(SinglePrompt) while BatchPrompt requires much fewer LLM calls and input tokens (For SinglePrompt v.s. BatchPrompt with batch size 32 using just 937;-1637; the number of LLM calls Boolq accuracy 90.637; to 90.937; with 27.437; tokens QQP accuracy 87.237; to 88.437; with 18.637; tokens RTE accuracy 91.537; to 91.137; with 30.837; tokens). To the best of our knowledge this is the first work to technically improve prompting efficiency of large language models. We hope our simple yet effective approach will shed light on the future research of large language models. The code will be released.

---
layout: publication
title: 'Learning And Forgetting Unsafe Examples In Large Language Models'
authors: Zhao Jiachen, Deng Zhun, Madras David, Zou James, Ren Mengye
conference: "Arxiv"
year: 2023
bibkey: zhao2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.12736"}
tags: ['Ethics And Bias', 'Responsible AI']
---
As the number of large language models (LLMs) released to the public grows, there is a pressing need to understand the safety implications associated with these models learning from third-party custom finetuning data. We explore the behavior of LLMs finetuned on noisy custom data containing unsafe content, represented by datasets that contain biases, toxicity, and harmfulness, finding that while aligned LLMs can readily learn this unsafe content, they also tend to forget it more significantly than other examples when subsequently finetuned on safer content. Drawing inspiration from the discrepancies in forgetting, we introduce the ForgetFilter algorithm, which filters unsafe data based on how strong the model's forgetting signal is for that data. We demonstrate that the ForgetFilter algorithm ensures safety in customized finetuning without compromising downstream task performance, unlike sequential safety finetuning. ForgetFilter outperforms alternative strategies like replay and moral self-correction in curbing LLMs' ability to assimilate unsafe content during custom finetuning, e.g. 75&#37; lower than not applying any safety measures and 62&#37; lower than using self-correction in toxicity score.

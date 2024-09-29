---
layout: publication
title: Baby Llama Knowledge Distillation From An Ensemble Of Teachers Trained On A Small Dataset With No Performance Penalty
authors: Timiryasov Inar, Tastet Jean-loup
conference: "Arxiv"
year: 2023
bibkey: timiryasov2023baby
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.02019"}
tags: ['Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Training Techniques']
---
We present our submission to the BabyLM challenge whose goal was to improve the sample efficiency of language models. We trained an ensemble consisting of a GPT45;2 and small LLaMA models on the developmentally45;plausible 10M45;word BabyLM dataset then distilled it into a small 58M45;parameter LLaMA model which exceeds in performance both of its teachers as well as a similar model trained without distillation. This suggests that distillation can not only retain the full performance of the teacher model when the latter is trained on a sufficiently small dataset; it can exceed it and lead to significantly better performance than direct training.

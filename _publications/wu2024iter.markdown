---
layout: publication
title: 'Iter-ahmcl: Alleviate Hallucination For Large Language Model Via Iterative Model-level Contrastive Learning'
authors: Huiwen Wu, Xiaohan Li, Xiaogang Xu, Jiafei Wu, Deyi Zhang, Zhe Liu
conference: "Arxiv"
year: 2024
bibkey: wu2024iter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12130"}
tags: ['Pretraining Methods', 'Security', 'Applications', 'RAG']
---
The development of Large Language Models (LLMs) has significantly advanced
various AI applications in commercial and scientific research fields, such as
scientific literature summarization, writing assistance, and knowledge graph
construction. However, a significant challenge is the high risk of
hallucination during LLM inference, which can lead to security concerns like
factual inaccuracies, inconsistent information, and fabricated content. To
tackle this issue, it is essential to develop effective methods for reducing
hallucination while maintaining the original capabilities of the LLM. This
paper introduces a novel approach called Iterative Model-level Contrastive
Learning (Iter-AHMCL) to address hallucination. This method modifies the
representation layers of pre-trained LLMs by using contrastive `positive' and
`negative' models, trained on data with and without hallucinations. By
leveraging the differences between these two models, we create a more
straightforward pathway to eliminate hallucinations, and the iterative nature
of contrastive learning further enhances performance. Experimental validation
on four pre-trained foundation LLMs (LLaMA2, Alpaca, LLaMA3, and Qwen)
finetuning with a specially designed dataset shows that our approach achieves
an average improvement of 10.1 points on the TruthfulQA benchmark.
Comprehensive experiments demonstrate the effectiveness of Iter-AHMCL in
reducing hallucination while maintaining the general capabilities of LLMs.

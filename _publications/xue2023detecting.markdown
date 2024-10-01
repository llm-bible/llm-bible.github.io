---
layout: publication
title: 'RCOT: Detecting And Rectifying Factual Inconsistency In Reasoning By Reversing Chain-of-thought'
authors: Xue Tianci, Wang Ziqi, Wang Zhenhailong, Han Chi, Yu Pengfei, Ji Heng
conference: "Arxiv"
year: 2023
bibkey: xue2023detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11499"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
"Large language Models (LLMs) have achieved promising performance on arithmetic reasoning tasks by incorporating step-by-step chain-of-thought (CoT) prompting. However, LLMs face challenges in maintaining factual consistency during reasoning, exhibiting tendencies to condition overlooking, question misinterpretation, and condition hallucination over given problems. Existing methods use coarse-grained feedback (e.g., whether the answer is correct) to improve factual consistency. In this work, we propose RCoT (Reversing Chain-of-Thought), a novel method to improve LLMs' reasoning abilities by automatically detecting and rectifying factual inconsistency in LLMs, generated solutions. To detect factual inconsistency, RCoT first asks LLMs to reconstruct the problem based on generated solutions. Then fine-grained comparisons between the original problem and the reconstructed problem expose the factual inconsistency in the original solutions. To rectify the solution, RCoT formulates detected factual inconsistency into fine-grained feedback to guide LLMs in revising solutions. Experimental results demonstrate improvements of RCoT over standard CoT, Self-Consistency and Self-Refine across seven arithmetic datasets. Moreover, we find that manually written fine-grained feedback can dramatically improve LLMs' reasoning abilities (e.g., ChatGPT reaches 94.6&#37; accuracy on GSM8K), encouraging the community to further explore the fine-grained feedback generation methods."

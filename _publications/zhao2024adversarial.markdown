---
layout: publication
title: 'Adversarial Contrastive Decoding: Boosting Safety Alignment Of Large Language Models Via Opposite Prompt Optimization'
authors: Zhao Zhengyue, Zhang Xiaoyun, Xu Kaidi, Hu Xing, Zhang Rui, Du Zidong, Guo Qi, Chen Yunji
conference: "Arxiv"
year: 2024
bibkey: zhao2024adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16743"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
With the widespread application of Large Language Models (LLMs) it has become a significant concern to ensure their safety and prevent harmful responses. While current safe-alignment methods based on instruction fine-tuning and Reinforcement Learning from Human Feedback (RLHF) can effectively reduce harmful responses from LLMs they often require high-quality datasets and heavy computational overhead during model training. Another way to align language models is to modify the logit of tokens in model outputs without heavy training. Recent studies have shown that contrastive decoding can enhance the performance of language models by reducing the likelihood of confused tokens. However these methods require the manual selection of contrastive models or instruction templates. To this end we propose Adversarial Contrastive Decoding (ACD) an optimization-based framework to generate two opposite system prompts for prompt-based contrastive decoding. ACD only needs to apply a lightweight prompt tuning on a rather small anchor dataset (< 3 min for each model) without training the target model. Experiments conducted on extensive models and benchmarks demonstrate that the proposed method achieves much better safety performance than previous model training-free decoding methods without sacrificing its original generation ability.

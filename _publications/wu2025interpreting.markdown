---
layout: publication
title: 'Interpreting And Steering Llms With Mutual Information-based Explanations On Sparse Autoencoders'
authors: Xuansheng Wu, Jiayi Yuan, Wenlin Yao, Xiaoming Zhai, Ninghao Liu
conference: "Arxiv"
year: 2025
bibkey: wu2025interpreting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15576'}
tags: ['Ethics and Bias', 'Interpretability and Explainability', 'Applications', 'Security']
---
Large language models (LLMs) excel at handling human queries, but they can
occasionally generate flawed or unexpected responses. Understanding their
internal states is crucial for understanding their successes, diagnosing their
failures, and refining their capabilities. Although sparse autoencoders (SAEs)
have shown promise for interpreting LLM internal representations, limited
research has explored how to better explain SAE features, i.e., understanding
the semantic meaning of features learned by SAE. Our theoretical analysis
reveals that existing explanation methods suffer from the frequency bias issue,
where they emphasize linguistic patterns over semantic concepts, while the
latter is more critical to steer LLM behaviors. To address this, we propose
using a fixed vocabulary set for feature interpretations and designing a mutual
information-based objective, aiming to better capture the semantic meaning
behind these features. We further propose two runtime steering strategies that
adjust the learned feature activations based on their corresponding
explanations. Empirical results show that, compared to baselines, our method
provides more discourse-level explanations and effectively steers LLM behaviors
to defend against jailbreak attacks. These findings highlight the value of
explanations for steering LLM behaviors in downstream applications. We will
release our code and data once accepted.

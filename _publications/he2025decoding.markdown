---
layout: publication
title: 'Delta: A Decoding Strategy Based On Logit Trajectory Prediction Improves Factuality And Reasoning Ability'
authors: Yunzhen He, Yusuke Takase, Yoichi Ishibashi, Hidetoshi Shimodaira
conference: "Arxiv"
year: 2025
bibkey: he2025decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02343"}
tags: ['Transformer', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) are increasingly being used in real-world
applications. However, concerns about the reliability of the content they
generate persist, as it frequently deviates from factual correctness or
exhibits deficiencies in logical reasoning. This paper proposes a novel
decoding strategy aimed at enhancing both factual accuracy and inferential
reasoning without requiring any modifications to the architecture or
pre-trained parameters of LLMs. Our approach adjusts next-token probabilities
by analyzing the trajectory of logits from lower to higher layers in
Transformers and applying linear regression. We find that this Decoding by
Logit Trajectory-based approach (DeLTa) effectively reinforces factuality and
reasoning while mitigating incorrect generation. Experiments on TruthfulQA
demonstrate that DeLTa attains up to a 4.9% improvement over the baseline.
Furthermore, it enhances performance by up to 8.1% on StrategyQA and 7.3% on
GSM8K, both of which demand strong reasoning capabilities.

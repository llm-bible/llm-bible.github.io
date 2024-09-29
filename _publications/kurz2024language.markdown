---
layout: publication
title: 'Language-specific Calibration For Pruning Multilingual Language Models'
authors: Kurz Simon, Chen Jian-jia, Flek Lucie, Zhao Zhixue
conference: "Arxiv"
year: 2024
bibkey: kurz2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14398"}
tags: ['Efficiency And Optimization', 'Pruning', 'Training Techniques']
---
Recent advances in large language model (LLM) pruning have shown state-of-the-art compression results in post-training and retraining-free settings while maintaining high predictive performance. However such research mainly considers calibrating pruning using English text despite the multilingual nature of modern LLMs and their frequent uses in non-English languages. In this paper we set out to explore effective strategies for calibrating the pruning of multilingual language models. We present the first comprehensive empirical study comparing different calibration languages for pruning multilingual models across diverse tasks models and state-of-the-art pruning techniques. Our results present practical suggestions for example calibrating in the target language can efficiently yield lower perplexity but does not necessarily benefit downstream tasks. Our further analysis experiments unveil that calibration in the target language mainly contributes to preserving language-specific features related to fluency and coherence but might not contribute to capturing language-agnostic features such as language understanding and reasoning. Last we provide practical recommendations for future practitioners.

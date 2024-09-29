---
layout: publication
title: Language45;specific Calibration For Pruning Multilingual Language Models
authors: Kurz Simon, Chen Jian-jia, Flek Lucie, Zhao Zhixue
conference: "Arxiv"
year: 2024
bibkey: kurz2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14398"}
tags: ['Efficiency And Optimization', 'Pruning', 'Training Techniques']
---
Recent advances in large language model (LLM) pruning have shown state45;of45;the45;art compression results in post45;training and retraining45;free settings while maintaining high predictive performance. However such research mainly considers calibrating pruning using English text despite the multilingual nature of modern LLMs and their frequent uses in non45;English languages. In this paper we set out to explore effective strategies for calibrating the pruning of multilingual language models. We present the first comprehensive empirical study comparing different calibration languages for pruning multilingual models across diverse tasks models and state45;of45;the45;art pruning techniques. Our results present practical suggestions for example calibrating in the target language can efficiently yield lower perplexity but does not necessarily benefit downstream tasks. Our further analysis experiments unveil that calibration in the target language mainly contributes to preserving language45;specific features related to fluency and coherence but might not contribute to capturing language45;agnostic features such as language understanding and reasoning. Last we provide practical recommendations for future practitioners.

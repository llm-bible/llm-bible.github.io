---
layout: publication
title: 'Shared Path: Unraveling Memorization In Multilingual Llms Through Language Similarities'
authors: Xiaoyu Luo, Yiyi Chen, Johannes Bjerva, Qiongxiu Li
conference: "Arxiv"
year: 2025
bibkey: luo2025shared
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15722"}
tags: ['Training Techniques', 'Survey Paper', 'Model Architecture']
---
We present the first comprehensive study of Memorization in Multilingual Large Language Models (MLLMs), analyzing 95 languages using models across diverse model scales, architectures, and memorization definitions. As MLLMs are increasingly deployed, understanding their memorization behavior has become critical. Yet prior work has focused primarily on monolingual models, leaving multilingual memorization underexplored, despite the inherently long-tailed nature of training corpora. We find that the prevailing assumption, that memorization is highly correlated with training data availability, fails to fully explain memorization patterns in MLLMs. We hypothesize that treating languages in isolation - ignoring their similarities - obscures the true patterns of memorization. To address this, we propose a novel graph-based correlation metric that incorporates language similarity to analyze cross-lingual memorization. Our analysis reveals that among similar languages, those with fewer training tokens tend to exhibit higher memorization, a trend that only emerges when cross-lingual relationships are explicitly modeled. These findings underscore the importance of a language-aware perspective in evaluating and mitigating memorization vulnerabilities in MLLMs. This also constitutes empirical evidence that language similarity both explains Memorization in MLLMs and underpins Cross-lingual Transferability, with broad implications for multilingual NLP.

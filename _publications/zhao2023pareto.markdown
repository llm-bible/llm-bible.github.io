---
layout: publication
title: 'Pareto Optimal Learning For Estimating Large Language Model Errors'
authors: Theodore Zhao, Mu Wei, J. Samuel Preston, Hoifung Poon
conference: "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1 Long Papers). 2024"
year: 2023
bibkey: zhao2023pareto
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.16564'}
tags: ['Prompting', 'Efficiency and Optimization', 'Applications', 'Tools']
---
Large Language Models (LLMs) have shown impressive abilities in many
applications. When a concrete and precise answer is desired, it is important to
have a quantitative estimation of the potential error rate. However, this can
be challenging due to the text-in-text-out nature of generative models. We
present a method based on Pareto optimization that generates a risk score to
estimate the probability of error in an LLM response by integrating multiple
sources of information. We prove theoretically that the error estimator
optimized in our framework aligns with the LLM and the information sources in
an Pareto optimal manner. Experimental results show that the risk scores
estimated by our method are well correlated with the true LLM error rate, thus
facilitating error correction. By dynamically combining with prompting
strategies such as self-verification and information retrieval, we demonstrate
the proposed method can be utilized to increase the performance of an LLM,
surpassing state-of-the-art task specific models.

---
layout: publication
title: 'Uncertainty Quantification For Language Models: A Suite Of Black-box, White-box, LLM Judge, And Ensemble Scorers'
authors: Dylan Bouchard, Mohit Singh Chauhan
conference: "Arxiv"
year: 2025
bibkey: bouchard2025uncertainty
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.19254'}
tags: ['Reinforcement Learning', 'Tools', 'Applications']
---
Hallucinations are a persistent problem with Large Language Models (LLMs). As
these models become increasingly used in high-stakes domains, such as
healthcare and finance, the need for effective hallucination detection is
crucial. To this end, we propose a versatile framework for zero-resource
hallucination detection that practitioners can apply to real-world use cases.
To achieve this, we adapt a variety of existing uncertainty quantification (UQ)
techniques, including black-box UQ, white-box UQ, and LLM-as-a-Judge,
transforming them as necessary into standardized response-level confidence
scores ranging from 0 to 1. To enhance flexibility, we introduce a tunable
ensemble approach that incorporates any combination of the individual
confidence scores. This approach enables practitioners to optimize the ensemble
for a specific use case for improved performance. To streamline implementation,
the full suite of scorers is offered in this paper's companion Python toolkit,
UQLM. To evaluate the performance of the various scorers, we conduct an
extensive set of experiments using several LLM question-answering benchmarks.
We find that our tunable ensemble typically surpasses its individual components
and outperforms existing hallucination detection methods. Our results
demonstrate the benefits of customized hallucination detection strategies for
improving the accuracy and reliability of LLMs.

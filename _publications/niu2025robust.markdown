---
layout: publication
title: 'Robust Hallucination Detection In Llms Via Adaptive Token Selection'
authors: Mengjia Niu, Hamed Haddadi, Guansong Pang
conference: "Arxiv"
year: 2025
bibkey: niu2025robust
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.07863'}
tags: ['Security', 'Responsible AI', 'Training Techniques']
---
Hallucinations in large language models (LLMs) pose significant safety
concerns that impede their broader deployment. Recent research in hallucination
detection has demonstrated that LLMs' internal representations contain
truthfulness hints, which can be harnessed for detector training. However, the
performance of these detectors is heavily dependent on the internal
representations of predetermined tokens, fluctuating considerably when working
on free-form generations with varying lengths and sparse distributions of
hallucinated entities. To address this, we propose HaMI, a novel approach that
enables robust detection of hallucinations through adaptive selection and
learning of critical tokens that are most indicative of hallucinations. We
achieve this robustness by an innovative formulation of the Hallucination
detection task as Multiple Instance (HaMI) learning over token-level
representations within a sequence, thereby facilitating a joint optimisation of
token selection and hallucination detection on generation sequences of diverse
forms. Comprehensive experimental results on four hallucination benchmarks show
that HaMI significantly outperforms existing state-of-the-art approaches.

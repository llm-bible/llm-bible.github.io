---
layout: publication
title: 'Synthetic Artifact Auditing: Tracing Llm-generated Synthetic Data Usage In Downstream Applications'
authors: Yixin Wu, Ziqing Yang, Yun Shen, Michael Backes, Yang Zhang
conference: "Arxiv"
year: 2025
bibkey: wu2025synthetic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.00808'}
tags: ['Interpretability and Explainability', 'RAG', 'Training Techniques', 'Applications', 'Tools', 'Ethics and Bias', 'Interpretability']
---
Large language models (LLMs) have facilitated the generation of high-quality,
cost-effective synthetic data for developing downstream models and conducting
statistical analyses in various domains. However, the increased reliance on
synthetic data may pose potential negative impacts. Numerous studies have
demonstrated that LLM-generated synthetic data can perpetuate and even amplify
societal biases and stereotypes, and produce erroneous outputs known as
``hallucinations'' that deviate from factual knowledge. In this paper, we aim
to audit artifacts, such as classifiers, generators, or statistical plots, to
identify those trained on or derived from synthetic data and raise user
awareness, thereby reducing unexpected consequences and risks in downstream
applications. To this end, we take the first step to introduce synthetic
artifact auditing to assess whether a given artifact is derived from
LLM-generated synthetic data. We then propose an auditing framework with three
methods including metric-based auditing, tuning-based auditing, and
classification-based auditing. These methods operate without requiring the
artifact owner to disclose proprietary training details. We evaluate our
auditing framework on three text classification tasks, two text summarization
tasks, and two data visualization tasks across three training scenarios. Our
evaluation demonstrates the effectiveness of all proposed auditing methods
across all these tasks. For instance, black-box metric-based auditing can
achieve an average accuracy of \\(0.868 \pm 0.071\\) for auditing classifiers and
\\(0.880 \pm 0.052\\) for auditing generators using only 200 random queries across
three scenarios. We hope our research will enhance model transparency and
regulatory compliance, ensuring the ethical and responsible use of synthetic
data.

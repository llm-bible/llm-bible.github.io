---
layout: publication
title: 'Factcheckmate: Preemptively Detecting And Mitigating Hallucinations In Lms'
authors: Deema Alnuhait, Neeraja Kirtane, Muhammad Khalifa, Hao Peng
conference: "Arxiv"
year: 2024
bibkey: alnuhait2024preemptively
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02899'}
tags: ['Reinforcement Learning', 'RAG']
---
Language models (LMs) hallucinate. We inquire: Can we detect and mitigate
hallucinations before they happen? This work answers this research question in
the positive, by showing that the internal representations of LMs provide rich
signals that can be used for this purpose. We introduce FactCheckMate, which
preemptively detects hallucinations by learning a classifier that predicts
whether the LM will hallucinate, based on the model's hidden states produced
over the inputs, before decoding begins. If a hallucination is detected,
FactCheckMate then intervenes, by adjusting the LM's hidden states such that
the model will produce more factual outputs. FactCheckMate provides fresh
insights that the inner workings of LMs can be revealed by their hidden states.
Practically, both the detection and mitigation models in FactCheckMate are
lightweight, adding little inference overhead; FactCheckMate proves a more
efficient approach for mitigating hallucinations compared to many post-hoc
alternatives. We evaluate FactCheckMate over LMs of different scales and model
families (including Llama, Mistral, and Gemma), across a variety of QA datasets
from different domains. Our results demonstrate the effectiveness of leveraging
internal representations for early hallucination detection and mitigation,
achieving over 70% preemptive detection accuracy. On average, outputs generated
by LMs with intervention are 34.4% more factual compared to those without
intervention. The average overhead difference in the inference time introduced
by FactCheckMate is around 3.16 seconds.

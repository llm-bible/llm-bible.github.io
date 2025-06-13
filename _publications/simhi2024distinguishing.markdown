---
layout: publication
title: 'Distinguishing Ignorance From Error In LLM Hallucinations'
authors: Adi Simhi, Jonathan Herzig, Idan Szpektor, Yonatan Belinkov
conference: "Arxiv"
year: 2024
bibkey: simhi2024distinguishing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22071"}
  - {name: "Code", url: "https://github.com/technion-cs-nlp/hallucination-mitigation"}
tags: ['Has Code', 'Training Techniques', 'Attention Mechanism', 'Model Architecture']
---
Large language models (LLMs) are susceptible to hallucinations -- factually
incorrect outputs -- leading to a large body of work on detecting and
mitigating such cases. We argue that it is important to distinguish between two
types of hallucinations: ones where the model does not hold the correct answer
in its parameters, which we term HK-, and ones where the model answers
incorrectly despite having the required knowledge, termed HK+. We first find
that HK+ hallucinations are prevalent and occur across models and datasets.
Then, we demonstrate that distinguishing between these two cases is beneficial
for mitigating hallucinations. Importantly, we show that different models
hallucinate on different examples, which motivates constructing model-specific
hallucination datasets for training detectors. Overall, our findings draw
attention to classifying types of hallucinations and provide means to handle
them more effectively. The code is available at
https://github.com/technion-cs-nlp/hallucination-mitigation .

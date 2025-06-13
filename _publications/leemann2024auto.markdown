---
layout: publication
title: 'Auto-gda: Automatic Domain Adaptation For Efficient Grounding Verification In Retrieval-augmented Generation'
authors: Tobias Leemann, Periklis Petridis, Giuseppe Vietri, Dionysis Manousakas, Aaron Roth, Sergul Aydore
conference: "Arxiv"
year: 2024
bibkey: leemann2024auto
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03461"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
While retrieval-augmented generation (RAG) has been shown to enhance
factuality of large language model (LLM) outputs, LLMs still suffer from
hallucination, generating incorrect or irrelevant information. A common
detection strategy involves prompting the LLM again to assess whether its
response is grounded in the retrieved evidence, but this approach is costly.
Alternatively, lightweight natural language inference (NLI) models for
efficient grounding verification can be used at inference time. While existing
pre-trained NLI models offer potential solutions, their performance remains
subpar compared to larger models on realistic RAG inputs. RAG inputs are more
complex than most datasets used for training NLI models and have
characteristics specific to the underlying knowledge base, requiring adaptation
of the NLI models to a specific target domain. Additionally, the lack of
labeled instances in the target domain makes supervised domain adaptation,
e.g., through fine-tuning, infeasible. To address these challenges, we
introduce Automatic Generative Domain Adaptation (Auto-GDA). Our framework
enables unsupervised domain adaptation through synthetic data generation.
Unlike previous methods that rely on handcrafted filtering and augmentation
strategies, Auto-GDA employs an iterative process to continuously improve the
quality of generated samples using weak labels from less efficient teacher
models and discrete optimization to select the most promising augmented
samples. Experimental results demonstrate the effectiveness of our approach,
with models fine-tuned on synthetic data using Auto-GDA often surpassing the
performance of the teacher model and reaching the performance level of LLMs at
10% of their computational cost.

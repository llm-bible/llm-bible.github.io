---
layout: publication
title: 'Post-training An LLM For RAG? Train On Self-generated Demonstrations'
authors: Matthew Finlayson, Ilia Kulikov, Daniel M. Bikel, Barlas Oguz, Xilun Chen, Aasish Pappu
conference: "Arxiv"
year: 2025
bibkey: finlayson2025post
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10596'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) often struggle with knowledge intensive NLP
tasks, such as answering "Who won the latest World Cup?" because the knowledge
they learn during training may be insufficient or outdated. Conditioning
generation on retrieved documents -- a technique known as retrieval augmented
generation (RAG) -- mitigates these shortcomings by allowing the model to
leverage in-context information. Practitioners can improve LLM RAG performance
by fine-tuning on retrieval-augmented instructions, but must beware that this
can cause undesirable model behaviors like hallucinations. We attribute this
degradation to the fact that the training data is likely to be
out-of-distribution for the model and may suffer from quality issues, such as
misalignment between retrievals and target responses (since retrievals are
frequently added post-hoc). We propose a recipe for training RAG-enabled LLMs
using self-generated demonstrations, thereby avoiding training on
out-of-distribution text and integrating retrievals into the LLM responses. We
evaluate our method on knowledge intensive question answering (QA) tasks and
show that our method teaches LLMs to properly handle in-context retrievals and
abstain from questions it will likely get wrong. Compared to conventional RA-IT
methods, our method prevents model degradation in non-RAG settings while
exhibiting superior QA performance.

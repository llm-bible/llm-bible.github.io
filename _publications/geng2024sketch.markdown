---
layout: publication
title: 'Sketch-guided Constrained Decoding For Boosting Blackbox Large Language Models Without Logit Access'
authors: Saibo Geng, Berkay Döner, Chris Wendler, Martin Josifoski, Robert West
conference: "Arxiv"
year: 2024
bibkey: geng2024sketch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.09967"}
tags: ['Training Techniques', 'Language Modeling', 'Ethics and Bias', 'Interpretability', 'Applications']
---
Constrained decoding, a technique for enforcing constraints on language model
outputs, offers a way to control text generation without retraining or
architectural modifications. Its application is, however, typically restricted
to models that give users access to next-token distributions (usually via
softmax logits), which poses a limitation with blackbox large language models
(LLMs). This paper introduces sketch-guided constrained decoding (SGCD), a
novel approach to constrained decoding for blackbox LLMs, which operates
without access to the logits of the blackbox LLM. SGCD utilizes a locally
hosted auxiliary model to refine the output of an unconstrained blackbox LLM,
effectively treating this initial output as a "sketch" for further elaboration.
This approach is complementary to traditional logit-based techniques and
enables the application of constrained decoding in settings where full model
transparency is unavailable. We demonstrate the efficacy of SGCD through
experiments in closed information extraction and constituency parsing, showing
how it enhances the utility and flexibility of blackbox LLMs for complex NLP
tasks.

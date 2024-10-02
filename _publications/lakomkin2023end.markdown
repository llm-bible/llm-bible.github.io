---
layout: publication
title: 'End-to-end Speech Recognition Contextualization With Large Language Models'
authors: Lakomkin Egor, Wu Chunyang, Fathullah Yassir, Kalinli Ozlem, Seltzer Michael L., Fuegen Christian
conference: "Arxiv"
year: 2023
bibkey: lakomkin2023end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.10917"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
'In recent years, Large Language Models (LLMs) have garnered significant attention from the research community due to their exceptional performance and generalization capabilities. In this paper, we introduce a novel method for contextualizing speech recognition models incorporating LLMs. Our approach casts speech recognition as a mixed-modal language modeling task based on a pretrained LLM. We provide audio features, along with optional text tokens for context, to train the system to complete transcriptions in a decoder-only fashion. As a result, the system is implicitly incentivized to learn how to leverage unstructured contextual information during training. Our empirical results demonstrate a significant improvement in performance, with a 6&#37; WER reduction when additional textual context is provided. Moreover, we find that our method performs competitively and improve by 7.5&#37; WER overall and 17&#37; WER on rare words against a baseline contextualized RNN-T system that has been trained on more than twenty five times larger speech dataset. Overall, we demonstrate that by only adding a handful number of trainable parameters via adapters, we can unlock contextualized speech recognition capability for the pretrained LLM while keeping the same text-only input functionality.'

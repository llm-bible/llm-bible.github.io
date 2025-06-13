---
layout: publication
title: 'Chain-of-thought Prompting For Speech Translation'
authors: Ke Hu, Zhehuai Chen, Chao-han Huck Yang, Piotr Żelasko, Oleksii Hrinchuk, Vitaly Lavrukhin, Jagadeesh Balam, Boris Ginsburg
conference: "Arxiv"
year: 2024
bibkey: hu2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11538"}
tags: ['Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'INTERSPEECH']
---
Large language models (LLMs) have demonstrated remarkable advancements in
language understanding and generation. Building on the success of text-based
LLMs, recent research has adapted these models to use speech embeddings for
prompting, resulting in Speech-LLM models that exhibit strong performance in
automatic speech recognition (ASR) and automatic speech translation (AST). In
this work, we propose a novel approach to leverage ASR transcripts as prompts
for AST in a Speech-LLM built on an encoder-decoder text LLM. The Speech-LLM
model consists of a speech encoder and an encoder-decoder structure
Megatron-T5. By first decoding speech to generate ASR transcripts and
subsequently using these transcripts along with encoded speech for prompting,
we guide the speech translation in a two-step process like chain-of-thought
(CoT) prompting. Low-rank adaptation (LoRA) is used for the T5 LLM for model
adaptation and shows superior performance to full model fine-tuning.
Experimental results show that the proposed CoT prompting significantly
improves AST performance, achieving an average increase of 2.4 BLEU points
across 6 En->X or X->En AST tasks compared to speech prompting alone.
Additionally, compared to a related CoT prediction method that predicts a
concatenated sequence of ASR and AST transcripts, our method performs better by
an average of 2 BLEU points.

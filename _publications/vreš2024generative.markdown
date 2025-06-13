---
layout: publication
title: 'Generative Model For Less-resourced Language With 1 Billion Parameters'
authors: Domen Vreš, Martin Božič, Aljaž Potočnik, Tomaž Martinčič, Marko Robnik-šikonja
conference: "Arxiv"
year: 2024
bibkey: vreš2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06898"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'GPT', 'Pretraining Methods', 'BERT', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) are a basic infrastructure for modern natural
language processing. Many commercial and open-source LLMs exist for English,
e.g., ChatGPT, Llama, Falcon, and Mistral. As these models are trained on
mostly English texts, their fluency and knowledge of low-resource languages and
societies are superficial. We present the development of large generative
language models for a less-resourced language. GaMS 1B - Generative Model for
Slovene with 1 billion parameters was created by continuing pretraining of the
existing English OPT model. We developed a new tokenizer adapted to Slovene,
Croatian, and English languages and used embedding initialization methods FOCUS
and WECHSEL to transfer the embeddings from the English OPT model. We evaluate
our models on several classification datasets from the Slovene suite of
benchmarks and generative sentence simplification task SENTA. We only used a
few-shot in-context learning of our models, which are not yet
instruction-tuned. For classification tasks, in this mode, the generative
models lag behind the existing Slovene BERT-type models fine-tuned for specific
tasks. On a sentence simplification task, the GaMS models achieve comparable or
better performance than the GPT-3.5-Turbo model.

---
layout: publication
title: Think Big, Generate Quick&#58; Llm-to-slm For Fast Autoregressive Decoding
authors: Bergner Benjamin, Skliar Andrii, Royer Amelie, Blankevoort Tijmen, Asano Yuki, Bejnordi Babak Ehteshami
conference: "Arxiv"
year: 2024
bibkey: bergner2024think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16844"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) have become ubiquitous in practice and are widely used for generation tasks such as translation summarization and instruction following. However their enormous size and reliance on autoregressive decoding increase deployment costs and complicate their use in latency-critical applications. In this work we propose a hybrid approach that combines language models of different sizes to increase the efficiency of autoregressive decoding while maintaining high performance. Our method utilizes a pretrained frozen LLM that encodes all prompt tokens once in parallel and uses the resulting representations to condition and guide a small language model (SLM) which then generates the response more efficiently. We investigate the combination of encoder-decoder LLMs with both encoder-decoder and decoder-only SLMs from different model families and only require fine-tuning of the SLM. Experiments with various benchmarks show substantial speedups of up to 4(times) with minor performance penalties of 1-237; for translation and summarization tasks compared to the LLM.

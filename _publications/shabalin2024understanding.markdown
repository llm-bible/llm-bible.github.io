---
layout: publication
title: 'Tencdm: Understanding The Properties Of The Diffusion Model In The Space Of Language Model Encodings'
authors: Alexander Shabalin, Viacheslav Meshchaninov, Egor Chimbulatov, Vladislav Lapikov, Roman Kim, Grigory Bartosh, Dmitry Molchanov, Sergey Markov, Dmitry Vetrov
conference: "Arxiv"
year: 2024
bibkey: shabalin2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.19097"}
  - {name: "Code", url: "https://github.com/M0RJIQUE/tencdm"}
tags: ['Model Architecture', 'Language Modeling', 'Merging', 'GPT', 'Pretraining Methods', 'Transformer', 'Has Code', 'Applications']
---
This paper presents the Text Encoding Diffusion Model (TEncDM), a novel
approach to diffusion modeling that operates in the space of pre-trained
language model encodings. In contrast to traditionally used embeddings,
encodings integrate contextual information. In our approach, we also employ a
transformer-based decoder, specifically designed to incorporate context in the
token prediction process. We conduct a comprehensive examination of the
influence of the encoder, decoder, noise scheduler, and self-conditioning on
zero-shot generation. Furthermore, we compare TEncDM with previous approaches
on three conditional text generation tasks: QQP, XSum, and Wiki-Auto. The
results show that TEncDM exhibits superior performance compared to existing
non-autoregressive diffusion models. Our code is available at
https://github.com/M0RJIQUE/tencdm.

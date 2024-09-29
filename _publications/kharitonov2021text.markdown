---
layout: publication
title: Text45;free Prosody45;aware Generative Spoken Language Modeling
authors: Kharitonov Eugene, Lee Ann, Polyak Adam, Adi Yossi, Copet Jade, Lakhotia Kushal, Nguyen Tu-anh, Rivière Morgane, Mohamed Abdelrahman, Dupoux Emmanuel, Hsu Wei-ning
conference: "Arxiv"
year: 2021
bibkey: kharitonov2021text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.03264"}
  - {name: "Code", url: "https://speechbot.github.io/pgslm"}
  - {name: "Code", url: "https://github.com/pytorch/fairseq/tree/main/examples/textless&#95;nlp/pgslm"}
tags: ['GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
Speech pre45;training has primarily demonstrated efficacy on classification tasks while its capability of generating novel speech similar to how GPT45;2 can generate coherent paragraphs has barely been explored. Generative Spoken Language Modeling (GSLM) cite123;Lakhotia2021125; is the only prior work addressing the generative aspects of speech pre45;training which replaces text with discovered phone45;like units for language modeling and shows the ability to generate meaningful novel sentences. Unfortunately despite eliminating the need of text the units used in GSLM discard most of the prosodic information. Hence GSLM fails to leverage prosody for better comprehension and does not generate expressive speech. In this work we present a prosody45;aware generative spoken language model (pGSLM). It is composed of a multi45;stream transformer language model (MS45;TLM) of speech represented as discovered unit and prosodic feature streams and an adapted HiFi45;GAN model converting MS45;TLM outputs to waveforms. We devise a series of metrics for prosody modeling and generation and re45;use metrics from GSLM for content modeling. Experimental results show that the pGSLM can utilize prosody to improve both prosody and content modeling and also generate natural meaningful and coherent speech given a spoken prompt. Audio samples can be found at https://speechbot.github.io/pgslm. Codes and models are available at https://github.com/pytorch/fairseq/tree/main/examples/textless&#95;nlp/pgslm.

---
layout: publication
title: 'Understanding The Effects Of Human-written Paraphrases In Llm-generated Text Detection'
authors: Hiu Ting Lau, Arkaitz Zubiaga
conference: "Arxiv"
year: 2024
bibkey: lau2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.03806"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Attention Mechanism', 'BERT']
---
Natural Language Generation has been rapidly developing with the advent of
large language models (LLMs). While their usage has sparked significant
attention from the general public, it is important for readers to be aware when
a piece of text is LLM-generated. This has brought about the need for building
models that enable automated LLM-generated text detection, with the aim of
mitigating potential negative outcomes of such content. Existing LLM-generated
detectors show competitive performances in telling apart LLM-generated and
human-written text, but this performance is likely to deteriorate when
paraphrased texts are considered. In this study, we devise a new data
collection strategy to collect Human & LLM Paraphrase Collection (HLPC), a
first-of-its-kind dataset that incorporates human-written texts and
paraphrases, as well as LLM-generated texts and paraphrases. With the aim of
understanding the effects of human-written paraphrases on the performance of
state-of-the-art LLM-generated text detectors OpenAI RoBERTa and watermark
detectors, we perform classification experiments that incorporate human-written
paraphrases, watermarked and non-watermarked LLM-generated documents from GPT
and OPT, and LLM-generated paraphrases from DIPPER and BART. The results show
that the inclusion of human-written paraphrases has a significant impact of
LLM-generated detector performance, promoting TPR@1%FPR with a possible
trade-off of AUROC and accuracy.

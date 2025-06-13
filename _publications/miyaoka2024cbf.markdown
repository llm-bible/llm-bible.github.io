---
layout: publication
title: 'CBF-LLM: Safe Control For LLM Alignment'
authors: Yuya Miyaoka, Masaki Inoue
conference: "Arxiv"
year: 2024
bibkey: miyaoka2024cbf
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.15625'}
  - {name: "Code", url: 'https://github.com/Mya-Mya/CBF-LLM'}
tags: ['Has Code', 'Language Modeling', 'RAG', 'Model Architecture', 'Tools', 'BERT', 'Applications', 'Responsible AI']
---
This paper proposes a control-based framework for aligning large language
models (LLMs) by leveraging a control barrier function (CBF) to ensure
user-desirable text generation. The presented framework applies the safety
filter, designed based on the CBF, to the output generation of the baseline
LLM, i.e., the sequence of the token, with the aim of intervening in the
generated text. The overall text-generation system is implemented with Llama 3
and a RoBERTa model, and the source code is available at
https://github.com/Mya-Mya/CBF-LLM. The experiment demonstrates its control
ability and effectiveness in reducing the number of interventions needed for
user-specified alignment tasks.

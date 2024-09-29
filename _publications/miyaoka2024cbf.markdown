---
layout: publication
title: CBF45;LLM Safe Control For LLM Alignment
authors: Miyaoka Yuya, Inoue Masaki
conference: "Arxiv"
year: 2024
bibkey: miyaoka2024cbf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15625"}
  - {name: "Code", url: "https://github.com/Mya&#45;Mya/CBF&#45;LLM"}
tags: ['Applications', 'BERT', 'Has Code', 'Language Modeling', 'Model Architecture', 'RAG', 'Responsible AI', 'Tools']
---
This paper proposes a control45;based framework for aligning large language models (LLMs) by leveraging a control barrier function (CBF) to ensure user45;desirable text generation. The presented framework applies the safety filter designed based on the CBF to the output generation of the baseline LLM i.e. the sequence of the token with the aim of intervening in the generated text. The overall text45;generation system is implemented with Llama 3 and a RoBERTa model and the source code is available at https://github.com/Mya&#45;Mya/CBF&#45;LLM. The experiment demonstrates its control ability and effectiveness in reducing the number of interventions needed for user45;specified alignment tasks.

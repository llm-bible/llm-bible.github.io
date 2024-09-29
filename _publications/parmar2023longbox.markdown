---
layout: publication
title: Longbox Evaluating Transformers On Long-sequence Clinical Tasks
authors: Parmar Mihir, Naik Aakanksha, Gupta Himanshu, Agrawal Disha, Baral Chitta
conference: "Arxiv"
year: 2023
bibkey: parmar2023longbox
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09564"}
  - {name: "Code", url: "https://github.com/Mihir3009/LongBoX"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Many large language models (LLMs) for medicine have largely been evaluated on short texts and their ability to handle longer sequences such as a complete electronic health record (EHR) has not been systematically explored. Assessing these models on long sequences is crucial since prior work in the general domain has demonstrated performance degradation of LLMs on longer texts. Motivated by this we introduce LongBoX a collection of seven medical datasets in text-to-text format designed to investigate model performance on long sequences. Preliminary experiments reveal that both medical LLMs (e.g. BioGPT) and strong general domain LLMs (e.g. FLAN-T5) struggle on this benchmark. We further evaluate two techniques designed for long-sequence handling (i) local-global attention and (ii) Fusion-in-Decoder (FiD). Our results demonstrate mixed results with long-sequence handling - while scores on some datasets increase there is substantial room for improvement. We hope that LongBoX facilitates the development of more effective long-sequence techniques for the medical domain. Data and source code are available at https://github.com/Mihir3009/LongBoX.

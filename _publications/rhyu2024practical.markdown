---
layout: publication
title: 'Practical And Reproducible Symbolic Music Generation By Large Language Models With Structural Embeddings'
authors: Rhyu Seungyeon, Yang Kichang, Cho Sungjun, Kim Jaehyeon, Lee Kyogu, Lee Moontae
conference: "Arxiv"
year: 2024
bibkey: rhyu2024practical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19900"}
tags: ['Model Architecture', 'Pretraining Methods', 'RAG', 'Tokenization', 'Tools', 'Transformer']
---
'Music generation introduces challenging complexities to large language models. Symbolic structures of music often include vertical harmonization as well as horizontal counterpoint, urging various adaptations and enhancements for large-scale Transformers. However, existing works share three major drawbacks: 1) their tokenization requires domain-specific annotations, such as bars and beats, that are typically missing in raw MIDI data; 2) the pure impact of enhancing token embedding methods is hardly examined without domain-specific annotations; and 3) existing works to overcome the aforementioned drawbacks, such as MuseNet, lack reproducibility. To tackle such limitations, we develop a MIDI-based music generation framework inspired by MuseNet, empirically studying two structural embeddings that do not rely on domain-specific annotations. We provide various metrics and insights that can guide suitable encoding to deploy. We also verify that multiple embedding configurations can selectively boost certain musical aspects. By providing open-source implementations via HuggingFace, our findings shed light on leveraging large language models toward practical and reproducible music generation.'

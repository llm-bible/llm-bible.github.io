---
layout: publication
title: 'AFRIDOC-MT: Document-level MT Corpus For African Languages'
authors: Jesujoba O. Alabi, Israel Abebe Azime, Miaoran Zhang, Cristina España-bonet, Rachel Bawden, Dawei Zhu, David Ifeoluwa Adelani, Clement Oyeleke Odoje, Idris Akinade, Iffat Maab, Davis David, Shamsuddeen Hassan Muhammad, Neo Putini, David O. Ademuyiwa, Andrew Caines, Dietrich Klakow
conference: "Arxiv"
year: 2025
bibkey: alabi2025afridoc
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.06374'}
tags: ['RAG', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Applications', 'Pretraining Methods']
---
This paper introduces AFRIDOC-MT, a document-level multi-parallel translation
dataset covering English and five African languages: Amharic, Hausa, Swahili,
Yor\`ub\'a, and Zulu. The dataset comprises 334 health and 271 information
technology news documents, all human-translated from English to these
languages. We conduct document-level translation benchmark experiments by
evaluating neural machine translation (NMT) models and large language models
(LLMs) for translations between English and these languages, at both the
sentence and pseudo-document levels. These outputs are realigned to form
complete documents for evaluation. Our results indicate that NLLB-200 achieved
the best average performance among the standard NMT models, while GPT-4o
outperformed general-purpose LLMs. Fine-tuning selected models led to
substantial performance gains, but models trained on sentences struggled to
generalize effectively to longer documents. Furthermore, our analysis reveals
that some LLMs exhibit issues such as under-generation, repetition of words or
phrases, and off-target translations, especially for African languages.

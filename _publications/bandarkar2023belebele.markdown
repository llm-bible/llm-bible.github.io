---
layout: publication
title: 'The Belebele Benchmark: A Parallel Reading Comprehension Dataset In 122 Language Variants'
authors: Bandarkar Lucas, Liang Davis, Muller Benjamin, Artetxe Mikel, Shukla Satya Narayan, Husa Donald, Goyal Naman, Krishnan Abhinandan, Zettlemoyer Luke, Khabsa Madian
conference: "Arxiv"
year: 2023
bibkey: bandarkar2023belebele
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.16884"}
tags: ['Applications', 'BERT', 'Masked Language Model', 'Pretraining Methods', 'RAG']
---
We present Belebele a multiple-choice machine reading comprehension (MRC) dataset spanning 122 language variants. Significantly expanding the language coverage of natural language understanding (NLU) benchmarks this dataset enables the evaluation of text models in high- medium- and low-resource languages. Each question is based on a short passage from the Flores-200 dataset and has four multiple-choice answers. The questions were carefully curated to discriminate between models with different levels of general language comprehension. The English dataset on its own proves difficult enough to challenge state-of-the-art language models. Being fully parallel this dataset enables direct comparison of model performance across all languages. We use this dataset to evaluate the capabilities of multilingual masked language models (MLMs) and large language models (LLMs). We present extensive results and find that despite significant cross-lingual transfer in English-centric LLMs much smaller MLMs pretrained on balanced multilingual data still understand far more languages. We also observe that larger vocabulary size and conscious vocabulary construction correlate with better performance on low-resource languages. Overall Belebele opens up new avenues for evaluating and analyzing the multilingual capabilities of NLP systems.

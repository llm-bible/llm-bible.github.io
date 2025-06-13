---
layout: publication
title: 'Astromlab 2: Astrollama-2-70b Model And Benchmarking Specialised Llms For Astronomy'
authors: Rui Pan, Tuan Dung Nguyen, Hardik Arora, Alberto Accomazzi, Tirthankar Ghosal, Yuan-sen Ting
conference: "Arxiv"
year: 2024
bibkey: pan2024astromlab
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19750"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Arxiv']
---
Continual pretraining of large language models on domain-specific data has
been proposed to enhance performance on downstream tasks. In astronomy, the
previous absence of astronomy-focused benchmarks has hindered objective
evaluation of these specialized LLM models. Leveraging a recent initiative to
curate high-quality astronomical MCQs, this study aims to quantitatively assess
specialized LLMs in astronomy. We find that the previously released AstroLLaMA
series, based on LLaMA-2-7B, underperforms compared to the base model. We
demonstrate that this performance degradation can be partially mitigated by
utilizing high-quality data for continual pretraining, such as summarized text
from arXiv. Despite the observed catastrophic forgetting in smaller models, our
results indicate that continual pretraining on the 70B model can yield
significant improvements. However, the current supervised fine-tuning dataset
still constrains the performance of instruct models. In conjunction with this
study, we introduce a new set of models, AstroLLaMA-3-8B and AstroLLaMA-2-70B,
building upon the previous AstroLLaMA series.

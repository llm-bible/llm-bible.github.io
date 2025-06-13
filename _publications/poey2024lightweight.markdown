---
layout: publication
title: 'Ragulator: Lightweight Out-of-context Detectors For Grounded Text Generation'
authors: Ian Poey, Jiajun Liu, Qishuai Zhong, Adrien Chenailler
conference: "Arxiv"
year: 2024
bibkey: poey2024lightweight
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.03920'}
tags: ['Language Modeling', 'RAG', 'Training Techniques', 'Applications', 'BERT', 'Model Architecture', 'Merging']
---
Real-time detection of out-of-context LLM outputs is crucial for enterprises
looking to safely adopt RAG applications. In this work, we train lightweight
models to discriminate LLM-generated text that is semantically out-of-context
from retrieved text documents. We preprocess a combination of summarisation and
semantic textual similarity datasets to construct training data using minimal
resources. We find that DeBERTa is not only the best-performing model under
this pipeline, but it is also fast and does not require additional text
preprocessing or feature engineering. While emerging work demonstrates that
generative LLMs can also be fine-tuned and used in complex data pipelines to
achieve state-of-the-art performance, we note that speed and resource limits
are important considerations for on-premise deployment.

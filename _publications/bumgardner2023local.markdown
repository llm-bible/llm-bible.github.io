---
layout: publication
title: 'Local Large Language Models For Complex Structured Medical Tasks'
authors: V. K. Cody Bumgardner, Aaron Mullen, Sam Armstrong, Caylin Hickey, Jeff Talbert
conference: "Arxiv"
year: 2023
bibkey: bumgardner2023local
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.01727"}
tags: ['BERT', 'Training Techniques', 'Applications', 'Model Architecture']
---
This paper introduces an approach that combines the language reasoning
capabilities of large language models (LLMs) with the benefits of local
training to tackle complex, domain-specific tasks. Specifically, the authors
demonstrate their approach by extracting structured condition codes from
pathology reports. The proposed approach utilizes local LLMs, which can be
fine-tuned to respond to specific generative instructions and provide
structured outputs. The authors collected a dataset of over 150k uncurated
surgical pathology reports, containing gross descriptions, final diagnoses, and
condition codes. They trained different model architectures, including LLaMA,
BERT and LongFormer and evaluated their performance. The results show that the
LLaMA-based models significantly outperform BERT-style models across all
evaluated metrics, even with extremely reduced precision. The LLaMA models
performed especially well with large datasets, demonstrating their ability to
handle complex, multi-label tasks. Overall, this work presents an effective
approach for utilizing LLMs to perform domain-specific tasks using accessible
hardware, with potential applications in the medical domain, where complex data
extraction and classification are required.

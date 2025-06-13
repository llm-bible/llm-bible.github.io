---
layout: publication
title: 'Efficient Knowledge Feeding To Language Models: A Novel Integrated Encoder-decoder Architecture'
authors: S Santosh Kumar, Rishi Gottimukkala, Supriya Devidutta, Karthikeyan S
conference: "Arxiv"
year: 2025
bibkey: kumar2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05233"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
This paper introduces a novel approach to efficiently feeding knowledge to
language models (LLMs) during prediction by integrating retrieval and
generation processes within a unified framework. While the Retrieval-Augmented
Generation (RAG) model addresses gaps in LLMs' training data and knowledge
limits, it is hindered by token limit restrictions and dependency on the
retrieval system's accuracy. Our proposed architecture incorporates in-context
vectors (ICV) to overcome these challenges. ICV recasts in-context learning by
using latent embeddings of LLMs to create a vector that captures essential task
information. This vector is then used to shift the latent states of the LLM,
enhancing the generation process without adding demonstration examples to the
prompt. ICV directly integrates information into the model, enabling it to
process this information more effectively. Our extensive experimental
evaluation demonstrates that ICV outperforms standard in-context learning and
fine-tuning across question-answering, information retrieval, and other tasks.
This approach mitigates the limitations of current RAG models and offers a more
robust solution for handling extensive and diverse datasets. Despite leveraging
a fraction of the parameters, our ICV-enhanced model achieves competitive
performance against models like LLaMA-3, Gemma, and Phi-3, significantly
reducing computational costs and memory requirements. ICV reduces prompt
length, is easy to control, surpasses token limitations, and is computationally
efficient compared to fine-tuning.

---
layout: publication
title: 'Reasoning To Attend: Try To Understand How <SEG> Token Works'
authors: Rui Qian, Xin Yin, Dejing Dou
conference: "Arxiv"
year: 2024
bibkey: qian2024reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17741"}
  - {name: "Code", url: "https://github.com/rui-qian/READ"}
tags: ['Multimodal Models', 'Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting']
---
Current Large Multimodal Models (LMMs) empowered visual grounding typically
rely on \\(\texttt\{<SEG>\}\\) tokens as a text prompt to jointly optimize the
vision-language model (e.g., LLaVA) and the downstream task-specific model
(e.g., SAM). However, we observe that little research has looked into how it
works.In this work, we first visualize the similarity maps, which are obtained
by computing the semantic similarity between the \\(\texttt\{<SEG>\}\\) token and the
image token embeddings derived from the last hidden layer in both the LLaVA
encoder and SAM decoder. Intriguingly, we have found that a striking
consistency holds in terms of activation responses in the similarity map, which
reveals that what the \\(\texttt\{<SEG>\}\\) token contributes to is semantic
similarity within image-text pairs. Specifically, the \\(\texttt\{<SEG>\}\\) token, a
placeholder expanded in text vocabulary, extensively queries among individual
tokenized image patches to match the semantics of an object from text to the
paired image, while the Large Language Models (LLMs) are being fine-tuned. Upon
the above findings, we present READ, which facilitates LMMs' resilient
\\(\textbf\{REA\}\\)soning capability of where to atten\\(\textbf\{D\}\\) under the
guidance of highly activated points borrowed from similarity maps. Remarkably,
READ features an intuitive design, Similarity as Points module (SasP), which
can be seamlessly applied to \\(\texttt\{<SEG>\}\\)-like paradigms in a plug-and-play
fashion. Also, extensive experiments have been conducted on ReasonSeg and
RefCOCO(+/g) datasets. To validate whether READ suffers from catastrophic
forgetting of previous skills after fine-tuning, we further assess its
generation ability on an augmented FP-RefCOCO(+/g) dataset. All codes and
models are publicly available at https://github.com/rui-qian/READ.

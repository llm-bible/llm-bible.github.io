---
layout: publication
title: Answer Is All You Need Instruction-following Text Embedding Via Answering The Question
authors: Peng Letian, Zhang Yuwei, Wang Zilong, Srinivasa Jayanth, Liu Gaowen, Wang Zihan, Shang Jingbo
conference: "Arxiv"
year: 2024
bibkey: peng2024answer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09642"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques']
---
This work aims to build a text embedder that can capture characteristics of texts specified by user instructions. Despite its tremendous potential to deploy user-oriented embeddings none of previous approaches provides a concrete solution for it. This paper offers a new viewpoint which treats the instruction as a question about the input text and encodes the expected answers to obtain the representation accordingly. Intuitively texts with the same (implicit) semantics would share similar answers following the instruction thus leading to more similar embeddings. Specifically we propose InBedder that instantiates this embed-via-answering idea by only fine-tuning language models on abstractive question answering tasks. InBedder demonstrates significantly improved instruction-following capabilities according to our proposed instruction awareness tests and instruction robustness tests when applied to both large language models (LLMs) (e.g. llama-2-7b) and smaller encoder-based LMs (e.g. roberta-large). Additionally our qualitative analysis of clustering outcomes achieved by applying different instructions to the same corpus demonstrates a high degree of interpretability.

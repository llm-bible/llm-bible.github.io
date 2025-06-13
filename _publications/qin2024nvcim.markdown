---
layout: publication
title: 'Nvcim-pt: An Nvcim-assisted Prompt Tuning Framework For Edge Llms'
authors: Ruiyang Qin, Pengyu Ren, Zheyu Yan, Liu Liu, Dancheng Liu, Amir Nassereldine, Jinjun Xiong, Kai Ni, Sharon Hu, Yiyu Shi
conference: "Arxiv"
year: 2024
bibkey: qin2024nvcim
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.08244'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large Language Models (LLMs) deployed on edge devices, known as edge LLMs,
need to continuously fine-tune their model parameters from user-generated data
under limited resource constraints. However, most existing learning methods are
not applicable for edge LLMs because of their reliance on high resources and
low learning capacity. Prompt tuning (PT) has recently emerged as an effective
fine-tuning method for edge LLMs by only modifying a small portion of LLM
parameters, but it suffers from user domain shifts, resulting in repetitive
training and losing resource efficiency. Conventional techniques to address
domain shift issues often involve complex neural networks and sophisticated
training, which are incompatible for PT for edge LLMs. Therefore, an open
research question is how to address domain shift issues for edge LLMs with
limited resources. In this paper, we propose a prompt tuning framework for edge
LLMs, exploiting the benefits offered by non-volatile computing-in-memory
(NVCiM) architectures. We introduce a novel NVCiM-assisted PT framework, where
we narrow down the core operations to matrix-matrix multiplication, which can
then be accelerated by performing in-situ computation on NVCiM. To the best of
our knowledge, this is the first work employing NVCiM to improve the edge LLM
PT performance.

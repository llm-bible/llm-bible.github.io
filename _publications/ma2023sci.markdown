---
layout: publication
title: 'Sci-cot: Leveraging Large Language Models For Enhanced Knowledge Distillation In Small Models For Scientific QA'
authors: Ma Yuhan, Jiang Haiqi, Fan Chenyou
conference: "Arxiv"
year: 2023
bibkey: ma2023sci
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04679"}
tags: ['Distillation', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have shown outstanding performance across wide
range of downstream tasks. This competency is attributed to their substantial
parameter size and pre-training on extensive corpus. Moreover, LLMs have
exhibited enhanced reasoning capabilities in tackling complex reasoning tasks,
owing to the utilization of a method named ``Chain-of-Thought (CoT)
prompting''. This method is designed to generate intermediate reasoning steps
that guide the inference of the final answer. However, it is essential to
highlight that these advanced reasoning abilities appear to emerge in models
with a minimum of 10 billion parameters, thereby limiting its efficacy in
situations where computational resources are constrained. In this paper, we
investigate the possibility of transferring the reasoning capabilities of LLMs
to smaller models via knowledge distillation. Specifically, we propose Sci-CoT,
a two-stage framework that separates the processes of generating rationales and
inferring answers. This method enables a more efficient use of rationales
during the answer inference stage, leading to improved performance on
scientific question-answering tasks. Utilizing Sci-CoT, our 80-million
parameter model is able to exceed the performance of BLOOM-176B in the ARC-Easy
dataset under the few shot setting.

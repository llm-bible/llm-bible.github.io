---
layout: publication
title: 'Rs-moe: A Vision-language Model With Mixture Of Experts For Remote Sensing Image Captioning And Visual Question Answering'
authors: Hui Lin, Danfeng Hong, Shuhang Ge, Chuyao Luo, Kai Jiang, Hao Jin, Congcong Wen
conference: "Arxiv"
year: 2024
bibkey: lin2024rs
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.01595'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Applications', 'Prompting', 'Fine-Tuning', 'Multimodal Models', 'Pretraining Methods']
---
Remote Sensing Image Captioning (RSIC) presents unique challenges and plays a
critical role in applications. Traditional RSIC methods often struggle to
produce rich and diverse descriptions. Recently, with advancements in VLMs,
efforts have emerged to integrate these models into the remote sensing domain
and to introduce descriptive datasets specifically designed to enhance VLM
training. This paper proposes RS-MoE, a first Mixture of Expert based VLM
specifically customized for remote sensing domain. Unlike traditional MoE
models, the core of RS-MoE is the MoE Block, which incorporates a novel
Instruction Router and multiple lightweight Large Language Models (LLMs) as
expert models. The Instruction Router is designed to generate specific prompts
tailored for each corresponding LLM, guiding them to focus on distinct aspects
of the RSIC task. This design not only allows each expert LLM to concentrate on
a specific subset of the task, thereby enhancing the specificity and accuracy
of the generated captions, but also improves the scalability of the model by
facilitating parallel processing of sub-tasks. Additionally, we present a
two-stage training strategy for tuning our RS-MoE model to prevent performance
degradation due to sparsity. We fine-tuned our model on the RSICap dataset
using our proposed training strategy. Experimental results on the RSICap
dataset, along with evaluations on other traditional datasets where no
additional fine-tuning was applied, demonstrate that our model achieves
state-of-the-art performance in generating precise and contextually relevant
captions. Notably, our RS-MoE-1B variant achieves performance comparable to 13B
VLMs, demonstrating the efficiency of our model design. Moreover, our model
demonstrates promising generalization capabilities by consistently achieving
state-of-the-art performance on the Remote Sensing Visual Question Answering
(RSVQA) task.

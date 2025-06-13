---
layout: publication
title: 'Answer-me: Multi-task Open-vocabulary Visual Question Answering'
authors: Aj Piergiovanni, Wei Li, Weicheng Kuo, Mohammad Saffar, Fred Bertsch, Anelia Angelova
conference: "Arxiv"
year: 2022
bibkey: piergiovanni2022answer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2205.00949'}
tags: ['Security', 'Model Architecture', 'Applications', 'Training Techniques', 'Tools', 'Multimodal Models', 'Pre-Training']
---
We present Answer-Me, a task-aware multi-task framework which unifies a
variety of question answering tasks, such as, visual question answering, visual
entailment, visual reasoning. In contrast to previous works using contrastive
or generative captioning training, we propose a novel and simple recipe to
pre-train a vision-language joint model, which is multi-task as well. The
pre-training uses only noisy image captioning data, and is formulated to use
the entire architecture end-to-end with both a strong language encoder and
decoder. Our results show state-of-the-art performance, zero-shot
generalization, robustness to forgetting, and competitive single-task results
across a variety of question answering tasks. Our multi-task mixture training
learns from tasks of various question intents and thus generalizes better,
including on zero-shot vision-language tasks. We conduct experiments in the
challenging multi-task and open-vocabulary settings and across a variety of
datasets and tasks, such as VQA2.0, SNLI-VE, NLVR2, GQA. We observe that the
proposed approach is able to generalize to unseen tasks and that more diverse
mixtures lead to higher accuracy in both known and novel tasks.

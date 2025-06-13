---
layout: publication
title: 'Give Me Some Hard Questions: Synthetic Data Generation For Clinical QA'
authors: Fan Bai, Keith Harrigian, Joel Stremmel, Hamid Hassanzadeh, Ardavan Saeedi, Mark Dredze
conference: "Arxiv"
year: 2024
bibkey: bai2024give
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04573"}
tags: ['Fine-Tuning', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Clinical Question Answering (QA) systems enable doctors to quickly access
patient information from electronic health records (EHRs). However, training
these systems requires significant annotated data, which is limited due to the
expertise needed and the privacy concerns associated with clinical data. This
paper explores generating Clinical QA data using large language models (LLMs)
in a zero-shot setting. We find that naive prompting often results in easy
questions that do not reflect the complexity of clinical scenarios. To address
this, we propose two prompting strategies: 1) instructing the model to generate
questions that do not overlap with the input context, and 2) summarizing the
input record using a predefined schema to scaffold question generation.
Experiments on two Clinical QA datasets demonstrate that our method generates
more challenging questions, significantly improving fine-tuning performance
over baselines. We compare synthetic and gold data and find a gap between their
training efficacy resulting from the quality of synthetically generated
answers.

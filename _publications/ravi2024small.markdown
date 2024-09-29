---
layout: publication
title: 'Small But Funny: A Feedback-driven Approach To Humor Distillation'
authors: Ravi Sahithya, Huber Patrick, Shrivastava Akshat, Sagar Aditya, Aly Ahmed, Shwartz Vered, Einolghozati Arash
conference: "Arxiv"
year: 2024
bibkey: ravi2024small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18113"}
tags: ['Distillation', 'Efficiency And Optimization', 'Reinforcement Learning']
---
The emergence of Large Language Models (LLMs) has brought to light promising language generation capabilities particularly in performing tasks like complex reasoning and creative writing. Consequently distillation through imitation of teacher responses has emerged as a popular technique to transfer knowledge from LLMs to more accessible Small Language Models (SLMs). While this works well for simpler tasks there is a substantial performance gap on tasks requiring intricate language comprehension and creativity such as humor generation. We hypothesize that this gap may stem from the fact that creative tasks might be hard to learn by imitation alone and explore whether an approach involving supplementary guidance from the teacher could yield higher performance. To address this we study the effect of assigning a dual role to the LLM - as a teacher generating data as well as a critic evaluating the students performance. Our experiments on humor generation reveal that the incorporation of feedback significantly narrows the performance gap between SLMs and their larger counterparts compared to merely relying on imitation. As a result our research highlights the potential of using feedback as an additional dimension to data when transferring complex language abilities via distillation.

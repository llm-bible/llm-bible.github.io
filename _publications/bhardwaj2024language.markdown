---
layout: publication
title: Language Models Are Homer Simpson! Safety Re-alignment Of Fine-tuned Language Models Through Task Arithmetic
authors: Bhardwaj Rishabh, Anh Do Duc, Poria Soujanya
conference: "Arxiv"
year: 2024
bibkey: bhardwaj2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11746"}
  - {name: "Code", url: "https://github.com/declare-lab/resta"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Responsible AI', 'Training Techniques']
---
Aligned language models face a significant limitation as their fine-tuning often results in compromised safety. To tackle this we propose a simple method RESTA that performs LLM safety realignment. RESTA stands for REstoring Safety through Task Arithmetic. At its core it involves a simple arithmetic addition of a safety vector to the weights of the compromised model. We demonstrate the effectiveness of RESTA in both parameter-efficient and full fine-tuning covering a wide range of downstream tasks including instruction following in Chinese English and Hindi as well as problem-solving capabilities in Code and Math. We also showcase the generalizability of RESTA on three existing safety evaluation benchmarks and a multilingual benchmark dataset proposed as a part of this work consisting of 550 harmful questions covering 11 categories each with 5 sub-categories of harm. Overall RESTA decreases the harmfulness of the compromised model from 18.637; to 5.137; and from 9.237; to 1.537; in parameter-efficient and full fine-tuning respectively while maintaining most of the models performance on the task. We release the source codes at https://github.com/declare-lab/resta."

---
layout: publication
title: 'Investigating Continual Pretraining In Large Language Models: Insights And Implications'
authors: Çağatay Yıldız, Nishaanth Kanna Ravichandran, Nitin Sharma, Matthias Bethge, Beyza Ermis
conference: "Arxiv"
year: 2024
bibkey: yıldız2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17400"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Continual learning (CL) in large language models (LLMs) is an evolving domain
that focuses on developing efficient and sustainable training strategies to
adapt models to emerging knowledge and achieve robustness in dynamic
environments. Our primary emphasis is on continual domain-adaptive pretraining,
a process designed to equip LLMs with the ability to integrate new information
from various domains while retaining previously learned knowledge. Since
existing works concentrate mostly on continual fine-tuning for a limited
selection of downstream tasks or training domains, we introduce a new benchmark
designed to measure the adaptability of LLMs to changing pretraining data
landscapes. We further examine the impact of model size on learning efficacy
and forgetting, as well as how the progression and similarity of emerging
domains affect the knowledge transfer within these models.
  Our findings uncover several key insights: (i) continual pretraining
consistently improves <1.5B models studied in this work and is also superior to
domain adaptation, (ii) larger models always achieve better perplexity than
smaller ones when continually pretrained on the same corpus, (iii) smaller
models are particularly sensitive to continual pretraining, showing the most
significant rates of both learning and forgetting, (iv) continual pretraining
boosts downstream task performance of GPT-2 family, (v) continual pretraining
enables LLMs to specialize better when the sequence of domains shows semantic
similarity while randomizing training domains leads to better transfer and
final performance otherwise. We posit that our research establishes a new
benchmark for CL in LLMs, providing a more realistic evaluation of knowledge
retention and transfer across diverse domains.

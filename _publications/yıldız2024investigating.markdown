---
layout: publication
title: Investigating Continual Pretraining In Large Language Models: Insights And Implications
authors: Yıldız Çağatay, Ravichandran Nishaanth Kanna, Punia Prishruit, Bethge Matthias, Ermis Beyza
conference: "Arxiv"
year: 2024
bibkey: yıldız2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17400"}
tags: ['Fine Tuning', 'Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
This paper studies the evolving domain of Continual Learning (CL) in large language models (LLMs) with a focus on developing strategies for efficient and sustainable training. Our primary emphasis is on continual domain-adaptive pretraining a process designed to equip LLMs with the ability to integrate new information from various domains while retaining previously learned knowledge and enhancing cross-domain knowledge transfer without relying on domain-specific identification. Unlike previous studies which mostly concentrate on a limited selection of tasks or domains and primarily aim to address the issue of forgetting our research evaluates the adaptability and capabilities of LLMs to changing data landscapes in practical scenarios. To this end we introduce a new benchmark designed to measure the adaptability of LLMs to these evolving data environments offering a comprehensive framework for evaluation. We examine the impact of model size on learning efficacy and forgetting as well as how the progression and similarity of emerging domains affect the knowledge transfer within these models. Our findings uncover several key insights (i) when the sequence of domains shows semantic similarity continual pretraining enables LLMs to better specialize in the current domain compared to stand-alone fine-tuning (ii) training across a diverse range of domains enhances both backward and forward knowledge transfer and (iii) smaller models are particularly sensitive to continual pretraining showing the most significant rates of both forgetting and learning. We posit that our research marks a shift towards establishing a more realistic benchmark for investigating CL in LLMs and has the potential to play a key role in guiding the direction of future research in the field.

---
layout: publication
title: Investigating the Robustness of LLMs on Math Word Problems
authors: Anantheswaran Ujjwala, Gupta Himanshu, Scaria Kevin, Verma Shreyas, Baral Chitta, Mishra Swaroop
conference: "Arxiv"
year: 2024
bibkey: anantheswaran2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15444"}
tags: ['ARXIV', 'Fine Tuning', 'LLM', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) excel at various tasks including solving math word problems (MWPs) but struggle with real-world problems containing irrelevant information. To address this we propose a prompting framework that generates adversarial variants of MWPs by adding irrelevant variables. We introduce a dataset ProbleMATHIC containing both adversarial and non-adversarial MWPs. Our experiments reveal that LLMs are susceptible to distraction by numerical noise resulting in an average relative performance drop of ~26 on adversarial MWPs. To mitigate this we fine-tune LLMs (Llama-2 Mistral) on the adversarial samples from our dataset. Fine-tuning on adversarial training instances improves performance on adversarial MWPs by ~8 indicating increased robustness to noise and better ability to identify relevant data for reasoning. Finally to assess the generalizability of our prompting framework we introduce GSM-8K-Adv an adversarial variant of the GSM-8K benchmark. LLMs continue to struggle when faced with adversarial information reducing performance by up to ~6.

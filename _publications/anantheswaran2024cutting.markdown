---
layout: publication
title: 'Cutting Through The Noise: Boosting LLM Performance On Math Word Problems'
authors: Ujjwala Anantheswaran, Himanshu Gupta, Kevin Scaria, Shreyas Verma, Chitta Baral, Swaroop Mishra
conference: "Arxiv"
year: 2024
bibkey: anantheswaran2024cutting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15444"}
tags: ['Security', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large Language Models (LLMs) excel at various tasks, including solving math
word problems (MWPs), but struggle with real-world problems containing
irrelevant information. To address this, we propose a prompting framework that
generates adversarial variants of MWPs by adding irrelevant variables. We
introduce a dataset, PROBLEMATHIC, containing both adversarial and
non-adversarial MWPs. Our experiments reveal that LLMs are susceptible to
distraction by numerical noise, resulting in an average relative performance
drop of ~26% on adversarial MWPs. To mitigate this, we fine-tune LLMs (Llama-2,
Mistral) on the adversarial samples from our dataset. Fine-tuning on
adversarial training instances improves performance on adversarial MWPs by ~8%,
indicating increased robustness to noise and improved ability to identify
relevant data for reasoning. Finally, to assess the generalizability of our
prompting framework, we introduce GSM-8K-Adv, an adversarial variant of the
GSM-8K benchmark. LLMs continue to struggle when faced with adversarial
information, reducing performance by up to 6%.

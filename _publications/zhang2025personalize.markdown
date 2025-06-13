---
layout: publication
title: 'Personalize Your LLM: Fake It Then Align It'
authors: Yijing Zhang, Dyah Adila, Changho Shin, Frederic Sala
conference: "Arxiv"
year: 2025
bibkey: zhang2025personalize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01048"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Personalizing large language models (LLMs) is essential for delivering
tailored interactions that improve user experience. Many existing
personalization methods require fine-tuning LLMs for each user, rendering them
prohibitively expensive for widespread adoption. Although retrieval-based
approaches offer a more compute-efficient alternative, they still depend on
large, high-quality datasets that are not consistently available for all users.
To address this challenge, we propose CHAMELEON, a scalable and efficient
personalization approach that uses (1) self-generated personal preference data
and (2) representation editing to enable quick and cost-effective
personalization. Our experiments on various tasks, including those from the
LaMP personalization benchmark, show that CHAMELEON efficiently adapts models
to personal preferences, improving instruction-tuned models and outperforms two
personalization baselines by an average of 40% across two model architectures.

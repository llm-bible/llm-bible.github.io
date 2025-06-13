---
layout: publication
title: 'Sculpting Subspaces: Constrained Full Fine-tuning In Llms For Continual Learning'
authors: Nikhil Shivakumar Nayak, Krishnateja Killamsetty, Ligong Han, Abhishek Bhandwaldar, Prateek Chanda, Kai Xu, Hao Wang, Aldo Pareja, Oleg Silkin, Mustafa Eyceoz, Akash Srivastava
conference: "Arxiv"
year: 2025
bibkey: nayak2025sculpting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.07097'}
tags: ['RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Responsible AI', 'Pretraining Methods']
---
Continual learning in large language models (LLMs) is prone to catastrophic
forgetting, where adapting to new tasks significantly degrades performance on
previously learned ones. Existing methods typically rely on low-rank,
parameter-efficient updates that limit the model's expressivity and introduce
additional parameters per task, leading to scalability issues. To address these
limitations, we propose a novel continual full fine-tuning approach leveraging
adaptive singular value decomposition (SVD). Our method dynamically identifies
task-specific low-rank parameter subspaces and constrains updates to be
orthogonal to critical directions associated with prior tasks, thus effectively
minimizing interference without additional parameter overhead or storing
previous task gradients. We evaluate our approach extensively on standard
continual learning benchmarks using both encoder-decoder (T5-Large) and
decoder-only (LLaMA-2 7B) models, spanning diverse tasks including
classification, generation, and reasoning. Empirically, our method achieves
state-of-the-art results, up to 7% higher average accuracy than recent
baselines like O-LoRA, and notably maintains the model's general linguistic
capabilities, instruction-following accuracy, and safety throughout the
continual learning process by reducing forgetting to near-negligible levels.
Our adaptive SVD framework effectively balances model plasticity and knowledge
retention, providing a practical, theoretically grounded, and computationally
scalable solution for continual learning scenarios in large language models.

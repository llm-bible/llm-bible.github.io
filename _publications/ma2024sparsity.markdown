---
layout: publication
title: 'Sparsity-accelerated Training For Large Language Models'
authors: Ma Da, Chen Lu, Wang Pengyu, Xu Hongshen, Li Hanqi, Sun Liangtai, Zhu Su, Fan Shuai, Yu Kai
conference: "Arxiv"
year: 2024
bibkey: ma2024sparsity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01392"}
  - {name: "Code", url: "https://github.com/OpenDFM/SAT"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
"Large language models (LLMs) have demonstrated proficiency across various natural language processing (NLP) tasks but often require additional training, such as continual pre-training and supervised fine-tuning. However, the costs associated with this, primarily due to their large parameter count, remain high. This paper proposes leveraging \emph\{sparsity\} in pre-trained LLMs to expedite this training process. By observing sparsity in activated neurons during forward iterations, we identify the potential for computational speed-ups by excluding inactive neurons. We address associated challenges by extending existing neuron importance evaluation metrics and introducing a ladder omission rate scheduler. Our experiments on Llama-2 demonstrate that Sparsity-Accelerated Training (SAT) achieves comparable or superior performance to standard training while significantly accelerating the process. Specifically, SAT achieves a \(45\%\) throughput improvement in continual pre-training and saves \(38\%\) training time in supervised fine-tuning in practice. It offers a simple, hardware-agnostic, and easily deployable framework for additional LLM training. Our code is available at https://github.com/OpenDFM/SAT."

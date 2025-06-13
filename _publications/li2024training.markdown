---
layout: publication
title: 'Training Dynamics Of A 1.7B Llama Model: A Data-efficient Approach'
authors: Miles Q. Li, Benjamin C. M. Fung, Shih-chia Huang
conference: "Arxiv"
year: 2024
bibkey: li2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13335"}
  - {name: "Code", url: "https://github.com/McGill-DMaS/DMaS-LLaMa-Lite-Training-Code"}
  - {name: "Code", url: "https://huggingface.co/collections/McGill-DMaS/dmas-llama-lite-6761d97ba903f82341954ceb"}
tags: ['Training Techniques', 'Has Code', 'Model Architecture', 'Pretraining Methods']
---
Pretraining large language models is a complex endeavor influenced by
multiple factors, including model architecture, data quality, training
continuity, and hardware constraints. In this paper, we share insights gained
from the experience of training DMaS-LLaMa-Lite, a fully open source,
1.7-billion-parameter, LLaMa-based model, on approximately 20 billion tokens of
carefully curated data. We chronicle the full training trajectory, documenting
how evolving validation loss levels and downstream benchmarks reflect
transitions from incoherent text to fluent, contextually grounded output.
Beyond pretraining, we extend our analysis to include a post-training phase
focused on instruction tuning, where the model was refined to produce more
contextually appropriate, user-aligned responses. We highlight practical
considerations such as the importance of restoring optimizer states when
resuming from checkpoints, and the impact of hardware changes on training
stability and throughput. While qualitative evaluation provides an intuitive
understanding of model improvements, our analysis extends to various
performance benchmarks, demonstrating how high-quality data and thoughtful
scaling enable competitive results with significantly fewer training tokens. By
detailing these experiences and offering training logs, checkpoints, and sample
outputs, we aim to guide future researchers and practitioners in refining their
pretraining strategies. The training script is available on Github at
https://github.com/McGill-DMaS/DMaS-LLaMa-Lite-Training-Code. The model
checkpoints are available on Huggingface at
https://huggingface.co/collections/McGill-DMaS/dmas-llama-lite-6761d97ba903f82341954ceb.

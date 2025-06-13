---
layout: publication
title: 'Seed-free Synthetic Data Generation Framework For Instruction-tuning Llms: A Case Study In Thai'
authors: Parinthapat Pengpun, Can Udomcharoenchaikit, Weerayut Buaphet, Peerat Limkonchotiwat
conference: "Arxiv"
year: 2024
bibkey: pengpun2024seed
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.15484'}
  - {name: "Code", url: 'https://github.com/parinzee/seed-free-synthetic-instruct'}
tags: ['Fine-Tuning', 'Has Code', 'Applications', 'Tools']
---
We present a synthetic data approach for instruction-tuning large language
models (LLMs) for low-resource languages in a data-efficient manner,
specifically focusing on Thai. We identify three key properties that contribute
to the effectiveness of instruction-tuning datasets: fluency, diversity, and
cultural context. We propose a seed-data-free framework for generating
synthetic instruction-tuning data that incorporates these essential properties.
Our framework employs an LLM to generate diverse topics, retrieve relevant
contexts from Wikipedia, and create instructions for various tasks, such as
question answering, summarization, and conversation. The experimental results
show that our best-performing synthetic dataset, which incorporates all three
key properties, achieves competitive performance using only 5,000 instructions
when compared to state-of-the-art Thai LLMs trained on hundreds of thousands of
instructions. Our code and dataset are publicly available at
https://github.com/parinzee/seed-free-synthetic-instruct.

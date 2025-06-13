---
layout: publication
title: 'LESS: Selecting Influential Data For Targeted Instruction Tuning'
authors: Mengzhou Xia, Sadhika Malladi, Suchin Gururangan, Sanjeev Arora, Danqi Chen
conference: "Arxiv"
year: 2024
bibkey: xia2024selecting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.04333'}
tags: ['Few-Shot', 'RAG', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
Instruction tuning has unlocked powerful capabilities in large language
models (LLMs), effectively using combined datasets to develop generalpurpose
chatbots. However, real-world applications often require a specialized suite of
skills (e.g., reasoning). The challenge lies in identifying the most relevant
data from these extensive datasets to effectively develop specific
capabilities, a setting we frame as targeted instruction tuning. We propose
LESS, an optimizer-aware and practically efficient algorithm to effectively
estimate data influences and perform Low-rank gradiEnt Similarity Search for
instruction data selection. Crucially, LESS adapts existing influence
formulations to work with the Adam optimizer and variable-length instruction
data. LESS first constructs a highly reusable and transferable gradient
datastore with low-dimensional gradient features and then selects examples
based on their similarity to few-shot examples embodying a specific capability.
Experiments show that training on a LESS-selected 5% of the data can often
outperform training on the full dataset across diverse downstream tasks.
Furthermore, the selected data is highly transferable: smaller models can be
leveraged to select useful data for larger models and models from different
families. Our qualitative analysis shows that our method goes beyond surface
form cues to identify data that exemplifies the necessary reasoning skills for
the intended downstream application.

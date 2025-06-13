---
layout: publication
title: 'Instruction Tuning Vs. In-context Learning: Revisiting Large Language Models In Few-shot Computational Social Science'
authors: Taihang Wang, Xiaoman Xu, Yimin Wang, Ye Jiang
conference: "Arxiv"
year: 2024
bibkey: wang2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14673"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Real-world applications of large language models (LLMs) in computational
social science (CSS) tasks primarily depend on the effectiveness of instruction
tuning (IT) or in-context learning (ICL). While IT has shown highly effective
at fine-tuning LLMs for various tasks, ICL offers a rapid alternative for task
adaptation by learning from examples without explicit gradient updates. In this
paper, we evaluate the classification performance of LLMs using IT versus ICL
in few-shot CSS tasks. The experimental results indicate that ICL consistently
outperforms IT in most CSS tasks. Additionally, we investigate the relationship
between the increasing number of training samples and LLM performance. Our
findings show that simply increasing the number of samples without considering
their quality does not consistently enhance the performance of LLMs with either
ICL or IT and can sometimes even result in a performance decline. Finally, we
compare three prompting strategies, demonstrating that ICL is more effective
than zero-shot and Chain-of-Thought (CoT). Our research highlights the
significant advantages of ICL in handling CSS tasks in few-shot settings and
emphasizes the importance of optimizing sample quality and prompting strategies
to improve LLM classification performance. The code will be made available.

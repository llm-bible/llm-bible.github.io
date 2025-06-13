---
layout: publication
title: 'Meta Prompting For AI Systems'
authors: Yifan Zhang, Yang Yuan, Andrew Chi-chih Yao
conference: "Arxiv"
year: 2023
bibkey: zhang2023meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11482"}
  - {name: "Code", url: "https://github.com/meta-prompting/meta-prompting"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Few-Shot', 'Tools', 'GPT', 'Has Code', 'Prompting', 'Applications', 'In-Context Learning']
---
We introduce Meta Prompting (MP), a prompting paradigm designed to enhance
the utilization of large language models (LLMs) and AI systems in complex
problem-solving and data interaction. Grounded in type theory and category
theory, Meta Prompting prioritizes structural and syntactical considerations
over traditional content-centric methods. In this work, we formally define Meta
Prompting, delineate its distinctions from few-shot prompting, and demonstrate
its effectiveness across various AI applications. In particular, we show that
Meta Prompting can decompose intricate reasoning tasks into simpler
sub-problems, thereby improving token efficiency and enabling fairer
comparisons with conventional few-shot techniques. Furthermore, we extend this
framework to prompting tasks, allowing LLMs to recursively self-generate
refined prompts in a metaprogramming-like manner. Empirical evaluations reveal
that a Qwen-72B base language model equipped with Meta Prompting-without
additional instruction tuning-achieves a PASS@1 accuracy of 46.3% on MATH
problems, surpassing a supervised fine-tuned counterpart, 83.5% accuracy on
GSM8K, and a 100% success rate on Game of 24 tasks using GPT-4. The code is
available at https://github.com/meta-prompting/meta-prompting.

---
layout: publication
title: 'RAM2C: A Liberal Arts Educational Chatbot Based On Retrieval-augmented Multi-role Multi-expert Collaboration'
authors: Haoyu Huang, Tong Niu, Rui Yang, Luping Shi
conference: "Arxiv"
year: 2024
bibkey: huang2024liberal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.15461'}
  - {name: "Code", url: 'https://github.com/ram2c/ram2c}{https://github.com/ram2c/ram2c'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Responsible AI']
---
Recently, many studies focus on utilizing large language models (LLMs) into
educational dialogues. Especially, within liberal arts dialogues, educators
must balance \textbf\{H\}umanized communication, \textbf\{T\}eaching expertise, and
\textbf\{S\}afety-ethics (\textbf\{HTS\}), besides the subject knowledge itself.
However, due to collecting massive amounts of HTS-compliant teaching dialogues
from real world as training corpus is expensive, the outputs of existing LLMs
in teaching dialogues fall short of human standards. To address this, we design
a Retrieval-augmented Multi-role Multi-expert Collaboration (RAM2C) framework
to automatically generate such dialogues data. Specifically, we first establish
HTS-guided knowledge bases, encompassing three domain knowledge in teaching
skills, psychology, and safety ethics. Then, RAM2C organizes LLMs, which are
retrieval-augmented by the above different knowledge bases, into multi-experts
groups with distinct roles to generate the HTS-compliant educational dialogues
dataset. We then fine-tuned the LLMs using this dataset. Empirical evaluations
indicate that RM2C-empowered LLMs excel in Chinese reading teaching, offering
more personalized, and ethically safe teaching response, demonstrating RAM2C's
practicality and high quality. We release the experiments at
\hyperlink\{https://github.com/ram2c/ram2c\}\{https://github.com/ram2c/ram2c\}.

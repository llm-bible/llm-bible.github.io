---
layout: publication
title: 'Smaller Large Language Models Can Do Moral Self-correction'
authors: Guangliang Liu, Zhiyu Xue, Xitong Zhang, Rongrong Wang, Kristen Marie Johnson
conference: "Arxiv"
year: 2024
bibkey: liu2024smaller
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23496"}
tags: ['Fine-Tuning', 'Responsible AI', 'Ethics and Bias', 'Interpretability and Explainability', 'Language Modeling', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Self-correction is one of the most amazing emerging capabilities of Large
Language Models (LLMs), enabling LLMs to self-modify an inappropriate output
given a natural language feedback which describes the problems of that output.
Moral self-correction is a post-hoc approach correcting unethical generations
without requiring a gradient update, making it both computationally lightweight
and capable of preserving the language modeling ability. Previous works have
shown that LLMs can self-debias, and it has been reported that small models,
i.e., those with less than 22B parameters, are not capable of moral
self-correction. However, there is no direct proof as to why such smaller
models fall short of moral self-correction, though previous research
hypothesizes that larger models are skilled in following instructions and
understanding abstract social norms. In this paper, we empirically validate
this hypothesis in the context of social stereotyping, through meticulous
prompting. Our experimental results indicate that (i) surprisingly, 3.8B LLMs
with proper safety alignment fine-tuning can achieve very good moral
self-correction performance, highlighting the significant effects of safety
alignment; and (ii) small LLMs are indeed weaker than larger-scale models in
terms of comprehending social norms and self-explanation through CoT, but all
scales of LLMs show bad self-correction performance given unethical
instructions.

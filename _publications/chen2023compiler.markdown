---
layout: publication
title: Compcodevet: A Compiler-guided Validation And Enhancement Approach For Code Dataset
authors: Chen Le, Bhattacharjee Arijit, Ahmed Nesreen K., Hasabnis Niranjan, Oren Gal, Lei Bin, Jannesari Ali
conference: "Arxiv"
year: 2023
bibkey: chen2023compiler
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.06505"}
tags: ['Applications', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) have become increasingly prominent in academia and industry due to their remarkable performance in diverse applications. As these models evolve with increasing parameters they excel in tasks like sentiment analysis and machine translation. However even models with billions of parameters face challenges in tasks demanding multi-step reasoning. Code generation and comprehension especially in C and C++ emerge as significant challenges. While LLMs trained on code datasets demonstrate competence in many tasks they struggle with rectifying non-compilable C and C++ code. Our investigation attributes this subpar performance to two primary factors the quality of the training dataset and the inherent complexity of the problem which demands intricate reasoning. Existing Chain of Thought (CoT) prompting techniques aim to enhance multi-step reasoning. This approach however retains the limitations associated with the latent drawbacks of LLMs. In this work we propose CompCodeVet a compiler-guided CoT approach to produce compilable code from non-compilable ones. Diverging from the conventional approach of utilizing larger LLMs we employ compilers as a teacher to establish a more robust zero-shot thought process. The evaluation of CompCodeVet on two open-source code datasets shows that CompCodeVet has the ability to improve the training dataset quality for LLMs.

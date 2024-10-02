---
layout: publication
title: 'Developing Safe And Responsible Large Language Model : Can We Balance Bias Reduction And Language Understanding In Large Language Models?'
authors: Raza Shaina, Bamgbose Oluwanifemi, Ghuge Shardul, Tavakol Fatemeh, Reji Deepak John, Bashir Syed Raza
conference: "Arxiv"
year: 2024
bibkey: raza2024developing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01399"}
  - {name: "Code", url: "https://github.com/shainarazavi/Safe-Responsible-LLM}{SR-LLM"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'Has Code', 'Language Modeling', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
'Large Language Models (LLMs) have advanced various Natural Language Processing (NLP) tasks, such as text generation and translation, among others. However, these models often generate text that can perpetuate biases. Existing approaches to mitigate these biases usually compromise knowledge retention. This study explores whether LLMs can produce safe, unbiased outputs without sacrificing knowledge or comprehension. We introduce the Safe and Responsible Large Language Model (\textbf\{SR\}\(_{\text{LLM}}\)), which has been instruction fine-tuned atop an inherently safe fine-tuned LLM to reduce biases in generated texts. We developed a specialized dataset with examples of unsafe and corresponding safe variations to train \textbf\{SR\}\(_{\text{LLM}}\) to identify and correct biased text. Experiments on our specialized dataset and out-of-distribution test sets reveal that \textbf\{SR\}\(_{\text{LLM}}\) effectively reduces biases while preserving knowledge integrity. This performance surpasses that of traditional fine-tuning of smaller language models and base LLMs that merely reply on prompting techniques. Our findings indicate that instruction fine-tuning is an effective strategy for minimizing bias in LLMs while retaining knowledge. The code and dataset are accessible at \href\{https://github.com/shainarazavi/Safe-Responsible-LLM\}\{SR-LLM\}.'

---
layout: publication
title: 'Developing Safe And Responsible Large Language Model : Can We Balance Bias Reduction And Language Understanding In Large Language Models?'
authors: Shaina Raza, Oluwanifemi Bamgbose, Shardul Ghuge, Fatemeh Tavakol, Deepak John Reji, Syed Raza Bashir
conference: "Arxiv"
year: 2024
bibkey: raza2024developing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.01399'}
  - {name: "Code", url: 'https://github.com/shainarazavi/Safe-Responsible-LLM}{SR-LLM'}
tags: ['Has Code', 'Language Modeling', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Ethics and Bias', 'Pretraining Methods']
---
Large Language Models (LLMs) have advanced various Natural Language
Processing (NLP) tasks, such as text generation and translation, among others.
However, these models often generate texts that can perpetuate biases. Existing
approaches to mitigate these biases usually compromise knowledge retention.
This study explores whether LLMs can produce safe, unbiased outputs without
sacrificing knowledge or comprehension. We introduce the Safe and Responsible
Large Language Model (\textbf\{SR\}\\(_\{\text\{LLM\}\}\\)), which has been instruction
fine-tuned atop of a safe fine-tuned auto-regressive decoder-only LLM to reduce
biases in generated texts. We developed a specialized dataset with examples of
unsafe and corresponding safe variations to train \textbf\{SR\}\\(_\{\text\{LLM\}\}\\) to
identify and correct biased text. Experiments on our specialized dataset and
out-of-distribution test sets reveal that \textbf\{SR\}\\(_\{\text\{LLM\}\}\\)
effectively reduces biases while preserving knowledge integrity. This
performance surpasses that of traditional fine-tuning of smaller language
models and base LLMs that merely reply on prompting techniques. Our findings
demonstrate that instruction fine-tuning on custom datasets tailored for tasks
such as debiasing is a highly effective strategy for minimizing bias in LLM
while preserving their inherent knowledge and capabilities. The code and
dataset are accessible at
\href\{https://github.com/shainarazavi/Safe-Responsible-LLM\}\{SR-LLM\}

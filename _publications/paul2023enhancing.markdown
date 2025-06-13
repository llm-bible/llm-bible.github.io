---
layout: publication
title: 'Enhancing Automated Program Repair Through Fine-tuning And Prompt Engineering'
authors: Rishov Paul, Md. Mohib Hossain, Mohammed Latif Siddiq, Masum Hasan, Anindya Iqbal, Joanna C. S. Santos
conference: "Arxiv"
year: 2023
bibkey: paul2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.07840"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'Survey Paper', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Sequence-to-sequence models have been used to transform erroneous programs
into correct ones when trained with a large enough dataset. Some recent studies
also demonstrated strong empirical evidence that code review could improve the
program repair further. Large language models, trained with Natural Language
(NL) and Programming Language (PL), can contain inherent knowledge of both. In
this study, we investigate if this inherent knowledge of PL and NL can be
utilized to improve automated program repair. We applied PLBART and CodeT5, two
state-of-the-art language models that are pre-trained with both PL and NL, on
two such natural language-based program repair datasets and found that the
pre-trained language models fine-tuned with datasets containing both code
review and subsequent code changes notably outperformed each of the previous
models. With the advent of code generative models like Codex and GPT-3.5-Turbo,
we also performed zero-shot and few-shots learning-based prompt engineering to
assess their performance on these datasets. However, the practical application
of using LLMs in the context of automated program repair is still a long way
off based on our manual analysis of the generated repaired codes by the
learning models.

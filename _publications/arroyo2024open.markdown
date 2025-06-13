---
layout: publication
title: 'Open (clinical) Llms Are Sensitive To Instruction Phrasings'
authors: Alberto Mario Ceballos Arroyo, Monica Munnangi, Jiuding Sun, Karen Y. C. Zhang, Denis Jered Mcinerney, Byron C. Wallace, Silvio Amir
conference: "Arxiv"
year: 2024
bibkey: arroyo2024open
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.09429'}
tags: ['Security', 'Fairness', 'Prompting', 'Bias Mitigation', 'Ethics and Bias']
---
Instruction-tuned Large Language Models (LLMs) can perform a wide range of
tasks given natural language instructions to do so, but they are sensitive to
how such instructions are phrased. This issue is especially concerning in
healthcare, as clinicians are unlikely to be experienced prompt engineers and
the potential consequences of inaccurate outputs are heightened in this domain.
  This raises a practical question: How robust are instruction-tuned LLMs to
natural variations in the instructions provided for clinical NLP tasks? We
collect prompts from medical doctors across a range of tasks and quantify the
sensitivity of seven LLMs -- some general, others specialized -- to natural
(i.e., non-adversarial) instruction phrasings. We find that performance varies
substantially across all models, and that -- perhaps surprisingly --
domain-specific models explicitly trained on clinical data are especially
brittle, compared to their general domain counterparts. Further, arbitrary
phrasing differences can affect fairness, e.g., valid but distinct instructions
for mortality prediction yield a range both in overall performance, and in
terms of differences between demographic groups.

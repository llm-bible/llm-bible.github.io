---
layout: publication
title: 'Llms And Memorization: On Quality And Specificity Of Copyright Compliance'
authors: Felix B Mueller, Rebekka Görge, Anna K Bernzen, Janna C Pirk, Maximilian Poretschkin
conference: "Proceedings of the AAAI/ACM Conference on AI Ethics and Society 7(1) 984-996 2024"
year: 2024
bibkey: mueller2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18492"}
  - {name: "Code", url: "https://github.com/felixbmuller/llms-memorization-copyright"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Has Code']
---
Memorization in large language models (LLMs) is a growing concern. LLMs have
been shown to easily reproduce parts of their training data, including
copyrighted work. This is an important problem to solve, as it may violate
existing copyright laws as well as the European AI Act. In this work, we
propose a systematic analysis to quantify the extent of potential copyright
infringements in LLMs using European law as an example. Unlike previous work,
we evaluate instruction-finetuned models in a realistic end-user scenario. Our
analysis builds on a proposed threshold of 160 characters, which we borrow from
the German Copyright Service Provider Act and a fuzzy text matching algorithm
to identify potentially copyright-infringing textual reproductions. The
specificity of countermeasures against copyright infringement is analyzed by
comparing model behavior on copyrighted and public domain data. We investigate
what behaviors models show instead of producing protected text (such as refusal
or hallucination) and provide a first legal assessment of these behaviors. We
find that there are huge differences in copyright compliance, specificity, and
appropriate refusal among popular LLMs. Alpaca, GPT 4, GPT 3.5, and Luminous
perform best in our comparison, with OpenGPT-X, Alpaca, and Luminous producing
a particularly low absolute number of potential copyright violations. Code can
be found at https://github.com/felixbmuller/llms-memorization-copyright.

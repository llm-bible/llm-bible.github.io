---
layout: publication
title: 'Analyzing The Safety Of Japanese Large Language Models In Stereotype-triggering Prompts'
authors: Akito Nakanishi, Yukie Sano, Geng Liu, Francesco Pierri
conference: "Arxiv"
year: 2025
bibkey: nakanishi2025analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01947"}
tags: ['Responsible AI', 'Tools', 'Ethics and Bias', 'Bias Mitigation', 'Reinforcement Learning', 'Prompting']
---
In recent years, Large Language Models have attracted growing interest for
their significant potential, though concerns have rapidly emerged regarding
unsafe behaviors stemming from inherent stereotypes and biases. Most research
on stereotypes in LLMs has primarily relied on indirect evaluation setups, in
which models are prompted to select between pairs of sentences associated with
particular social groups. Recently, direct evaluation methods have emerged,
examining open-ended model responses to overcome limitations of previous
approaches, such as annotator biases. Most existing studies have focused on
English-centric LLMs, whereas research on non-English models, particularly
Japanese, remains sparse, despite the growing development and adoption of these
models. This study examines the safety of Japanese LLMs when responding to
stereotype-triggering prompts in direct setups. We constructed 3,612 prompts by
combining 301 social group terms, categorized by age, gender, and other
attributes, with 12 stereotype-inducing templates in Japanese. Responses were
analyzed from three foundational models trained respectively on Japanese,
English, and Chinese language. Our findings reveal that LLM-jp, a Japanese
native model, exhibits the lowest refusal rate and is more likely to generate
toxic and negative responses compared to other models. Additionally, prompt
format significantly influence the output of all models, and the generated
responses include exaggerated reactions toward specific social groups, varying
across models. These findings underscore the insufficient ethical safety
mechanisms in Japanese LLMs and demonstrate that even high-accuracy models can
produce biased outputs when processing Japanese-language prompts. We advocate
for improving safety mechanisms and bias mitigation strategies in Japanese
LLMs, contributing to ongoing discussions on AI ethics beyond linguistic
boundaries.

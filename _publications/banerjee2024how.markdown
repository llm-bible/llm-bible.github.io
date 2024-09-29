---
layout: publication
title: How (un)ethical Are Instruction45;centric Responses Of Llms Unveiling The Vulnerabilities Of Safety Guardrails To Harmful Queries
authors: Banerjee Somnath, Layek Sayan, Hazra Rima, Mukherjee Animesh
conference: "Arxiv"
year: 2024
bibkey: banerjee2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15302"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Responsible AI']
---
In this study we tackle a growing concern around the safety and ethical use of large language models (LLMs). Despite their potential these models can be tricked into producing harmful or unethical content through various sophisticated methods including jailbreaking techniques and targeted manipulation. Our work zeroes in on a specific issue to what extent LLMs can be led astray by asking them to generate responses that are instruction45;centric such as a pseudocode a program or a software snippet as opposed to vanilla text. To investigate this question we introduce TechHazardQA a dataset containing complex queries which should be answered in both text and instruction45;centric formats (e.g. pseudocodes) aimed at identifying triggers for unethical responses. We query a series of LLMs 45;45; Llama45;245;13b Llama45;245;7b Mistral45;V2 and Mistral 8X7B 45;45; and ask them to generate both text and instruction45;centric responses. For evaluation we report the harmfulness score metric as well as judgements from GPT45;4 and humans. Overall we observe that asking LLMs to produce instruction45;centric responses enhances the unethical response generation by ~245;3837; across the models. As an additional objective we investigate the impact of model editing using the ROME technique which further increases the propensity for generating undesirable content. In particular asking edited LLMs to generate instruction45;centric responses further increases the unethical response generation by ~345;1637; across the different models.

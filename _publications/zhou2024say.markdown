---
layout: publication
title: Dont Say No Jailbreaking LLM By Suppressing Refusal
authors: Zhou Yukai, Wang Wenjie
conference: "Arxiv"
year: 2024
bibkey: zhou2024say
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16369"}
tags: ['Ethics And Bias', 'Prompting', 'Responsible AI', 'Security']
---
Ensuring the safety alignment of Large Language Models (LLMs) is crucial to generating responses consistent with human values. Despite their ability to recognize and avoid harmful queries LLMs are vulnerable to jailbreaking attacks where carefully crafted prompts elicit them to produce toxic content. One category of jailbreak attacks is reformulating the task as adversarial attacks by eliciting the LLM to generate an affirmative response. However the typical attack in this category GCG has very limited attack success rate. In this study to better study the jailbreak attack we introduce the DSN (Dont Say No) attack which prompts LLMs to not only generate affirmative responses but also novelly enhance the objective to suppress refusals. In addition another challenge lies in jailbreak attacks is the evaluation as it is difficult to directly and accurately assess the harmfulness of the attack. The existing evaluation such as refusal keyword matching has its own limitation as it reveals numerous false positive and false negative instances. To overcome this challenge we propose an ensemble evaluation pipeline incorporating Natural Language Inference (NLI) contradiction assessment and two external LLM evaluators. Extensive experiments demonstrate the potency of the DSN and the effectiveness of ensemble evaluation compared to baseline methods.

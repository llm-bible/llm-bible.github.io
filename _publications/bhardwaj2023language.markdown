---
layout: publication
title: Language Model Unalignment Parametric Red45;teaming To Expose Hidden Harms And Biases
authors: Bhardwaj Rishabh, Poria Soujanya
conference: "Arxiv"
year: 2023
bibkey: bhardwaj2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14303"}
tags: ['Agentic', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Responsible AI', 'Security', 'Training Techniques']
---
Red45;teaming has been a widely adopted way to evaluate the harmfulness of Large Language Models (LLMs). It aims to jailbreak a models safety behavior to make it act as a helpful agent disregarding the harmfulness of the query. Existing methods are primarily based on input text45;based red45;teaming such as adversarial prompts low45;resource prompts or contextualized prompts to condition the model in a way to bypass its safe behavior. Bypassing the guardrails uncovers hidden harmful information and biases in the model that are left untreated or newly introduced by its safety training. However prompt45;based attacks fail to provide such a diagnosis owing to their low attack success rate and applicability to specific models. In this paper we present a new perspective on LLM safety research i.e. parametric red45;teaming through Unalignment. It simply (instruction) tunes the model parameters to break model guardrails that are not deeply rooted in the models behavior. Unalignment using as few as 100 examples can significantly bypass commonly referred to as CHATGPT to the point where it responds with an 8837; success rate to harmful queries on two safety benchmark datasets. On open45;source models such as VICUNA45;7B and LLAMA45;245;CHAT 7B AND 13B it shows an attack success rate of more than 9137;. On bias evaluations Unalignment exposes inherent biases in safety45;aligned models such as CHATGPT and LLAMA45; 245;CHAT where the models responses are strongly biased and opinionated 6437; of the time.

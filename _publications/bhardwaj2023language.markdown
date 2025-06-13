---
layout: publication
title: 'Language Model Unalignment: Parametric Red-teaming To Expose Hidden Harms And Biases'
authors: Rishabh Bhardwaj, Soujanya Poria
conference: "Arxiv"
year: 2023
bibkey: bhardwaj2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14303"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Training Techniques', 'Model Architecture', 'GPT', 'Ethics and Bias', 'Prompting']
---
Red-teaming has been a widely adopted way to evaluate the harmfulness of
Large Language Models (LLMs). It aims to jailbreak a model's safety behavior to
make it act as a helpful agent disregarding the harmfulness of the query.
Existing methods are primarily based on input text-based red-teaming such as
adversarial prompts, low-resource prompts, or contextualized prompts to
condition the model in a way to bypass its safe behavior. Bypassing the
guardrails uncovers hidden harmful information and biases in the model that are
left untreated or newly introduced by its safety training. However,
prompt-based attacks fail to provide such a diagnosis owing to their low attack
success rate, and applicability to specific models. In this paper, we present a
new perspective on LLM safety research i.e., parametric red-teaming through
Unalignment. It simply (instruction) tunes the model parameters to break model
guardrails that are not deeply rooted in the model's behavior. Unalignment
using as few as 100 examples can significantly bypass commonly referred to as
CHATGPT, to the point where it responds with an 88% success rate to harmful
queries on two safety benchmark datasets. On open-source models such as
VICUNA-7B and LLAMA-2-CHAT 7B AND 13B, it shows an attack success rate of more
than 91%. On bias evaluations, Unalignment exposes inherent biases in
safety-aligned models such as CHATGPT and LLAMA- 2-CHAT where the model's
responses are strongly biased and opinionated 64% of the time.

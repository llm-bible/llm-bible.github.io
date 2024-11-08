---
layout: publication
title: 'Conversational Complexity For Assessing Risk In Large Language Models'
authors: Burden John, Cebrian Manuel, Hernandez-orallo Jose
conference: "Arxiv"
year: 2024
bibkey: burden2024conversational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01247"}
tags: ['Applications', 'Reinforcement Learning', 'Responsible AI', 'Tools']
---
Large Language Models (LLMs) present a dual-use dilemma: they enable
beneficial applications while harboring potential for harm, particularly
through conversational interactions. Despite various safeguards, advanced LLMs
remain vulnerable. A watershed case was Kevin Roose's notable conversation with
Bing, which elicited harmful outputs after extended interaction. This contrasts
with simpler early jailbreaks that produced similar content more easily,
raising the question: How much conversational effort is needed to elicit
harmful information from LLMs? We propose two measures: Conversational Length
(CL), which quantifies the conversation length used to obtain a specific
response, and Conversational Complexity (CC), defined as the Kolmogorov
complexity of the user's instruction sequence leading to the response. To
address the incomputability of Kolmogorov complexity, we approximate CC using a
reference LLM to estimate the compressibility of user instructions. Applying
this approach to a large red-teaming dataset, we perform a quantitative
analysis examining the statistical distribution of harmful and harmless
conversational lengths and complexities. Our empirical findings suggest that
this distributional analysis and the minimisation of CC serve as valuable tools
for understanding AI safety, offering insights into the accessibility of
harmful information. This work establishes a foundation for a new perspective
on LLM safety, centered around the algorithmic complexity of pathways to harm.

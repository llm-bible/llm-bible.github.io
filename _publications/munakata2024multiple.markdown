---
layout: publication
title: 'A Multiple-fill-in-the-blank Exam Approach For Enhancing Zero-resource Hallucination Detection In Large Language Models'
authors: Satoshi Munakata, Taku Fukui, Takao Mohri
conference: "Arxiv"
year: 2024
bibkey: munakata2024multiple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.17173'}
tags: ['Prompting', 'Merging']
---
Large language models (LLMs) often fabricate a hallucinatory text. Several
methods have been developed to detect such text by semantically comparing it
with the multiple versions probabilistically regenerated. However, a
significant issue is that if the storyline of each regenerated text changes,
the generated texts become incomparable, which worsen detection accuracy. In
this paper, we propose a hallucination detection method that incorporates a
multiple-fill-in-the-blank exam approach to address this storyline-changing
issue. First, our method creates a multiple-fill-in-the-blank exam by masking
multiple objects from the original text. Second, prompts an LLM to repeatedly
answer this exam. This approach ensures that the storylines of the exam answers
align with the original ones. Finally, quantifies the degree of hallucination
for each original sentence by scoring the exam answers, considering the
potential for *hallucination snowballing* within the original text itself.
Experimental results show that our method alone not only outperforms existing
methods, but also achieves clearer state-of-the-art performance in the
ensembles with existing methods.

---
layout: publication
title: 'Prompt-reverse Inconsistency: LLM Self-inconsistency Beyond Generative Randomness And Prompt Paraphrasing'
authors: Jihyun Janice Ahn, Wenpeng Yin
conference: "Arxiv"
year: 2025
bibkey: ahn2025prompt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01282'}
tags: ['Prompting', 'Language Modeling', 'Applications']
---
While the inconsistency of LLMs is not a novel topic, prior research has
predominantly addressed two types of generative inconsistencies: i) Randomness
Inconsistency: running the same LLM multiple trials, yielding varying
responses; ii) Paraphrase Inconsistency: paraphrased prompts result in
different responses from the same LLM. Randomness Inconsistency arises from the
inherent randomness due to stochastic sampling in generative models, while
Paraphrase Inconsistency is a consequence of the language modeling objectives,
where paraphrased prompts alter the distribution of vocabulary logits. This
research discovers Prompt-Reverse Inconsistency (PRIN), a new form of LLM
self-inconsistency: given a question and a couple of LLM-generated answer
candidates, the LLM often has conflicting responses when prompted "Which are
correct answers?" and "Which are incorrect answers?". PRIN poses a big concern
as it undermines the credibility of LLM-as-a-judge, and suggests a challenge
for LLMs to adhere to basic logical rules. We conduct a series of experiments
to investigate PRIN, examining the extent of PRIN across different LLMs,
methods to mitigate it, potential applications, and its relationship with
Randomness Inconsistency and Paraphrase Inconsistency. As the first study to
explore PRIN, our findings offer valuable insights into the inner workings of
LLMs and contribute to advancing trustworthy AI.

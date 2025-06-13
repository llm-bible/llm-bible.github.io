---
layout: publication
title: 'Evaluating Gender Bias In Large Language Models Via Chain-of-thought Prompting'
authors: Masahiro Kaneko, Danushka Bollegala, Naoaki Okazaki, Timothy Baldwin
conference: "Arxiv"
year: 2024
bibkey: kaneko2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15585"}
tags: ['Prompting', 'Ethics and Bias', 'RAG']
---
There exist both scalable tasks, like reading comprehension and
fact-checking, where model performance improves with model size, and unscalable
tasks, like arithmetic reasoning and symbolic reasoning, where model
performance does not necessarily improve with model size. Large language models
(LLMs) equipped with Chain-of-Thought (CoT) prompting are able to make accurate
incremental predictions even on unscalable tasks. Unfortunately, despite their
exceptional reasoning abilities, LLMs tend to internalize and reproduce
discriminatory societal biases. Whether CoT can provide discriminatory or
egalitarian rationalizations for the implicit information in unscalable tasks
remains an open question.
  In this study, we examine the impact of LLMs' step-by-step predictions on
gender bias in unscalable tasks. For this purpose, we construct a benchmark for
an unscalable task where the LLM is given a list of words comprising feminine,
masculine, and gendered occupational words, and is required to count the number
of feminine and masculine words. In our CoT prompts, we require the LLM to
explicitly indicate whether each word in the word list is a feminine or
masculine before making the final predictions. With counting and handling the
meaning of words, this benchmark has characteristics of both arithmetic
reasoning and symbolic reasoning. Experimental results in English show that
without step-by-step prediction, most LLMs make socially biased predictions,
despite the task being as simple as counting words. Interestingly, CoT
prompting reduces this unconscious social bias in LLMs and encourages fair
predictions.

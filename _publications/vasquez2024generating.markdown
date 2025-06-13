---
layout: publication
title: 'Generating Diverse Negations From Affirmative Sentences'
authors: Darian Rodriguez Vasquez, Afroditi Papadaki
conference: "Arxiv"
year: 2024
bibkey: vasquez2024generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00056'}
  - {name: "Code", url: 'https://github.com/DarianRodriguez/NegVerse'}
tags: ['Has Code', 'Training Techniques', 'Applications', 'Prompting', 'Reinforcement Learning']
---
Despite the impressive performance of large language models across various
tasks, they often struggle with reasoning under negated statements. Negations
are important in real-world applications as they encode negative polarity in
verb phrases, clauses, or other expressions. Nevertheless, they are
underrepresented in current benchmarks, which mainly include basic negation
forms and overlook more complex ones, resulting in insufficient data for
training a language model. In this work, we propose NegVerse, a method that
tackles the lack of negation datasets by producing a diverse range of negation
types from affirmative sentences, including verbal, non-verbal, and affixal
forms commonly found in English text. We provide new rules for masking parts of
sentences where negations are most likely to occur, based on syntactic
structure and use a frozen baseline LLM and prompt tuning to generate negated
sentences. We also propose a filtering mechanism to identify negation cues and
remove degenerate examples, producing a diverse range of meaningful
perturbations. Our results show that NegVerse outperforms existing methods and
generates negations with higher lexical similarity to the original sentences,
better syntactic preservation and negation diversity. The code is available in
https://github.com/DarianRodriguez/NegVerse

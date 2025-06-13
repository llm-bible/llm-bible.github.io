---
layout: publication
title: 'Percul: A Story-driven Cultural Evaluation Of Llms In Persian'
authors: Erfan Moosavi Monazzah, Vahid Rahimzadeh, Yadollah Yaghoobzadeh, Azadeh Shakery, Mohammad Taher Pilehvar
conference: "Arxiv"
year: 2025
bibkey: monazzah2025story
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.07459'}
tags: ['Training Techniques']
---
Large language models predominantly reflect Western cultures, largely due to
the dominance of English-centric training data. This imbalance presents a
significant challenge, as LLMs are increasingly used across diverse contexts
without adequate evaluation of their cultural competence in non-English
languages, including Persian. To address this gap, we introduce PerCul, a
carefully constructed dataset designed to assess the sensitivity of LLMs toward
Persian culture. PerCul features story-based, multiple-choice questions that
capture culturally nuanced scenarios. Unlike existing benchmarks, PerCul is
curated with input from native Persian annotators to ensure authenticity and to
prevent the use of translation as a shortcut. We evaluate several
state-of-the-art multilingual and Persian-specific LLMs, establishing a
foundation for future research in cross-cultural NLP evaluation. Our
experiments demonstrate a 11.3% gap between best closed source model and
layperson baseline while the gap increases to 21.3% by using the best
open-weight model. You can access the dataset from here:
https://huggingface.co/datasets/teias-ai/percul

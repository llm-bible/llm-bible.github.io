---
layout: publication
title: 'Multiloko: A Multilingual Local Knowledge Benchmark For Llms Spanning 31 Languages'
authors: Dieuwke Hupkes, Nikolay Bogoychev
conference: "Arxiv"
year: 2025
bibkey: hupkes2025multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.10356'}
tags: ['RAG']
---
We present MultiLoKo, a new benchmark for evaluating multilinguality in LLMs
covering 31 languages. MultiLoKo consists of three partitions: a main partition
consisting of 500 questions per language, separately sourced to be locally
relevant to the specific language, and two translated partitions, containing
human-authored translations from 30 non-English languages to English and vice
versa. For comparison, we also release corresponding machine-authored
translations. The data is equally distributed over two splits: a dev split and
a blind, out-of-distribution test split. MultiLoKo can be used to study a
variety of questions regarding the multilinguality of LLMs as well as
meta-questions about multilingual benchmark creation. We compute MultiLoKo
scores for 11 base and chat models marketed to be multilingual and study their
average performance, their performance parity across languages, how much their
ability to answer questions depends on the question language, and which
languages are most difficult. None of the models we studied performs well on
MultiLoKo, as indicated by low average scores as well as large differences
between the best and worst scoring languages. Furthermore, we find a
substantial effect of the question language, indicating sub-optimal knowledge
transfer between languages. Lastly, we find that using local vs
English-translated data can result in differences more than 20 points for the
best performing models, drastically change the estimated difficulty of some
languages. For using machines instead of human translations, we find a weaker
effect on ordering of language difficulty, a larger difference in model
rankings, and a substantial drop in estimated performance for all models.

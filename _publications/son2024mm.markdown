---
layout: publication
title: 'Mm-eval: A Multilingual Meta-evaluation Benchmark For Llm-as-a-judge And Reward Models'
authors: Guijin Son, Dongkeun Yoon, Juyoung Suk, Javier Aula-blasco, Mano Aslan, Vu Trong Kim, Shayekh Bin Islam, Jaume Prats-cristià, Lucía Tormo-bañuelos, Seungone Kim
conference: "Arxiv"
year: 2024
bibkey: son2024mm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.17578"}
tags: ['Bias Mitigation', 'Fairness', 'Ethics and Bias', 'Reinforcement Learning']
---
As Large Language Models (LLMs) are now capable of producing fluent and
coherent content in languages other than English, it is not imperative to
precisely evaluate these non-English outputs. However, when assessing the
outputs from mutlilingual LLMs, prior works often employed LLM based evaluators
that excel at assessing English outputs, without a thorough examination of
whether these evaluators could effectively assess non-English text as well.
Moreover, existing benchmarks to test evaluator LLMs (referred to as
"meta-evaluation benchmarks") are mostly English-centric. To bridge this gap
and examine whether evaluator LLMs can reliably assess the outputs of
multilingual LLMs, we introduce MM-Eval, a multilingual meta-evaluation
benchmark comprising five core subsets covering 18 languages and a Language
Consistency subset spanning 122 languages. A core attribute of MM-Eval is that,
instead of merely translating existing English meta-evaluation benchmarks, it
is designed with multilingual-specific challenges in mind. Additionally, unlike
existing meta-evaluation benchmarks that focus solely on ranking accuracy over
pairwise data, MM-Eval also evaluates the consistency and fairness of absolute
score values across a wide range of languages. Our results show that existing
evaluator LLMs that excel in English contexts have considerable room for
improvement when assessing non-English outputs. Furthermore, we find that
evaluators are unfair and inconsistent when evaluating lower-resourced
languages. Finally, we validate MM-Eval by measuring its correlation with
Best-of-N rankings, finding a significantly stronger correlation compared to
other meta-evaluation benchmarks. We publicly release our benchmark and code.

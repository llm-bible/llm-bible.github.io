---
layout: publication
title: 'A Benchmark For Learning To Translate A New Language From One Grammar Book'
authors: Garrett Tanzer, Mirac Suzgun, Eline Visser, Dan Jurafsky, Luke Melas-kyriazi
conference: "Arxiv"
year: 2023
bibkey: tanzer2023benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16575"}
tags: ['Interpretability and Explainability', 'RAG', 'Training Techniques', 'Applications']
---
Large language models (LLMs) can perform impressive feats with in-context
learning or lightweight finetuning. It is natural to wonder how well these
models adapt to genuinely new tasks, but how does one find tasks that are
unseen in internet-scale training sets? We turn to a field that is explicitly
motivated and bottlenecked by a scarcity of web data: low-resource languages.
In this paper, we introduce MTOB (Machine Translation from One Book), a
benchmark for learning to translate between English and Kalamang -- a language
with less than 200 speakers and therefore virtually no presence on the web --
using several hundred pages of field linguistics reference materials. This task
framing is novel in that it asks a model to learn a language from a single
human-readable book of grammar explanations, rather than a large mined corpus
of in-domain data, more akin to L2 learning than L1 acquisition. We demonstrate
that baselines using current LLMs are promising but fall short of human
performance, achieving 44.7 chrF on Kalamang to English translation and 45.8
chrF on English to Kalamang translation, compared to 51.6 and 57.0 chrF by a
human who learned Kalamang from the same reference materials. We hope that MTOB
will help measure LLM capabilities along a new dimension, and that the methods
developed to solve it could help expand access to language technology for
underserved communities by leveraging qualitatively different kinds of data
than traditional machine translation.

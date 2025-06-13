---
layout: publication
title: 'Beyond Memorization: Mapping The Originality-quality Frontier Of Language Models'
authors: Vishakh Padmakumar, Chen Yueh-han, Jane Pan, Valerie Chen, He He
conference: "Arxiv"
year: 2025
bibkey: padmakumar2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.09389'}
tags: ['Training Techniques']
---
As large language models (LLMs) are increasingly used for ideation and
scientific discovery, it is important to evaluate their ability to generate
novel output. Prior work evaluates novelty as the originality with respect to
training data, but original outputs can be low quality. In contrast, non-expert
judges may favor high-quality but memorized outputs, limiting the reliability
of human preference as a metric. We propose a new novelty metric for LLM
generations that balances originality and quality -- the harmonic mean of the
fraction of \ngrams unseen during training and a task-specific quality score.
We evaluate the novelty of generations from two families of open-data models
(OLMo and Pythia) on three creative tasks: story completion, poetry writing,
and creative tool use. We find that LLM generated text is less novel than human
written text. To elicit more novel outputs, we experiment with various
inference-time methods, which reveals a trade-off between originality and
quality. While these methods can boost novelty, they do so by increasing
originality at the expense of quality. In contrast, increasing model size or
applying post-training reliably shifts the Pareto frontier, highlighting that
starting with a stronger base model is a more effective way to improve novelty.

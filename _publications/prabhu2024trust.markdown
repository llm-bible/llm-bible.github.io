---
layout: publication
title: 'Trust But Verify: Programmatic VLM Evaluation In The Wild'
authors: Viraj Prabhu, Senthil Purushwalkam, An Yan, Caiming Xiong, Ran Xu
conference: "Arxiv"
year: 2024
bibkey: prabhu2024trust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13121"}
tags: ['Tools', 'Multimodal Models', 'Prompting', 'Reinforcement Learning']
---
Vision-Language Models (VLMs) often generate plausible but incorrect
responses to visual queries. However, reliably quantifying the effect of such
hallucinations in free-form responses to open-ended queries is challenging as
it requires visually verifying each claim within the response. We propose
Programmatic VLM Evaluation (PROVE), a new benchmarking paradigm for evaluating
VLM responses to open-ended queries. To construct PROVE, we provide a large
language model (LLM) with a high-fidelity scene-graph representation
constructed from a hyper-detailed image caption, and prompt it to generate
diverse question-answer (QA) pairs, as well as programs that can be executed
over the scene graph object to verify each QA pair. We thus construct a
benchmark of 10.5k challenging but visually grounded QA pairs. Next, to
evaluate free-form model responses to queries in PROVE, we propose a
programmatic evaluation strategy that measures both the helpfulness and
truthfulness of a response within a unified scene graph-based framework. We
benchmark the helpfulness-truthfulness trade-offs of a range of VLMs on PROVE,
finding that very few are in-fact able to achieve a good balance between the
two. Project page: \url\{https://prove-explorer.netlify.app/\}.

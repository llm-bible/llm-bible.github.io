---
layout: publication
title: 'MINERVA: Evaluating Complex Video Reasoning'
authors: Arsha Nagrani, Sachit Menon, Ahmet Iscen, Shyamal Buch, Ramin Mehran, Nilpa Jha, Anja Hauth, Yukun Zhu, Carl Vondrick, Mikhail Sirotenko, Cordelia Schmid, Tobias Weyand
conference: "Arxiv"
year: 2025
bibkey: nagrani2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00681"}
  - {name: "Code", url: "https://github.com/google-deepmind/neptune?tab=readme-ov-file\#minerva"}
tags: ['Ethics and Bias', 'Multimodal Models', 'Has Code', 'Reinforcement Learning']
---
Multimodal LLMs are turning their focus to video benchmarks, however most
video benchmarks only provide outcome supervision, with no intermediate or
interpretable reasoning steps. This makes it challenging to assess if models
are truly able to combine perceptual and temporal information to reason about
videos, or simply get the correct answer by chance or by exploiting linguistic
biases. To remedy this, we provide a new video reasoning dataset called MINERVA
for modern multimodal models. Each question in the dataset comes with 5 answer
choices, as well as detailed, hand-crafted reasoning traces. Our dataset is
multimodal, diverse in terms of video domain and length, and consists of
complex multi-step questions. Extensive benchmarking shows that our dataset
provides a challenge for frontier open-source and proprietary models. We
perform fine-grained error analysis to identify common failure modes across
various models, and create a taxonomy of reasoning errors. We use this to
explore both human and LLM-as-a-judge methods for scoring video reasoning
traces, and find that failure modes are primarily related to temporal
localization, followed by visual perception errors, as opposed to logical or
completeness errors. The dataset, along with questions, answer candidates and
reasoning traces will be publicly available under
https://github.com/google-deepmind/neptune?tab=readme-ov-file\#minerva.

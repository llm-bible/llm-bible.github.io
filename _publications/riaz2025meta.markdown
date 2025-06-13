---
layout: publication
title: 'Metasynth: Meta-prompting-driven Agentic Scaffolds For Diverse Synthetic Data Generation'
authors: Haris Riaz, Sourav Bhabesh, Vinayak Arannil, Miguel Ballesteros, Graham Horwood
conference: "Arxiv"
year: 2025
bibkey: riaz2025meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12563"}
tags: ['Agentic', 'Training Techniques', 'RAG', 'Fine-Tuning', 'Prompting', 'Pre-Training', 'Applications']
---
Recent smaller language models such Phi-3.5 and Phi-4 rely on synthetic data
generated using larger Language models. Questions remain about leveraging
synthetic data for other use cases, such as adapting LLMs to specific domains.
A key limitation of synthetic data is low diversity, which negatively impacts
its downstream applicability for improving other models. To address this, we
propose MetaSynth, a method for generating synthetic data that enhances
diversity through meta-prompting, where a language model orchestrates multiple
"expert" LLM agents to collaboratively generate data. Using only 25 million
tokens of synthetic data generated with MetaSynth, we successfully adapt a
well-trained LLM (Mistral-7B-v0.3) to two specialized domains-Finance and
Biomedicine-without compromising the capabilities of the resulting model in
general tasks. In addition, we evaluate the diversity of our synthetic data
using seven automated metrics, and find that it approaches the diversity of LLM
pre-training corpora.
  Continually pre-training Mistral-7B-v0.3 with MetaSynth notably outperforms
the base LLM, showing improvements of up to 4.08% in Finance and 13.75% in
Biomedicine. The same model shows degraded performance when trained on data
generated using a template prompt, even when the template includes prior
generations and varying In-Context exemplars of real data. Our findings suggest
that a few million tokens of diverse synthetic data without mixing any real
data, is sufficient for effective domain adaptation when using MetaSynth.

---
layout: publication
title: 'What Are Models Thinking About? Understanding Large Language Model Hallucinations "psychology" Through Model Inner State Analysis'
authors: Peiran Wang, Yang Liu, Yunfei Lu, Jue Hong, Ye Wu
conference: "Arxiv"
year: 2025
bibkey: wang2025what
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13490'}
tags: ['RAG', 'Interpretability and Explainability', 'Prompting']
---
Large language model (LLM) systems suffer from the models' unstable ability
to generate valid and factual content, resulting in hallucination generation.
Current hallucination detection methods heavily rely on out-of-model
information sources, such as RAG to assist the detection, thus bringing heavy
additional latency. Recently, internal states of LLMs' inference have been
widely used in numerous research works, such as prompt injection detection,
etc. Considering the interpretability of LLM internal states and the fact that
they do not require external information sources, we introduce such states into
LLM hallucination detection. In this paper, we systematically analyze different
internal states' revealing features during inference forward and
comprehensively evaluate their ability in hallucination detection.
Specifically, we cut the forward process of a large language model into three
stages: understanding, query, generation, and extracting the internal state
from these stages. By analyzing these states, we provide a deep understanding
of why the hallucinated content is generated and what happened in the internal
state of the models. Then, we introduce these internal states into
hallucination detection and conduct comprehensive experiments to discuss the
advantages and limitations.

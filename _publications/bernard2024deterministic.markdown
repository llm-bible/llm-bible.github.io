---
layout: publication
title: 'EQUATOR: A Deterministic Framework For Evaluating LLM Reasoning With Open-ended Questions. # V1.0.0-beta'
authors: Raymond Phd Bernard, Shaina Phd Raza, Subhabrata Phd Das, Rahul Murugan
conference: "Arxiv"
year: 2024
bibkey: bernard2024deterministic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00257"}
tags: ['Ethics and Bias', 'RAG', 'Applications', 'Tools']
---
Despite the remarkable coherence of Large Language Models (LLMs), existing
evaluation methods often suffer from fluency bias and rely heavily on
multiple-choice formats, making it difficult to assess factual accuracy and
complex reasoning effectively. LLMs thus frequently generate factually
inaccurate responses, especially in complex reasoning tasks, highlighting two
prominent challenges: (1) the inadequacy of existing methods to evaluate
reasoning and factual accuracy effectively, and (2) the reliance on human
evaluators for nuanced judgment, as illustrated by Williams and Huckle
(2024)[1], who found manual grading indispensable despite automated grading
advancements.
  To address evaluation gaps in open-ended reasoning tasks, we introduce the
EQUATOR Evaluator (Evaluation of Question Answering Thoroughness in Open-ended
Reasoning). This framework combines deterministic scoring with a focus on
factual accuracy and robust reasoning assessment. Using a vector database,
EQUATOR pairs open-ended questions with human-evaluated answers, enabling more
precise and scalable evaluations. In practice, EQUATOR significantly reduces
reliance on human evaluators for scoring and improves scalability compared to
Williams and Huckle's (2004)[1] methods.
  Our results demonstrate that this framework significantly outperforms
traditional multiple-choice evaluations while maintaining high accuracy
standards. Additionally, we introduce an automated evaluation process
leveraging smaller, locally hosted LLMs. We used LLaMA 3.2B, running on the
Ollama binaries to streamline our assessments. This work establishes a new
paradigm for evaluating LLM performance, emphasizing factual accuracy and
reasoning ability, and provides a robust methodological foundation for future
research.

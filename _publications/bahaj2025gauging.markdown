---
layout: publication
title: 'Gauging Overprecision In Llms: An Empirical Study'
authors: Adil Bahaj, Hamed Rahimi, Mohamed Chetouani, Mounir Ghogho
conference: "Arxiv"
year: 2025
bibkey: bahaj2025gauging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12098"}
tags: ['Model Architecture', 'Tools', 'Ethics and Bias', 'Prompting', 'Attention Mechanism']
---
Recently, overconfidence in large language models (LLMs) has garnered
considerable attention due to its fundamental importance in quantifying the
trustworthiness of LLM generation. However, existing approaches prompt the
\textit\{black box LLMs\} to produce their confidence (\textit\{verbalized
confidence\}), which can be subject to many biases and hallucinations. Inspired
by a different aspect of overconfidence in cognitive science called
\textit\{overprecision\}, we designed a framework for its study in black box
LLMs. This framework contains three main phases: 1) generation, 2) refinement
and 3) evaluation. In the generation phase we prompt the LLM to generate
answers to numerical questions in the form of intervals with a certain level of
confidence. This confidence level is imposed in the prompt and not required for
the LLM to generate as in previous approaches. We use various prompting
techniques and use the same prompt multiple times to gauge the effects of
randomness in the generation process. In the refinement phase, answers from the
previous phase are refined to generate better answers. The LLM answers are
evaluated and studied in the evaluation phase to understand its internal
workings. This study allowed us to gain various insights into LLM
overprecision: 1) LLMs are highly uncalibrated for numerical tasks 2) there is
no correlation between the length of the interval and the imposed confidence
level, which can be symptomatic of a a) lack of understanding of the concept of
confidence or b) inability to adjust self-confidence by following instructions,
\{3) LLM numerical precision differs depending on the task, scale of answer and
prompting technique 4) Refinement of answers doesn't improve precision in most
cases. We believe this study offers new perspectives on LLM overconfidence and
serves as a strong baseline for overprecision in LLMs.

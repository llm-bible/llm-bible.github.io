---
layout: publication
title: 'Gitchameleon: Unmasking The Version-switching Capabilities Of Code Generation Models'
authors: Nizar Islah, Justine Gehring, Diganta Misra, Eilif Muller, Irina Rish, Terry Yue Zhuo, Massimo Caccia
conference: "Arxiv"
year: 2024
bibkey: islah2024unmasking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05830"}
  - {name: "Code", url: "https://github.com/NizarIslah/GitChameleon"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Has Code']
---
The rapid evolution of software libraries presents a significant challenge
for code generation models, which must adapt to frequent version updates while
maintaining compatibility with previous versions. Existing code completion
benchmarks often overlook this dynamic aspect, and the one that does consider
it relies on static code prediction tasks without execution-based evaluation,
offering a limited perspective on a model's practical usability. To address
this gap, we introduce \textbf\{\GitChameleon\{\}\}, a novel, manually curated
dataset comprising 116 Python code completion problems, each conditioned on
specific library versions and accompanied by executable unit tests.
\GitChameleon\{\} is designed to rigorously assess the ability of modern large
language models (LLMs) to generate version-specific code that is not only
syntactically correct but also functionally accurate upon execution. Our
comprehensive evaluations reveal that state-of-the-art LLMs struggle with this
task; for instance, \textbf\{GPT-4o\} achieves a pass@10 of only 39.9% (43.7%
when provided with error feedback), highlighting the complexity of the problem
and the limitations of current models. By providing an execution-based
benchmark that emphasizes the dynamic nature of code libraries, \GitChameleon\{\}
serves as a critical tool to advance the development of more adaptable and
reliable code generation models. For facilitation for further exploration of
version-conditioned code generation, we make our code repository publicly
accessible at \url\{https://github.com/NizarIslah/GitChameleon\}.

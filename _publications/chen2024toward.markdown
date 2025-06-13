---
layout: publication
title: 'Toward Adaptive Reasoning In Large Language Models With Thought Rollback'
authors: Sijia Chen, Baochun Li
conference: "Arxiv"
year: 2024
bibkey: chen2024toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.19707"}
tags: ['Prompting', 'Model Architecture', 'GPT', 'Tools']
---
Large language models (LLMs) have been routinely used to solve various tasks
using step-by-step reasoning. However, the structure of intermediate reasoning
steps, or thoughts, is rigid and unidirectional, such as chains, trees, or
acyclic-directed graphs. Consequently, the resulting inflexible and
forward-only reasoning may not address challenging tasks and fail when the LLM
frequently gives false responses, i.e., ``hallucinations''. This paper proposes
a new reasoning framework, called Thought Rollback (TR), allowing LLMs to
adaptively build thought structure while maintaining effective reasoning toward
problem-solving under ``hallucinations''. The core mechanism of TR is rolling
back thoughts, which allows LLMs to perform error analysis on thoughts, and
thus roll back to any previously mistaken thought for revision. Subsequently,
by including such trial-and-error in the prompt to guide the LLM, each rollback
leads to one more reliable reasoning path. Therefore, starting with a simple
prompt without human annotations, LLM with TR adaptively and gradually explores
thoughts for a correct solution. Comprehensive experiments on mathematical
problems and multi-task reasoning demonstrate the state-of-the-art performance
of TR in terms of problem-solving rate and interaction cost. For instance, the
solving rate of GPT-4 with TR outperforms the current best by \\(9%\\) on the MATH
dataset.

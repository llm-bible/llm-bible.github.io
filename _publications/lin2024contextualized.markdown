---
layout: publication
title: 'Contextualized Sequence Likelihood: Enhanced Confidence Scores For Natural Language Generation'
authors: Lin Zhen, Trivedi Shubhendu, Sun Jimeng
conference: "Arxiv"
year: 2024
bibkey: lin2024contextualized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01806"}
tags: ['Attention Mechanism', 'Model Architecture', 'Prompting']
---
The advent of large language models (LLMs) has dramatically advanced the
state-of-the-art in numerous natural language generation tasks. For LLMs to be
applied reliably, it is essential to have an accurate measure of their
confidence. Currently, the most commonly used confidence score function is the
likelihood of the generated sequence, which, however, conflates semantic and
syntactic components. For instance, in question-answering (QA) tasks, an
awkward phrasing of the correct answer might result in a lower probability
prediction. Additionally, different tokens should be weighted differently
depending on the context. In this work, we propose enhancing the predicted
sequence probability by assigning different weights to various tokens using
attention values elicited from the base LLM. By employing a validation set, we
can identify the relevant attention heads, thereby significantly improving the
reliability of the vanilla sequence probability confidence measure. We refer to
this new score as the Contextualized Sequence Likelihood (CSL). CSL is easy to
implement, fast to compute, and offers considerable potential for further
improvement with task-specific prompts. Across several QA datasets and a
diverse array of LLMs, CSL has demonstrated significantly higher reliability
than state-of-the-art baselines in predicting generation quality, as measured
by the AUROC or AUARC.

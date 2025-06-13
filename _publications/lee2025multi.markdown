---
layout: publication
title: 'Multi-round, Chain-of-thought Post-editing For Unfaithful Summaries'
authors: Yi-hui Lee, Xiangci Li, Jessica Ouyang
conference: "Arxiv"
year: 2025
bibkey: lee2025multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.11273'}
tags: ['Prompting', 'Applications']
---
Recent large language models (LLMs) have demonstrated a remarkable ability to
perform natural language understanding and generation tasks. In this work, we
investigate the use of LLMs for evaluating faithfulness in news summarization,
finding that it achieves a strong correlation with human judgments. We further
investigate LLMs' capabilities as a faithfulness post-editor, experimenting
with different chain-of-thought prompts for locating and correcting factual
inconsistencies between a generated summary and the source news document and
are able to achieve a higher editing success rate than was reported in prior
work. We perform both automated and human evaluations of the post-edited
summaries, finding that prompting LLMs using chain-of-thought reasoning about
factual error types is an effective faithfulness post-editing strategy,
performing comparably to fine-tuned post-editing models. We also demonstrate
that multiple rounds of post-editing, which has not previously been explored,
can be used to gradually improve the faithfulness of summaries whose errors
cannot be fully corrected in a single round.

---
layout: publication
title: 'Lost In The Passage: Passage-level In-context Learning Does Not Necessarily Need A "passage"'
authors: Hao Sun, Chenming Tang, Gengyang Li, Yunfang Wu
conference: "Arxiv"
year: 2025
bibkey: sun2025lost
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10634'}
tags: ['Attention Mechanism', 'Prompting', 'In-Context Learning', 'Model Architecture']
---
By simply incorporating demonstrations into the context, in-context learning
(ICL) enables large language models (LLMs) to yield awesome performance on many
tasks. In this paper, we focus on passage-level long-context ICL for generation
tasks and find that LLMs cannot learn the intrinsic relationships between the
demonstration passage and the generation output. We conduct experiments with
different LLMs on two typical generation tasks including single-document QA and
distractor generation, demonstrating that even a completely meaningless
demonstration passage with 1/4 length achieves much better performance than the
original full passage. Analysis via attention score reveals that LLMs pay
little attention to passages compared to other components in prompt and little
attention flows from the passage to other parts of the demonstration, which
further confirms our finding. Additionally, experiments on context compression
indicate that compression approaches proven effective on other long-context
tasks are not suitable for passage-level ICL, since simply using shorter
meaningless demonstration passages has achieved competitive performance.

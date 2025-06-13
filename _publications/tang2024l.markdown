---
layout: publication
title: 'L-citeeval: Do Long-context Models Truly Leverage Context For Responding?'
authors: Zecheng Tang, Keyan Zhou, Juntao Li, Baibei Ji, Jianye Hou, Min Zhang
conference: "Arxiv"
year: 2024
bibkey: tang2024l
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02115"}
tags: ['Transformer', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Attention Mechanism']
---
Long-context models (LCMs) have made remarkable strides in recent years,
offering users great convenience for handling tasks that involve long context,
such as document summarization. As the community increasingly prioritizes the
faithfulness of generated results, merely ensuring the accuracy of LCM outputs
is insufficient, as it is quite challenging for humans to verify the results
from the extremely lengthy context. Yet, although some efforts have been made
to assess whether LCMs respond truly based on the context, these works either
are limited to specific tasks or heavily rely on external evaluation resources
like GPT4.In this work, we introduce L-CiteEval, a comprehensive multi-task
benchmark for long-context understanding with citations, aiming to evaluate
both the understanding capability and faithfulness of LCMs. L-CiteEval covers
11 tasks from diverse domains, spanning context lengths from 8K to 48K, and
provides a fully automated evaluation suite. Through testing with 11
cutting-edge closed-source and open-source LCMs, we find that although these
models show minor differences in their generated results, open-source models
substantially trail behind their closed-source counterparts in terms of
citation accuracy and recall. This suggests that current open-source LCMs are
prone to responding based on their inherent knowledge rather than the given
context, posing a significant risk to the user experience in practical
applications. We also evaluate the RAG approach and observe that RAG can
significantly improve the faithfulness of LCMs, albeit with a slight decrease
in the generation quality. Furthermore, we discover a correlation between the
attention mechanisms of LCMs and the citation generation process.

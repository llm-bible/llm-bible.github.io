---
layout: publication
title: Semantically Diverse Language Generation For Uncertainty Estimation In Language Models
authors: Aichberger Lukas, Schweighofer Kajetan, Ielanskyi Mykyta, Hochreiter Sepp
conference: "Arxiv"
year: 2024
bibkey: aichberger2024semantically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04306"}
tags: ['Applications', 'GPT', 'Pretraining Methods']
---
Large language models (LLMs) can suffer from hallucinations when generating text. These hallucinations impede various applications in society and industry by making LLMs untrustworthy. Current LLMs generate text in an autoregressive fashion by predicting and appending text tokens. When an LLM is uncertain about the semantic meaning of the next tokens to generate it is likely to start hallucinating. Thus it has been suggested that hallucinations stem from predictive uncertainty. We introduce Semantically Diverse Language Generation (SDLG) to quantify predictive uncertainty in LLMs. SDLG steers the LLM to generate semantically diverse yet likely alternatives for an initially generated text. This approach provides a precise measure of aleatoric semantic uncertainty detecting whether the initial text is likely to be hallucinated. Experiments on question45;answering tasks demonstrate that SDLG consistently outperforms existing methods while being the most computationally efficient setting a new standard for uncertainty estimation in LLMs.

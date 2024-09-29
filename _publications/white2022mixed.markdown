---
layout: publication
title: "Mixed-effects Transformers For Hierarchical Adaptation"
authors: White Julia, Goodman Noah, Hawkins Robert
conference: "Arxiv"
year: 2022
bibkey: white2022mixed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.01749"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Language use differs dramatically from context to context. To some degree modern language models like GPT-3 are able to account for such variance by conditioning on a string of previous input text or prompt. Yet prompting is ineffective when contexts are sparse out-of-sample or extra-textual; for instance accounting for when and where the text was produced or who produced it. In this paper we introduce the mixed-effects transformer (MET) a novel approach for learning hierarchically-structured prefixes -- lightweight modules prepended to the input -- to account for structured variation. Specifically we show how the popular class of mixed-effects models may be extended to transformer-based architectures using a regularized prefix-tuning procedure with dropout. We evaluate this approach on several domain-adaptation benchmarks finding that it efficiently adapts to novel contexts with minimal data while still effectively generalizing to unseen contexts.

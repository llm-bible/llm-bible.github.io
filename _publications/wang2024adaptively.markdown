---
layout: publication
title: 'Adacad: Adaptively Decoding To Balance Conflicts Between Contextual And Parametric Knowledge'
authors: Han Wang, Archiki Prasad, Elias Stengel-eskin, Mohit Bansal
conference: "Arxiv"
year: 2024
bibkey: wang2024adaptively
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.07394'}
tags: ['Reinforcement Learning', 'RAG', 'Applications']
---
Knowledge conflict arises from discrepancies between information in the
context of a large language model (LLM) and the knowledge stored in its
parameters. This can hurt performance when using standard decoding techniques,
which tend to ignore the context. Existing test-time contrastive methods seek
to address this by comparing the LLM's output distribution with and without the
context and adjust the model according to the contrast between them. However,
we find that these methods frequently misjudge the degree of conflict and
struggle to handle instances that vary in their amount of conflict, with static
methods over-adjusting when conflict is absent. We propose a fine-grained,
instance-level approach called AdaCAD, which dynamically infers the weight of
adjustment based on the degree of conflict, as measured by the Jensen-Shannon
divergence between distributions representing contextual and parametric
knowledge. Across four LLMs, six question-answering (QA) and three
summarization datasets, we demonstrate that ADACAD consistently outperforms
other decoding baselines with average QA accuracy gains of 14.21% (absolute)
over a static contrastive baseline, and improves the factuality of summaries by
6.19 (AlignScore). Lastly, we show that while contrastive baselines hurt
performance when conflict is absent, ADACAD mitigates these losses, making it
more applicable to real-world datasets in which some examples have conflict and
others do not.

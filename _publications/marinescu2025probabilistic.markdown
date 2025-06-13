---
layout: publication
title: 'Factreasoner: A Probabilistic Approach To Long-form Factuality Assessment For Large Language Models'
authors: Radu Marinescu, Debarun Bhattacharjya, Junkyu Lee, Tigran Tchrakian, Javier Carnerero Cano, Yufang Hou, Elizabeth Daly, Alessandra Pascale
conference: "Arxiv"
year: 2025
bibkey: marinescu2025probabilistic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18573'}
tags: ['Reinforcement Learning', 'Prompting']
---
Large language models (LLMs) have demonstrated vast capabilities on
generative tasks in recent years, yet they struggle with guaranteeing the
factual correctness of the generated content. This makes these models
unreliable in realistic situations where factually accurate responses are
expected. In this paper, we propose FactReasoner, a new factuality assessor
that relies on probabilistic reasoning to assess the factuality of a long-form
generated response. Specifically, FactReasoner decomposes the response into
atomic units, retrieves relevant contexts for them from an external knowledge
source, and constructs a joint probability distribution over the atoms and
contexts using probabilistic encodings of the logical relationships
(entailment, contradiction) between the textual utterances corresponding to the
atoms and contexts. FactReasoner then computes the posterior probability of
whether atomic units in the response are supported by the retrieved contexts.
Our experiments on labeled and unlabeled benchmark datasets demonstrate clearly
that FactReasoner improves considerably over state-of-the-art prompt-based
approaches in terms of both factual precision and recall.

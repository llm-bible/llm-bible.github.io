---
layout: publication
title: 'Jailbreaking Large Language Models In Infinitely Many Ways'
authors: Oliver Goldstein, Emanuele La Malfa, Felix Drinkall, Samuele Marro, Michael Wooldridge
conference: "Arxiv"
year: 2025
bibkey: goldstein2025jailbreaking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.10800'}
tags: ['RAG', 'Security', 'Responsible AI']
---
We discuss the ``Infinitely Many Paraphrases'' attacks (IMP), a category of
jailbreaks that leverages the increasing capabilities of a model to handle
paraphrases and encoded communications to bypass their defensive mechanisms.
IMPs' viability pairs and grows with a model's capabilities to handle and bind
the semantics of simple mappings between tokens and work extremely well in
practice, posing a concrete threat to the users of the most powerful LLMs in
commerce. We show how one can bypass the safeguards of the most powerful open-
and closed-source LLMs and generate content that explicitly violates their
safety policies. One can protect against IMPs by improving the guardrails and
making them scale with the LLMs' capabilities. For two categories of attacks
that are straightforward to implement, i.e., bijection and encoding, we discuss
two defensive strategies, one in token and the other in embedding space. We
conclude with some research questions we believe should be prioritised to
enhance the defensive mechanisms of LLMs and our understanding of their safety.

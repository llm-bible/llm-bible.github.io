---
layout: publication
title: 'Curate: Benchmarking Personalised Alignment Of Conversational AI Assistants'
authors: Lize Alberts, Benjamin Ellis, Andrei Lupu, Jakob Foerster
conference: "Arxiv"
year: 2024
bibkey: alberts2024benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21159'}
tags: ['Ethics and Bias', 'Prompting', 'Responsible AI', 'Applications']
---
We introduce a multi-turn benchmark for evaluating personalised alignment in
LLM-based AI assistants, focusing on their ability to handle user-provided
safety-critical contexts. Our assessment of ten leading models across five
scenarios (with 337 use cases each) reveals systematic inconsistencies in
maintaining user-specific consideration, with even top-rated "harmless" models
making recommendations that should be recognised as obviously harmful to the
user given the context provided. Key failure modes include inappropriate
weighing of conflicting preferences, sycophancy (prioritising desires above
safety), a lack of attentiveness to critical user information within the
context window, and inconsistent application of user-specific knowledge. The
same systematic biases were observed in OpenAI's o1, suggesting that strong
reasoning capacities do not necessarily transfer to this kind of personalised
thinking. We find that prompting LLMs to consider safety-critical context
significantly improves performance, unlike a generic 'harmless and helpful'
instruction. Based on these findings, we propose research directions for
embedding self-reflection capabilities, online user modelling, and dynamic risk
assessment in AI assistants. Our work emphasises the need for nuanced,
context-aware approaches to alignment in systems designed for persistent human
interaction, aiding the development of safe and considerate AI assistants.

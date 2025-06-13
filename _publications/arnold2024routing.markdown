---
layout: publication
title: 'Routing In Sparsely-gated Language Models Responds To Context'
authors: Stefan Arnold, Marian Fietta, Dilara Yesilbas
conference: "Arxiv"
year: 2024
bibkey: arnold2024routing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14107"}
tags: ['Uncategorized']
---
Language Models (LMs) recently incorporate mixture-of-experts layers
consisting of a router and a collection of experts to scale up their parameter
count given a fixed computational budget. Building on previous efforts
indicating that token-expert assignments are predominantly influenced by token
identities and positions, we trace routing decisions of similarity-annotated
text pairs to evaluate the context sensitivity of learned token-expert
assignments. We observe that routing in encoder layers mainly depends on
(semantic) associations, but contextual cues provide an additional layer of
refinement. Conversely, routing in decoder layers is more variable and markedly
less sensitive to context.

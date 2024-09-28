---
layout: publication
title: Domain-independent User Simulation with Transformers for Task-oriented Dialogue Systems
authors: Lin Hsien-chin, Lubis Nurul, Hu Songbo, Van Niekerk Carel, Geishauser Christian, Heck Michael, Feng Shutong, Gašić Milica
conference: "Arxiv"
year: 2021
bibkey: lin2021domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.08838"}
tags: ['ARXIV', 'Model Architecture', 'Transformer']
---
Dialogue policy optimisation via reinforcement learning requires a large number of training interactions which makes learning with real users time consuming and expensive. Many set-ups therefore rely on a user simulator instead of humans. These user simulators have their own problems. While hand-coded rule-based user simulators have been shown to be sufficient in small simple domains for complex domains the number of rules quickly becomes intractable. State-of-the-art data-driven user simulators on the other hand are still domain-dependent. This means that adaptation to each new domain requires redesigning and retraining. In this work we propose a domain-independent transformer-based user simulator (TUS). The structure of our TUS is not tied to a specific domain enabling domain generalisation and learning of cross-domain user behaviour from data. We compare TUS with the state of the art using automatic as well as human evaluations. TUS can compete with rule-based user simulators on pre-defined domains and is able to generalise to unseen domains in a zero-shot fashion.

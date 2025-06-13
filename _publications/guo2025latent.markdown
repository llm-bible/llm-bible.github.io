---
layout: publication
title: 'Darkmind: Latent Chain-of-thought Backdoor In Customized Llms'
authors: Zhen Guo, Reza Tourani
conference: "Arxiv"
year: 2025
bibkey: guo2025latent
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.18617'}
tags: ['Agentic', 'Security', 'GPT', 'Model Architecture', 'Tools', 'Reinforcement Learning']
---
With the growing demand for personalized AI solutions, customized LLMs have
become a preferred choice for businesses and individuals, driving the
deployment of millions of AI agents across various platforms, e.g., GPT Store
hosts over 3 million customized GPTs. Their popularity is partly driven by
advanced reasoning capabilities, such as Chain-of-Thought, which enhance their
ability to tackle complex tasks. However, their rapid proliferation introduces
new vulnerabilities, particularly in reasoning processes that remain largely
unexplored. We introduce DarkMind, a novel backdoor attack that exploits the
reasoning capabilities of customized LLMs. Designed to remain latent, DarkMind
activates within the reasoning chain to covertly alter the final outcome.
Unlike existing attacks, it operates without injecting triggers into user
queries, making it a more potent threat. We evaluate DarkMind across eight
datasets covering arithmetic, commonsense, and symbolic reasoning domains,
using five state-of-the-art LLMs with five distinct trigger implementations.
Our results demonstrate DarkMind effectiveness across all scenarios,
underscoring its impact. Finally, we explore potential defense mechanisms to
mitigate its risks, emphasizing the need for stronger security measures.

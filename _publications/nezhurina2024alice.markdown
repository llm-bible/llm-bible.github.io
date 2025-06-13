---
layout: publication
title: 'Alice In Wonderland: Simple Tasks Showing Complete Reasoning Breakdown In State-of-the-art Large Language Models'
authors: Marianna Nezhurina, Lucia Cipolina-kun, Mehdi Cherti, Jenia Jitsev
conference: "Arxiv"
year: 2024
bibkey: nezhurina2024alice
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02061"}
  - {name: "Code", url: "https://github.com/LAION-AI/AIW"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Scaling Laws', 'Reinforcement Learning', 'RAG', 'GPT', 'Large-Scale Training', 'Has Code', 'Interpretability and Explainability', 'Prompting', 'Pre-Training']
---
Large Language Models (LLMs) are often described as instances of foundation
models that possess strong generalization obeying scaling laws, and therefore
transfer robustly across various conditions in few- or zero-shot manner. Such
claims rely on standardized benchmarks that suppose to measure generalization
and reasoning, where state-of-the-art (SOTA) models score high. We demonstrate
here a dramatic breakdown of generalization and basic reasoning of all SOTA
models claiming strong function, including large scale advanced models like
GPT-4 or Claude 3 Opus, using a simple, short common sense math problem
formulated in concise natural language, easily solvable by humans (AIW
problem). The breakdown is dramatic as it manifests on a simple problem in both
low average performance and strong performance fluctuations on natural
variations in problem template that do not change either problem structure or
its difficulty at all. By testing models on further control problems with
similar form, we rule out that breakdown might be rooted in minor low-level
issues like natural language or numbers parsing. We also observe strong
overconfidence in the wrong solutions, expressed in form of plausible sounding
explanation-like confabulations. Various standard interventions in an attempt
to get the right solution, like chain-of-thought prompting, or urging the
models to reconsider the wrong solutions again by multi step re-evaluation,
fail. We use these observations to stimulate re-assessment of the capabilities
of current generation of LLMs as claimed by standardized benchmarks. Such
re-assessment also requires common action to create standardized benchmarks
that would allow proper detection of such deficits in generalization and
reasoning that obviously remain undiscovered by current state-of-the-art
evaluation procedures, where SOTA LLMs manage to score high. Code:
https://github.com/LAION-AI/AIW

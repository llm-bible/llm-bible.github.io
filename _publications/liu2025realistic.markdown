---
layout: publication
title: 'Eeyore: Realistic Depression Simulation Via Supervised And Preference Optimization'
authors: Siyang Liu, Bianca Brie, Wenda Li, Laura Biester, Andrew Lee, James Pennebaker, Rada Mihalcea
conference: "Arxiv"
year: 2025
bibkey: liu2025realistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00018"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting']
---
Large Language Models (LLMs) have been previously explored for mental
healthcare training and therapy client simulation, but they still fall short in
authentically capturing diverse client traits and psychological conditions. We
introduce \textbf\{Eeyore\}, an 8B model optimized for realistic depression
simulation through a structured alignment framework, incorporating expert input
at every stage. First, we systematically curate real-world depression-related
conversations, extracting depressive traits to guide data filtering and
psychological profile construction, and use this dataset to instruction-tune
Eeyore for profile adherence. Next, to further enhance realism, Eeyore
undergoes iterative preference optimization -- first leveraging model-generated
preferences and then calibrating with a small set of expert-annotated
preferences. Throughout the entire pipeline, we actively collaborate with
domain experts, developing interactive interfaces to validate trait extraction
and iteratively refine structured psychological profiles for clinically
meaningful role-play customization. Despite its smaller model size, the Eeyore
depression simulation outperforms GPT-4o with SOTA prompting strategies, both
in linguistic authenticity and profile adherence.

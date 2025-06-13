---
layout: publication
title: 'Charactergpt: A Persona Reconstruction Framework For Role-playing Agents'
authors: Jeiyoon Park, Chanjun Park, Heuiseok Lim
conference: "Arxiv"
year: 2024
bibkey: park2024persona
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19778"}
  - {name: "Code", url: "https://github.com/Jeiyoon/charactergpt"}
tags: ['Agentic', 'GPT', 'Tools', 'Model Architecture', 'Training Techniques', 'Has Code']
---
The recent introduction of the Assistants API highlights its potential for
large language models (LLMs) in role-playing agents (RPA). However, maintaining
consistent character personas remains a significant challenge due to
variability in information extraction, which frequently omits critical elements
such as backstory or interpersonal relationships. To address this limitation,
we introduce CharacterGPT, a framework designed to dynamically reconstruct
character personas through Character Persona Training (CPT). This approach
incrementally updates personas by extracting traits from chapter-wise novel
summaries, reflecting the progression of the narrative. Our framework is
evaluated through Big Five personality evaluations and creative tasks, in which
characters generate original narratives, demonstrating the efficacy of
CharacterGPT in preserving persona consistency. The code and results are
available at https://github.com/Jeiyoon/charactergpt

---
layout: publication
title: 'Rolemrc: A Fine-grained Composite Benchmark For Role-playing And Instruction-following'
authors: Junru Lu, Jiazheng Li, Guodong Shen, Lin Gui, Siyu An, Yulan He, Di Yin, Xing Sun
conference: "Arxiv"
year: 2025
bibkey: lu2025fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11387"}
  - {name: "Code", url: "https://github.com/LuJunru/RoleMRC"}
tags: ['Has Code', 'Reinforcement Learning']
---
Role-playing is important for Large Language Models (LLMs) to follow diverse
instructions while maintaining role identity and the role's pre-defined ability
limits. Existing role-playing datasets mostly contribute to controlling role
style and knowledge boundaries, but overlook role-playing in
instruction-following scenarios. We introduce a fine-grained role-playing and
instruction-following composite benchmark, named RoleMRC, including: (1)
Multi-turn dialogues between ideal roles and humans, including free chats or
discussions upon given passages; (2) Role-playing machine reading
comprehension, involving response, refusal, and attempts according to passage
answerability and role ability; (3) More complex scenarios with nested,
multi-turn and prioritized instructions. The final RoleMRC features a 10.2k
role profile meta-pool, 37.9k well-synthesized role-playing instructions, and
1.4k testing samples. We develop a pipeline to quantitatively evaluate the
fine-grained role-playing and instruction-following capabilities of several
mainstream LLMs, as well as models that are fine-tuned on our data. Moreover,
cross-evaluation on external role-playing datasets confirms that models
fine-tuned on RoleMRC enhances instruction-following without compromising
general role-playing and reasoning capabilities. We also probe the neural-level
activation maps of different capabilities over post-tuned LLMs. Access to our
RoleMRC, RoleMRC-mix and Codes: https://github.com/LuJunru/RoleMRC.

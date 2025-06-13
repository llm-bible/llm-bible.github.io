---
layout: publication
title: 'BT-ACTION: A Test-driven Approach For Modular Understanding Of User Instruction Leveraging Behaviour Trees And Llms'
authors: Alexander Leszczynski, Sarah Gillet, Iolanda Leite, Fethiye Irmak Dogan
conference: "Arxiv"
year: 2025
bibkey: leszczynski2025bt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.02779'}
  - {name: "Code", url: 'https://github.com/1Eggbert7/BT_LLM'}
tags: ['Has Code', 'RAG', 'BERT', 'Model Architecture', 'Prompting']
---
Natural language instructions are often abstract and complex, requiring
robots to execute multiple subtasks even for seemingly simple queries. For
example, when a user asks a robot to prepare avocado toast, the task involves
several sequential steps. Moreover, such instructions can be ambiguous or
infeasible for the robot or may exceed the robot's existing knowledge. While
Large Language Models (LLMs) offer strong language reasoning capabilities to
handle these challenges, effectively integrating them into robotic systems
remains a key challenge. To address this, we propose BT-ACTION, a test-driven
approach that combines the modular structure of Behavior Trees (BT) with LLMs
to generate coherent sequences of robot actions for following complex user
instructions, specifically in the context of preparing recipes in a
kitchen-assistance setting. We evaluated BT-ACTION in a comprehensive user
study with 45 participants, comparing its performance to direct LLM prompting.
Results demonstrate that the modular design of BT-ACTION helped the robot make
fewer mistakes and increased user trust, and participants showed a significant
preference for the robot leveraging BT-ACTION. The code is publicly available
at https://github.com/1Eggbert7/BT_LLM.

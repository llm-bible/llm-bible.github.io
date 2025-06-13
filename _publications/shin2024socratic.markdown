---
layout: publication
title: 'Socratic Planner: Self-qa-based Zero-shot Planning For Embodied Instruction Following'
authors: Suyeon Shin, Sujin Jeon, Junghyun Kim, Gi-cheon Kang, Byoung-tak Zhang
conference: "Arxiv"
year: 2024
bibkey: shin2024socratic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15190"}
tags: ['Agentic', 'Training Techniques', 'Few-Shot', 'Reinforcement Learning', 'TACL', 'ACL', 'Prompting', 'In-Context Learning']
---
Embodied Instruction Following (EIF) is the task of executing natural
language instructions by navigating and interacting with objects in interactive
environments. A key challenge in EIF is compositional task planning, typically
addressed through supervised learning or few-shot in-context learning with
labeled data. To this end, we introduce the Socratic Planner, a self-QA-based
zero-shot planning method that infers an appropriate plan without any further
training. The Socratic Planner first facilitates self-questioning and answering
by the Large Language Model (LLM), which in turn helps generate a sequence of
subgoals. While executing the subgoals, an embodied agent may encounter
unexpected situations, such as unforeseen obstacles. The Socratic Planner then
adjusts plans based on dense visual feedback through a visually-grounded
re-planning mechanism. Experiments demonstrate the effectiveness of the
Socratic Planner, outperforming current state-of-the-art planning models on the
ALFRED benchmark across all metrics, particularly excelling in long-horizon
tasks that demand complex inference. We further demonstrate its real-world
applicability through deployment on a physical robot for long-horizon tasks.

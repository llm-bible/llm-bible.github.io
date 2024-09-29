---
layout: publication
title: Grounding Language With Visual Affordances Over Unstructured Data
authors: Mees Oier, Borja-diaz Jessica, Burgard Wolfram
conference: "Arxiv"
year: 2022
bibkey: mees2022grounding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.01911"}
  - {name: "Code", url: "http://hulc2.cs.uni-freiburg.de"}
tags: ['Few Shot', 'Has Code', 'In Context Learning', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Recent works have shown that Large Language Models (LLMs) can be applied to ground natural language to a wide variety of robot skills. However in practice learning multi-task language-conditioned robotic skills typically requires large-scale data collection and frequent human intervention to reset the environment or help correcting the current policies. In this work we propose a novel approach to efficiently learn general-purpose language-conditioned robot skills from unstructured offline and reset-free data in the real world by exploiting a self-supervised visuo-lingual affordance model which requires annotating as little as 137; of the total data with language. We evaluate our method in extensive experiments both in simulated and real-world robotic tasks achieving state-of-the-art performance on the challenging CALVIN benchmark and learning over 25 distinct visuomotor manipulation tasks with a single policy in the real world. We find that when paired with LLMs to break down abstract natural language instructions into subgoals via few-shot prompting our method is capable of completing long-horizon multi-tier tasks in the real world while requiring an order of magnitude less data than previous approaches. Code and videos are available at http://hulc2.cs.uni-freiburg.de

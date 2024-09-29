---
layout: publication
title: Empowering Large Language Models On Robotic Manipulation With Affordance Prompting
authors: Cheng Guangran, Zhang Chuheng, Cai Wenzhe, Zhao Li, Sun Changyin, Bian Jiang
conference: "Arxiv"
year: 2024
bibkey: cheng2024empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11027"}
tags: ['Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While large language models (LLMs) are successful in completing various language processing tasks they easily fail to interact with the physical world by generating control sequences properly. We find that the main reason is that LLMs are not grounded in the physical world. Existing LLM45;based approaches circumvent this problem by relying on additional pre45;defined skills or pre45;trained sub45;policies making it hard to adapt to new tasks. In contrast we aim to address this problem and explore the possibility to prompt pre45;trained LLMs to accomplish a series of robotic manipulation tasks in a training45;free paradigm. Accordingly we propose a framework called LLM+A(ffordance) where the LLM serves as both the sub45;task planner (that generates high45;level plans) and the motion controller (that generates low45;level control sequences). To ground these plans and control sequences on the physical world we develop the affordance prompting technique that stimulates the LLM to 1) predict the consequences of generated plans and 2) generate affordance values for relevant objects. Empirically we evaluate the effectiveness of LLM+A in various language45;conditioned robotic manipulation tasks which show that our approach substantially improves performance by enhancing the feasibility of generated plans and control and can easily generalize to different environments.

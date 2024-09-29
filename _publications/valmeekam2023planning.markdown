---
layout: publication
title: 'On The Planning Abilities Of Large Language Models : A Critical Investigation'
authors: Valmeekam Karthik, Marquez Matthew, Sreedharan Sarath, Kambhampati Subbarao
conference: "Arxiv"
year: 2023
bibkey: valmeekam2023planning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15771"}
tags: ['Agent', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Intrigued by the claims of emergent reasoning capabilities in LLMs trained on general web corpora in this paper we set out to investigate their planning capabilities. We aim to evaluate (1) the effectiveness of LLMs in generating plans autonomously in commonsense planning tasks and (2) the potential of LLMs in LLM-Modulo settings where they act as a source of heuristic guidance for external planners and verifiers. We conduct a systematic study by generating a suite of instances on domains similar to the ones employed in the International Planning Competition and evaluate LLMs in two distinct modes autonomous and heuristic. Our findings reveal that LLMs ability to generate executable plans autonomously is rather limited with the best model (GPT-4) having an average success rate of ~1237; across the domains. However the results in the LLM-Modulo setting show more promise. In the LLM-Modulo setting we demonstrate that LLM-generated plans can improve the search process for underlying sound planners and additionally show that external verifiers can help provide feedback on the generated plans and back-prompt the LLM for better plan generation.

---
layout: publication
title: Towards Robots That Know When They Need Help Affordance-Based Uncertainty for Large Language Model Planners
authors: Mullen James F. Jr., Manocha Dinesh
conference: "Arxiv"
year: 2024
bibkey: mullen2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13198"}
tags: ['Applications', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) showcase many desirable traits for intelligent and helpful robots. However they are also known to hallucinate predictions. This issue is exacerbated in consumer robotics where LLM hallucinations may result in robots confidently executing plans that are contrary to user goals relying more frequently on human assistance or preventing the robot from asking for help at all. In this work we present LAP a novel approach for utilizing off-the-shelf LLMs alongside scene and object Affordances in robotic Planners that minimize harmful hallucinations and know when to ask for help. Our key finding is that calculating and leveraging a scene affordance score a measure of whether a given action is possible in the provided scene helps to mitigate hallucinations in LLM predictions and better align the LLMs confidence measure with the probability of success. We specifically propose and test three different affordance scores which can be used independently or in tandem to improve performance across different use cases. The most successful of these individual scores involves prompting an LLM to determine if a given action is possible and safe in the given scene and uses the LLMs response to compute the score. Through experiments in both simulation and the real world on tasks with a variety of ambiguities we show that LAP significantly increases success rate and decreases the amount of human intervention required relative to prior art. For example in our real-world testing paradigm LAP decreases the human help rate of previous methods by over 33 at a success rate of 70.

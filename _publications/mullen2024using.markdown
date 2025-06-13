---
layout: publication
title: 'LAP, Using Action Feasibility For Improved Uncertainty Alignment Of Large Language Model Planners'
authors: James F. Jr. Mullen, Dinesh Manocha
conference: "Arxiv"
year: 2024
bibkey: mullen2024using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13198"}
tags: ['RAG', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) showcase many desirable traits for intelligent
and helpful robots. However, they are also known to hallucinate predictions.
This issue is exacerbated in robotics where LLM hallucinations may result in
robots confidently executing plans that are contrary to user goals, relying
more frequently on human assistance, or preventing the robot from asking for
help at all. In this work, we present LAP, a novel approach for utilizing
off-the-shelf LLMs, alongside a novel Action feasibility metric, in robotic
Planners that minimize harmful hallucinations and human intervention. Our key
finding is that calculating and leveraging a new metric, which we call
A-Feasibility, a measure of whether a given action is possible and safe in the
provided scene, helps to mitigate hallucinations in LLM predictions and better
align the LLM's confidence measure with the probability of success. We
specifically propose an A-Feasibility metric which both combines scene context
and prompting a LLM to determine if a given action is possible and safe in the
scene, using the LLM's response to compute the score. Through experiments in
both simulation and the real world on tasks with a variety of ambiguities, we
show that LAP significantly increases success rate and decreases the amount of
human intervention required relative to prior art. For example, in our
real-world testing paradigm, LAP decreases the human help rate of previous
methods by over 33% at a success rate of 70%.

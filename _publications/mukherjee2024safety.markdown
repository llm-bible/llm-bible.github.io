---
layout: publication
title: 'Polaris: A Safety-focused LLM Constellation Architecture For Healthcare'
authors: Subhabrata Mukherjee, Paul Gamble, Markel Sanz Ausin, Neel Kant, Kriti Aggarwal, Neha Manjunath, Debajyoti Datta, Zhengliang Liu, Jiayuan Ding, Sophia Busacca, Cezanne Bianco, Swapnil Sharma, Rae Lasko, Michelle Voisard, Sanchay Harneja, Darya Filippova, Gerry Meixiong, Kevin Cha, Amir Youssefi, Meyhaa Buvanesh, Howard Weingram, Sebastian Bierman-lytle, Harpreet Singh Mangat, Kim Parikh, Saad Godil, Alex Miller
conference: "Arxiv"
year: 2024
bibkey: mukherjee2024safety
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.13313'}
tags: ['Agentic', 'Model Architecture', 'Applications', 'Training Techniques', 'GPT', 'Reinforcement Learning', 'Responsible AI']
---
We develop Polaris, the first safety-focused LLM constellation for real-time
patient-AI healthcare conversations. Unlike prior LLM works in healthcare
focusing on tasks like question answering, our work specifically focuses on
long multi-turn voice conversations. Our one-trillion parameter constellation
system is composed of several multibillion parameter LLMs as co-operative
agents: a stateful primary agent that focuses on driving an engaging
conversation and several specialist support agents focused on healthcare tasks
performed by nurses to increase safety and reduce hallucinations. We develop a
sophisticated training protocol for iterative co-training of the agents that
optimize for diverse objectives. We train our models on proprietary data,
clinical care plans, healthcare regulatory documents, medical manuals, and
other medical reasoning documents. We align our models to speak like medical
professionals, using organic healthcare conversations and simulated ones
between patient actors and experienced nurses. This allows our system to
express unique capabilities such as rapport building, trust building, empathy
and bedside manner. Finally, we present the first comprehensive clinician
evaluation of an LLM system for healthcare. We recruited over 1100 U.S.
licensed nurses and over 130 U.S. licensed physicians to perform end-to-end
conversational evaluations of our system by posing as patients and rating the
system on several measures. We demonstrate Polaris performs on par with human
nurses on aggregate across dimensions such as medical safety, clinical
readiness, conversational quality, and bedside manner. Additionally, we conduct
a challenging task-based evaluation of the individual specialist support
agents, where we demonstrate our LLM agents significantly outperform a much
larger general-purpose LLM (GPT-4) as well as from its own medium-size class
(LLaMA-2 70B).

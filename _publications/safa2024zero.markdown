---
layout: publication
title: 'A Zero-shot Open-vocabulary Pipeline For Dialogue Understanding'
authors: Abdulfattah Safa, Gözde Gül Şahin
conference: "Arxiv"
year: 2024
bibkey: safa2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15861"}
tags: ['Prompting', 'Tools']
---
Dialogue State Tracking (DST) is crucial for understanding user needs and
executing appropriate system actions in task-oriented dialogues. Majority of
existing DST methods are designed to work within predefined ontologies and
assume the availability of gold domain labels, struggling with adapting to new
slots values. While Large Language Models (LLMs)-based systems show promising
zero-shot DST performance, they either require extensive computational
resources or they underperform existing fully-trained systems, limiting their
practicality. To address these limitations, we propose a zero-shot,
open-vocabulary system that integrates domain classification and DST in a
single pipeline. Our approach includes reformulating DST as a
question-answering task for less capable models and employing self-refining
prompts for more adaptable ones. Our system does not rely on fixed slot values
defined in the ontology allowing the system to adapt dynamically. We compare
our approach with existing SOTA, and show that it provides up to 20% better
Joint Goal Accuracy (JGA) over previous methods on datasets like Multi-WOZ 2.1,
with up to 90% fewer requests to the LLM API.

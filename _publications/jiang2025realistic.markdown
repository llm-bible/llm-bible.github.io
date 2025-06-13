---
layout: publication
title: 'Medagentbench: A Realistic Virtual EHR Environment To Benchmark Medical LLM Agents'
authors: Yixing Jiang, Kameron C. Black, Gloria Geng, Danny Park, James Zou, Andrew Y. Ng, Jonathan H. Chen
conference: "Arxiv"
year: 2025
bibkey: jiang2025realistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.14654"}
  - {name: "Code", url: "https://github.com/stanfordmlgroup/MedAgentBench"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Applications']
---
Recent large language models (LLMs) have demonstrated significant
advancements, particularly in their ability to serve as agents thereby
surpassing their traditional role as chatbots. These agents can leverage their
planning and tool utilization capabilities to address tasks specified at a high
level. However, a standardized dataset to benchmark the agent capabilities of
LLMs in medical applications is currently lacking, making the evaluation of
LLMs on complex tasks in interactive healthcare environments challenging. To
address this gap, we introduce MedAgentBench, a broad evaluation suite designed
to assess the agent capabilities of large language models within medical
records contexts. MedAgentBench encompasses 300 patient-specific
clinically-derived tasks from 10 categories written by human physicians,
realistic profiles of 100 patients with over 700,000 data elements, a
FHIR-compliant interactive environment, and an accompanying codebase. The
environment uses the standard APIs and communication infrastructure used in
modern EMR systems, so it can be easily migrated into live EMR systems.
MedAgentBench presents an unsaturated agent-oriented benchmark that current
state-of-the-art LLMs exhibit some ability to succeed at. The best model
(Claude 3.5 Sonnet v2) achieves a success rate of 69.67%. However, there is
still substantial space for improvement which gives the community a next
direction to optimize. Furthermore, there is significant variation in
performance across task categories. MedAgentBench establishes this and is
publicly available at https://github.com/stanfordmlgroup/MedAgentBench ,
offering a valuable framework for model developers to track progress and drive
continuous improvements in the agent capabilities of large language models
within the medical domain.

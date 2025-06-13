---
layout: publication
title: 'Coding Reliable Llm-based Integrated Task And Knowledge Agents With Genieworksheets'
authors: Harshit Joshi, Shicheng Liu, James Chen, Robert Weigle, Monica S. Lam
conference: "Arxiv"
year: 2024
bibkey: joshi2024coding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05674"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT']
---
Large Language Models (LLMs) present an opportunity to create automated
assistants that can help users navigate complex tasks. However, existing
approaches have limitations in handling conditional logic, integrating
knowledge sources, and consistently following instructions. Researchers and
industry professionals often employ ad hoc pipelines to construct
conversational agents. These pipelines aim to maintain context, address failure
cases, and minimize hallucinations, yet frequently fail to achieve these
objectives. To this end, we present Genie - a programmable framework for
creating task-oriented conversational agents that are designed to handle
complex user interactions and knowledge queries. Unlike LLMs, Genie provides
reliable grounded responses, with controllable agent policies through its
expressive specification, Genie Worksheet. In contrast to dialog trees, it is
resilient to diverse user queries, helpful with knowledge sources, and offers
ease of programming policies through its declarative paradigm. The agents built
using Genie outperforms the state-of-the-art method on complex logic domains in
STARV2 dataset by up to 20.5%. Additionally, through a real-user study
involving 62 participants, we show that Genie beats the GPT-4 with function
calling baseline by 21.1%, 20.1%, and 61% on execution accuracy, dialogue act
accuracy, and goal completion rate, respectively, on three diverse real-world
domains

---
layout: publication
title: 'Memento No More: Coaching AI Agents To Master Multiple Tasks Via Hints Internalization'
authors: Minttu Alakuijala, Ya Gao, Georgy Ananov, Samuel Kaski, Pekka Marttinen, Alexander Ilin, Harri Valpola
conference: "Arxiv"
year: 2025
bibkey: alakuijala2025memento
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01562'}
tags: ['Agentic', 'Efficiency and Optimization', 'Distillation', 'GPT', 'Training Techniques', 'Model Architecture', 'Prompting', 'Applications', 'Reinforcement Learning']
---
As the general capabilities of artificial intelligence (AI) agents continue to evolve, their ability to learn to master multiple complex tasks through experience remains a key challenge. Current LLM agents, particularly those based on proprietary language models, typically rely on prompts to incorporate knowledge about the target tasks. This approach does not allow the agent to internalize this information and instead relies on ever-expanding prompts to sustain its functionality in diverse scenarios. This resembles a system of notes used by a person affected by anterograde amnesia, the inability to form new memories. In this paper, we propose a novel method to train AI agents to incorporate knowledge and skills for multiple tasks without the need for either cumbersome note systems or prior high-quality demonstration data. Our approach employs an iterative process where the agent collects new experiences, receives corrective feedback from humans in the form of hints, and integrates this feedback into its weights via a context distillation training procedure. We demonstrate the efficacy of our approach by implementing it in a Llama-3-based agent that, after only a few rounds of feedback, outperforms advanced models GPT-4o and DeepSeek-V3 in tasksets requiring correct sequencing of information retrieval, tool use, and question answering.

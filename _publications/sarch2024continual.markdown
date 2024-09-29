---
layout: publication
title: "ICAL: Continual Learning Of Multimodal Agents By Transforming Trajectories Into Actionable Insights"
authors: Sarch Gabriel, Jang Lawrence, Tarr Michael J., Cohen William W., Marino Kenneth, Fragkiadaki Katerina
conference: "Arxiv"
year: 2024
bibkey: sarch2024continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14596"}
tags: ['Agentic', 'Few Shot', 'GPT', 'In Context Learning', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Tools']
---
Large-scale generative language and vision-language models (LLMs and VLMs) excel in few-shot in-context learning for decision making and instruction following. However they require high-quality exemplar demonstrations to be included in their context window. In this work we ask Can LLMs and VLMs generate their own prompt examples from generic sub-optimal demonstrations We propose In-Context Abstraction Learning (ICAL) a method that builds a memory of multimodal experience insights from sub-optimal demonstrations and human feedback. Given a noisy demonstration in a new domain VLMs abstract the trajectory into a general program by fixing inefficient actions and annotating cognitive abstractions task relationships object state changes temporal subgoals and task construals. These abstractions are refined and adapted interactively through human feedback while the agent attempts to execute the trajectory in a similar environment. The resulting abstractions when used as exemplars in the prompt significantly improve decision-making in retrieval-augmented LLM and VLM agents. Our ICAL agent surpasses the state-of-the-art in dialogue-based instruction following in TEACh multimodal web agents in VisualWebArena and action anticipation in Ego4D. In TEACh we achieve a 12.637; improvement in goal-condition success. In VisualWebArena our task success rate improves over the SOTA from 14.337; to 22.737;. In Ego4D action forecasting we improve over few-shot GPT-4V and remain competitive with supervised models. We show finetuning our retrieval-augmented in-context agent yields additional improvements. Our approach significantly reduces reliance on expert-crafted examples and consistently outperforms in-context learning from action plans that lack such insights.

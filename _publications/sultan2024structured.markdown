---
layout: publication
title: 'Structured Chain-of-thought Prompting For Few-shot Generation Of Content-grounded QA Conversations'
authors: Md Arafat Sultan, Jatin Ganhotra, Ramón Fernandez Astudillo
conference: "Arxiv"
year: 2024
bibkey: sultan2024structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11770"}
tags: ['Agentic', 'Training Techniques', 'Few-Shot', 'Tools', 'RAG', 'Prompting']
---
We introduce a structured chain-of-thought (SCoT) prompting approach to
generating content-grounded multi-turn question-answer conversations using a
pre-trained large language model (LLM). At the core of our proposal is a
structured breakdown of the complex task into a number of states in a state
machine, so that actions corresponding to various subtasks, e.g., content
reading and utterance generation, can be executed in their own dedicated
states. Each state leverages a unique set of resources including prompts and
(optionally) additional tools to augment the generation process. Our
experimental results show that SCoT prompting with designated states for
hallucination mitigation increases agent faithfulness to grounding documents by
up to 16.8%. When used as training data, our open-domain conversations
synthesized from only 6 Wikipedia-based seed demonstrations train strong
conversational QA agents; in out-of-domain evaluation, for example, we observe
improvements of up to 13.9% over target domain gold data when the latter is
augmented with our generated examples.

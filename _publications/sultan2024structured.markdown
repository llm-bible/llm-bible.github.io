---
layout: publication
title: Structured Chain45;of45;thought Prompting For Few45;shot Generation Of Content45;grounded QA Conversations
authors: Sultan Md Arafat, Ganhotra Jatin, Astudillo Ramón Fernandez
conference: "Arxiv"
year: 2024
bibkey: sultan2024structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11770"}
tags: ['Agentic', 'Applications', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
We introduce a structured chain45;of45;thought (SCoT) prompting approach to generating content45;grounded multi45;turn question45;answer conversations using a pre45;trained large language model (LLM). At the core of our proposal is a structured breakdown of the complex task into a number of states in a state machine so that actions corresponding to various subtasks e.g. content reading and utterance generation can be executed in their own dedicated states. Each state leverages a unique set of resources including prompts and (optionally) additional tools to augment the generation process. Our experimental results show that SCoT prompting with designated states for hallucination mitigation increases agent faithfulness to grounding documents by up to 16.837;. When used as training data our open45;domain conversations synthesized from only 6 Wikipedia45;based seed demonstrations train strong conversational QA agents; in out45;of45;domain evaluation for example we observe improvements of up to 13.937; over target domain gold data when the latter is augmented with our generated examples.

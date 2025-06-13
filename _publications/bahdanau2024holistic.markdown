---
layout: publication
title: 'Tapeagents: A Holistic Framework For Agent Development And Optimization'
authors: Dzmitry Bahdanau, Nicolas Gontier, Gabriel Huang, Ehsan Kamalloo, Rafael Pardinas, Alex Piché, Torsten Scholak, Oleh Shliazhko, Jordan Prince Tremblay, Karam Ghanem, Soham Parikh, Mitul Tiwari, Quaizar Vohra
conference: "Arxiv"
year: 2024
bibkey: bahdanau2024holistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08445"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Efficiency and Optimization', 'Applications', 'Agentic', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
We present TapeAgents, an agent framework built around a granular, structured
log tape of the agent session that also plays the role of the session's
resumable state. In TapeAgents we leverage tapes to facilitate all stages of
the LLM Agent development lifecycle. The agent reasons by processing the tape
and the LLM output to produce new thought and action steps and append them to
the tape. The environment then reacts to the agent's actions by likewise
appending observation steps to the tape. By virtue of this tape-centred design,
TapeAgents can provide AI practitioners with holistic end-to-end support. At
the development stage, tapes facilitate session persistence, agent auditing,
and step-by-step debugging. Post-deployment, one can reuse tapes for
evaluation, fine-tuning, and prompt-tuning; crucially, one can adapt tapes from
other agents or use revised historical tapes. In this report, we explain the
TapeAgents design in detail. We demonstrate possible applications of TapeAgents
with several concrete examples of building monolithic agents and multi-agent
teams, of optimizing agent prompts and finetuning the agent's LLM. We present
tooling prototypes and report a case study where we use TapeAgents to finetune
a Llama-3.1-8B form-filling assistant to perform as well as GPT-4o while being
orders of magnitude cheaper. Lastly, our comparative analysis shows that
TapeAgents's advantages over prior frameworks stem from our novel design of the
LLM agent as a resumable, modular state machine with a structured
configuration, that generates granular, structured logs and that can transform
these logs into training text -- a unique combination of features absent in
previous work.

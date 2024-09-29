---
layout: publication
title: Open-ended Instructable Embodied Agents With Memory-augmented Large Language Models
authors: Sarch Gabriel, Wu Yue, Tarr Michael J., Fragkiadaki Katerina
conference: "Arxiv"
year: 2023
bibkey: sarch2023open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15127"}
  - {name: "Code", url: "https://helper-agent-llm.github.io"}
tags: ['Agentic', 'Few Shot', 'Has Code', 'Prompting', 'RAG']
---
Pre-trained and frozen large language models (LLMs) can effectively map simple scene rearrangement instructions to programs over a robots visuomotor functions through appropriate few-shot example prompting. To parse open-domain natural language and adapt to a users idiosyncratic procedures not known during prompt engineering time fixed prompts fall short. In this paper we introduce HELPER an embodied agent equipped with an external memory of language-program pairs that parses free-form human-robot dialogue into action programs through retrieval-augmented LLM prompting relevant memories are retrieved based on the current dialogue instruction correction or VLM description and used as in-context prompt examples for LLM querying. The memory is expanded during deployment to include pairs of users language and action plans to assist future inferences and personalize them to the users language and routines. HELPER sets a new state-of-the-art in the TEACh benchmark in both Execution from Dialog History (EDH) and Trajectory from Dialogue (TfD) with a 1.7x improvement over the previous state-of-the-art for TfD. Our models code and video results can be found in our projects website https://helper-agent-llm.github.io.

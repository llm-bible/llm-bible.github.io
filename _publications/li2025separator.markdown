---
layout: publication
title: 'Separator Injection Attack: Uncovering Dialogue Biases In Large Language Models Caused By Role Separators'
authors: Xitao Li, Haijun Wang, Jiang Wu, Ting Liu
conference: "Arxiv"
year: 2025
bibkey: li2025separator
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05689"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Prompting', 'Attention Mechanism']
---
Conversational large language models (LLMs) have gained widespread attention
due to their instruction-following capabilities. To ensure conversational LLMs
follow instructions, role separators are employed to distinguish between
different participants in a conversation. However, incorporating role
separators introduces potential vulnerabilities. Misusing roles can lead to
prompt injection attacks, which can easily misalign the model's behavior with
the user's intentions, raising significant security concerns. Although various
prompt injection attacks have been proposed, recent research has largely
overlooked the impact of role separators on safety. This highlights the
critical need to thoroughly understand the systemic weaknesses in dialogue
systems caused by role separators. This paper identifies modeling weaknesses
caused by role separators. Specifically, we observe a strong positional bias
associated with role separators, which is inherent in the format of dialogue
modeling and can be triggered by the insertion of role separators. We further
develop the Separators Injection Attack (SIA), a new orthometric attack based
on role separators. The experiment results show that SIA is efficient and
extensive in manipulating model behavior with an average gain of 18.2% for
manual methods and enhances the attack success rate to 100% with automatic
methods.

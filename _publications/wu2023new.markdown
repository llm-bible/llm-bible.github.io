---
layout: publication
title: 'A New Dialogue Response Generation Agent For Large Language Models By Asking Questions To Detect User''s Intentions'
authors: Siwei Wu, Xiangqing Shen, Rui Xia
conference: "Arxiv"
year: 2023
bibkey: wu2023new
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03293"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT']
---
Large Language Models (LLMs), such as ChatGPT, have recently been applied to
various NLP tasks due to its open-domain generation capabilities. However,
there are two issues with applying LLMs to dialogue tasks. 1. During the
dialogue process, users may have implicit intentions that might be overlooked
by LLMs. Consequently, generated responses couldn't align with the user's
intentions. 2. It is unlikely for LLMs to encompass all fields comprehensively.
In certain specific domains, their knowledge may be incomplete, and LLMs cannot
update the latest knowledge in real-time. To tackle these issues, we propose a
framework~*using LLM to \textbf\{E*nhance dialogue response generation by
asking questions to \textbf\{D\}etect user's \textbf\{I\}mplicit
in\textbf\{T\}entions\} (\textbf\{EDIT\}). Firstly, EDIT generates open questions
related to the dialogue context as the potential user's intention; Then, EDIT
answers those questions by interacting with LLMs and searching in
domain-specific knowledge bases respectively, and use LLMs to choose the proper
answers to questions as extra knowledge; Finally, EDIT enhances response
generation by explicitly integrating those extra knowledge. Besides, previous
question generation works only focus on asking questions with answers in
context. In order to ask open questions, we construct a Context-Open-Question
(COQ) dataset. On two task-oriented dialogue tasks (Wizard of Wikipedia and
Holl-E), EDIT outperformed other LLMs.

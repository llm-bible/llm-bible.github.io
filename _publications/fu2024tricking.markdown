---
layout: publication
title: 'Imprompter: Tricking LLM Agents Into Improper Tool Use'
authors: Xiaohan Fu, Shuheng Li, Zihan Wang, Yihao Liu, Rajesh K. Gupta, Taylor Berg-kirkpatrick, Earlence Fernandes
conference: "Arxiv"
year: 2024
bibkey: fu2024tricking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14923"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Merging', 'Security', 'Multimodal Models', 'Prompting']
---
Large Language Model (LLM) Agents are an emerging computing paradigm that
blends generative machine learning with tools such as code interpreters, web
browsing, email, and more generally, external resources. These agent-based
systems represent an emerging shift in personal computing. We contribute to the
security foundations of agent-based systems and surface a new class of
automatically computed obfuscated adversarial prompt attacks that violate the
confidentiality and integrity of user resources connected to an LLM agent. We
show how prompt optimization techniques can find such prompts automatically
given the weights of a model. We demonstrate that such attacks transfer to
production-level agents. For example, we show an information exfiltration
attack on Mistral's LeChat agent that analyzes a user's conversation, picks out
personally identifiable information, and formats it into a valid markdown
command that results in leaking that data to the attacker's server. This attack
shows a nearly 80% success rate in an end-to-end evaluation. We conduct a range
of experiments to characterize the efficacy of these attacks and find that they
reliably work on emerging agent-based systems like Mistral's LeChat, ChatGLM,
and Meta's Llama. These attacks are multimodal, and we show variants in the
text-only and image domains.

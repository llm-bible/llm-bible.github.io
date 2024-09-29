---
layout: publication
title: All in How You Ask for It Simple Black-Box Method for Jailbreak Attacks
authors: Takemoto Kazuhiro
conference: "Appl. Sci."
year: 2024
bibkey: takemoto2024all
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.09798"}
tags: ['Agent', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Security']
---
Large Language Models (LLMs) such as ChatGPT encounter jailbreak challenges wherein safeguards are circumvented to generate ethically harmful prompts. This study introduces a straightforward black-box method for efficiently crafting jailbreak prompts addressing the significant complexity and computational costs associated with conventional methods. Our technique iteratively transforms harmful prompts into benign expressions directly utilizing the target LLM predicated on the hypothesis that LLMs can autonomously generate expressions that evade safeguards. Through experiments conducted with ChatGPT (GPT-3.5 and GPT-4) and Gemini-Pro our method consistently achieved an attack success rate exceeding 80 within an average of five iterations for forbidden questions and proved robust against model updates. The jailbreak prompts generated were not only naturally-worded and succinct but also challenging to defend against. These findings suggest that the creation of effective jailbreak prompts is less complex than previously believed underscoring the heightened risk posed by black-box jailbreak attacks.

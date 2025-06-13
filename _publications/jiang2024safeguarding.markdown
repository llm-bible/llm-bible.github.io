---
layout: publication
title: 'Safeguarding System Prompts For Llms'
authors: Zhifeng Jiang, Zhihua Jin, Guoliang He
conference: "Arxiv"
year: 2024
bibkey: jiang2024safeguarding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13426"}
tags: ['Security', 'Efficiency and Optimization', 'Prompting', 'Applications']
---
Large language models (LLMs) are increasingly utilized in applications where
system prompts, which guide model outputs, play a crucial role. These prompts
often contain business logic and sensitive information, making their protection
essential. However, adversarial and even regular user queries can exploit LLM
vulnerabilities to expose these hidden prompts. To address this issue, we
propose PromptKeeper, a robust defense mechanism designed to safeguard system
prompts. PromptKeeper tackles two core challenges: reliably detecting prompt
leakage and mitigating side-channel vulnerabilities when leakage occurs. By
framing detection as a hypothesis-testing problem, PromptKeeper effectively
identifies both explicit and subtle leakage. Upon detection, it regenerates
responses using a dummy prompt, ensuring that outputs remain indistinguishable
from typical interactions when no leakage is present. PromptKeeper ensures
robust protection against prompt extraction attacks via either adversarial or
regular queries, while preserving conversational capability and runtime
efficiency during benign user interactions.
